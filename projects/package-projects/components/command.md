# @command

The `@command` decorator is a built-in injection class for register commands in the Floating Command Bar within an HTML Design Frame.

## Import

```javascript
import * as core from "/@studio/core.js"
const { decorators } = core.Packages
const { command } = decorators()
```

## Usage

```javascript
class YourComponent extends Component {
    // Component implementation
    
    @command(settings)
    method() {
        // ...
    }
}
```

## Parameters

* `settings` (object): An object containing settings for the command.
  * `caption` (string): Caption for the command.
  * `onGetActive` (string | function): Method name or function for determining the active state of the command.
  * `onGetEnabled` (string | function): Method name or function for determining the enabled state of the command.
  * `section` (string): Name of the section where the command will be registered.
  * `items` (array): An array of items to be included within the command menu.
    * `id` (string): Identifier for the item.
    * `caption` (string): Caption displayed for the item.
    * `title` (string): Title text displayed when hovering over the item.

## Example

```javascript
class QAlert extends Component {
    // Component implementation
    
    // Register a command for toggle the close button in the component
    @command({
        caption: "Dismissible",
        title: "Show/hide a close button for make the alert dismissible",
        onGetActive: "@isAlertDismissible"
    })
    toggleDismissible(command) {
        // ...
    }
    
    // Register a command menu for add content new in the component
    @command({
        section: "q-alert",
        caption: "Add",
        items: [
            {
                id: "icon",
                caption: "Icon",
                title: "Add a icon inside the alert."
            },
            {
                id: "badge",
                caption: "Badge",
                title: "Add a badge inside the alert."
            }
        ],
        onGetEnabled: "@haveContent"
    })
    async addContent(command, itemId) {
        // ...
    }
}
```

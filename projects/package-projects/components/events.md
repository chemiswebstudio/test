# @events

The `@events` decorator is a built-in injection class for defining events within an HTML Design Frame in the Node Inspector. It allows registering events with various settings and conditions for display.

## Import

```javascript
import * as core from "/@studio/core.js"
const { decorators } = core.Packages
const { events } = decorators()
```

## Usage

```javascript
class YourComponent extends Component {
    // Component implementation
    
    @events(settings, events)
}
```

## Parameters

* `settings` (object): An object containing settings parameters.
  * `displayName` (string): The name to be displayed for the events section in the inspector.
  * `processPriority` (number): The priority of the class descriptor for processing. Higher priority values mean the descriptor will be processed earlier. Defaults to `0.5`.
  * `renderPriority` (number): The priority of the class descriptor for rendering. Higher priority values mean the descriptor will be rendered earlier. Defaults to `0.5`.
  * `expanded` (boolean): Determines if the events section will be expanded by default. Defaults to `true`.
  * `help` (string): A URL linking to additional help documentation for the events section.
* `events` (object): An object defining events to be displayed within the inspector.
  * `name` (string | object): The data type of the event value. It can be a string representing the data type or an object specifying additional details about the data type.
    * `domain` (array): Specifies the domain or range of the event value.

## Example

```javascript
class QInput extends Component {
    // Component implementation
    
    // events
    @events({
        displayName: "QInput",
        help: "https://quantum.chemisweb.com/button#events"
    }, {
        "onQBlur": XEvent,
        "onQFocus": XEvent
    })
}
```

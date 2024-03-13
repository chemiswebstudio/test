# @attributes

The `@attributes` decorator is a built-in injection class for defining attributes within an HTML Design Frame in the Node Inspector. It allows registering attributes with various settings and conditions for display.

## Import

```javascript
import * as core from "/@studio/core.js"
const { decorators } = core.Packages
const { attributes } = decorators()
```

## Usage

```javascript
class YourComponent extends Component {
    // Component implementation
    
    @attributes(settings, attributes)
}
```

## Parameters

* `settings` (object): An object containing settings parameters.
  * `displayName` (string): The name to be displayed for the attributes section in the inspector.
  * `processPriority` (number): The priority of the class descriptor for processing. Higher priority values mean the descriptor will be processed earlier. Defaults to `0.5`.
  * `renderPriority` (number): The priority of the class descriptor for rendering. Higher priority values mean the descriptor will be rendered earlier. Defaults to `0.5`.
  * `expanded` (boolean): Determines if the attributes section will be expanded by default. Defaults to `true`.
  * `help` (string): A URL linking to additional help documentation for the attributes section.
* `attributes` (object): An object defining attributes to be displayed within the inspector.
  * `name` (string | object): The data type of the attribute value. It can be a string representing the data type or an object specifying additional details about the data type.
    * `domain` (array): Specifies the domain or range of the attribute's value.
    * `condition` (function): A function used to determine whether the attribute should be displayed based on some conditions. The function takes an object as an argument and returns a boolean value indicating whether the attribute should be shown.

## Example

```javascript
class QInput extends Component {
    // Component implementation
    
    // 
    @attributes({
        displayName: "QInput",
        help: "https://quantum.chemisweb.com/button"
    }, {
        "label": XString,
        "size": { type: XString, domain: ["small", "medium", "large"] },
        "disabled": { type: XBoolean, domain: [null, ""] },
        "no-spin-buttons": {
	    type: XBoolean, 
	    domain: ["false", "true"], 
	    condition: (object) => (object.type == "number")
	}
    })
}
```

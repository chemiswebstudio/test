# @component

The `@component` decorator is a built-in injection class for annotating components with 'Query Selector' and 'Palette Path', facilitating their registration. It references the class within the context.

## Import

```javascript
import * as core from "/@studio/core.js"
const { decorators } = core.Packages
const { component } = decorators()
```

## Usage

```javascript
@component(querySelector, palettePath, params)
class YourComponent extends Component {
    // Component implementation
}
```

## Parameters

* `querySelector` (string): The CSS query selector for the component.
* `palettePath` (string): The path to the palette for the component.
* `params` (object): Additional parameters for the component.

## Example

```javascript
@component(
    ".q-button", 
    "/Quantum Package/QButton", 
    { 
        imports: `
            require quantum-css
            set-facade QButton.js
            xref default QButton @studio/quantum-vcl/QButton.js --extern
            ref QButton %facade-module% --module
            restore-facade
        `
    }
)
class QButton extends Component {
    // Component implementation
}
```

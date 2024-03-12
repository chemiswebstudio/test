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
class YourComponent {
    // Component implementation
}
```

## Parameters

<table data-header-hidden><thead><tr><th width="258"></th><th></th></tr></thead><tbody><tr><td>querySelector</td><td><p>string</p><p>The CSS query selector for the component.</p></td></tr><tr><td>palettePath</td><td><p>string</p><p>The path to the palette for the component.</p></td></tr><tr><td>params</td><td><p>object</p><p>Additional parameters for the component.</p></td></tr></tbody></table>

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
class MyComponent {
    // Component implementation
}
```

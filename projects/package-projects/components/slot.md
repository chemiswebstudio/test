# @slot

The `@slot` decorator is a built-in injection class for creating slots within an HTML Design Frame. It allows registering slots with various settings for handling dropped contexts.

## Import

```javascript
import * as core from "/@studio/core.js"
const { decorators } = core.Packages
const { slot } = decorators()
```

## Usage

```javascript
class YourComponent extends Component {
    // Component implementation
    
    @slot(slotName)
    method(slot, context) {
        // ...
    }
}
```

## Parameters

* `slotName` (string): The slot name.

## Example

```javascript
class QAlert extends Component {
    // Component implementation
    
    // Register a slot named "image"
    @slot("image")
    droppedImage(slot, context) {
        slot.handleDroppedContext(context, this.getObject())
    }
}
```

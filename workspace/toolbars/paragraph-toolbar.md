# Paragraph toolbar

En la barra de herramientas **Paragraph** encontrará comandos para afectar aspectos de los parrafos de la seleccion presente en el documento. Si mantiene seleccionado un bloque en el **Inspector de Hojas de Estilos**, estos comandos modificaran directamente las declaraciones dentro del bloque en lugar de la seleccion del documento.

#### Parrafos de la seleccion:

Los parrafos de la seleccion son todos los elementos de nivel de bloque, que estan contenidos total o parcialmente en la seleccion realizada por el usuario dentro del documento, incluyendo los bloques anonimos. Para mayor comprension de estos conceptos, vease el siguiente articulo externo: [Visual Formatting Model](https://developer.mozilla.org/en-US/docs/Web/CSS/Visual\_formatting\_model).

{% hint style="success" %}
Para conocer mas detalles del comportamiento sobrecargado de los comandos consulte la pagina **Seleccion de bloque y comandos sobrecargados**.
{% endhint %}

<div>

<figure><img src="../../.gitbook/assets/toolbars-paragraph.jpg" alt=""><figcaption><p>Paragraph toolbar</p></figcaption></figure>

 

<figure><img src="../../.gitbook/assets/toolbars-paragraph-overloaded.jpg" alt=""><figcaption><p>Paragraph toolbar with commands overloaded</p></figcaption></figure>

</div>

### **Comandos de la barra:**

* **Unordered list**: This command create/modifies an unordered list of items with the paragraphs of the document selection. It does not perform any action in overload mode.
* **Ordered list**: This command create/modifies an ordered list of items with the paragraphs of the document selection. It does not perform any action in overload mode.
* **List type**: This command sets/modifies the `list-style-type` property, or its shorthand `list-style` if present. You can select one option in the menu list, or enter a custom value. In overload mode, it sets/modifies the `list-style-type` property, or its shorthand `list-style`, within the selected CSS block.
* **Indent decrease**: This command wrap outer the paragraphs of the document selection using the HTML `<blockquote>` and move it to the right of the margin. It does not perform any action in overload mode.
* **Indent increase**: This command wrap outer the paragraphs of the document selection using the HTML `<blockquote>` and move it to the left of the margin. It does not perform any action in overload mode.
* **Align left**: This command sets the `text-align` property with the `"left"` value. The action aligning to the left the paragraphs of the document selection. In overload mode, it sets the `text-align` property with the `"left"` value within the selected CSS block.
* **Align center**: This command sets the `text-align` property with the `"center"` value. The action aligning to the center the paragraphs of the document selection. In overload mode, it sets the `text-align` property with the `"center"` value within the selected CSS block.
* **Align right**: This command sets the `text-align` property with the `"right"` value. The action aligning to the right the paragraphs of the document selection. In overload mode, it sets the `text-align` property with the `"right"` value within the selected CSS block.
* **Justify content**: This command sets the `text-align` property with the `"justify"` value. The action distributes evenly the paragraphs of the document selection. In overload mode, it sets the `text-align` property with the `"justify"` value within the selected CSS block.
* **Vertical align**: This command sets/modifies the `vertical-align` property. You can select one option in the menu list, or enter a custom value. In overload mode it sets/modifies the `vertical-align` property within the selected CSS block.
* **Paragraph level**: This command allows you to switch the paragraphs of the document selection between different types of elements, such as headings of different levels (H1 to H6) , blockquotes, paragraphs or divs. It does not perform any action in overload mode.
* **Line height**: This command sets/modifies the `line-height` property. You can select one option in the menu list, or enter a custom value. In overload mode it sets/modifies the `line-height` property within the selected CSS block.
* **Float**: This command sets/modifies the `float` and `clear` properties. You can select the properties values in the menu list. In overload mode it sets/modifies the `float` and `clear` properties within the selected CSS block.
* Show a menu list that allows you to select a value and places the selected element on the left or right side of its container, allowing text and inline elements to wrap around it. Also, it contains a sub-menu list for the **Clear** property and its values.
* **Columns**: Show a menu list that allows you to select a number of columns. For set more columns and options, open the Columns generator dialog at the end of the list.
* **Flow control**: Show a menu list with sub-menus for the properties White space, Word break, Line break and Text overflow. These properties are used to manage how text is displayed within an element, including whitespace handling, how lines of text are broken, and how text overflow is handled.
* **Spacing and indentation**: Show a menu list with sub-menus for the properties Word spacing, Letter spacing and Text indent. These properties are used to control the spacing between words and letters, and the indentation of text.
* **Direction**: Show a menu list that allows you to change the direction of text, table columns, and horizontal overflow.
* **Orientation and writing mode**: Show a menu list with sub-menus for the properties Text orientation and Writing mode. These properties are used to control the orientation of characters and the direction in which lines of text are laid out.

{% hint style="warning" %}
**Propiedades shorthand**:

En CSS, ciertas propiedades se incluyen automáticamente dentro de su forma shorthand. Cuando se detecta que una propiedad está contenida en el shorthand existente, el comando no añade la propiedad, sino que modifica el valor dentro del shorthand, optimizando así la eficiencia y legibilidad del código CSS. Para mas detalles consulte el articulo externo [Shorthand properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand\_properties).
{% endhint %}

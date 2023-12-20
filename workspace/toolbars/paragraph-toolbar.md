# Paragraph toolbar

En la barra de herramientas **Paragraph** encontrará comandos para afectar aspectos de los parrafos de la seleccion presente en el documento. Si mantiene seleccionado un bloque en el **Inspector de Hojas de Estilos**, estos comandos modificaran directamente las declaraciones dentro del bloque en lugar de la seleccion del documento

#### Parrafos de la seleccion:

Los parrafos de la seleccion son todos los elementos de nivel de bloque, que estan contenidos total o parcialmente en la seleccion realizada por el usuario dentro del documento, incluyendo los bloques anonimos. Para mayor comprension de estos conceptos, vease el siguiente articulo: [Visual Formatting Model](https://developer.mozilla.org/en-US/docs/Web/CSS/Visual\_formatting\_model).

{% hint style="warning" %}
Para conocer mas detalles del comportamiento sobrecargado de los comandos consulte la pagina **Seleccion de bloque y comandos sobrecargados**.
{% endhint %}

<div>

<figure><img src="../../.gitbook/assets/toolbars-paragraph.jpg" alt=""><figcaption><p>Paragraph toolbar</p></figcaption></figure>

 

<figure><img src="../../.gitbook/assets/toolbars-paragraph-overloaded.jpg" alt=""><figcaption><p>Paragraph toolbar with commands overloaded</p></figcaption></figure>

</div>

### **Comandos de la barra:**

* **Unordered list**: Create an unordered list of items, con los parrafos de la seleccion del documento, typically rendered as a bulleted list.
* **Ordered list**: Create an ordered list of items, typically rendered as a numbered list.
* **List type**: Change the type of the list.
* **Indent decrease**: Move the paragraph to the right of the margin.
* **Indent increase**: Move the paragraph to the left of the margin.
* **Align left**: Set the inline-level content aligned to the left edge of the element or table-cell box.
* **Align center**: Set the inline-level content aligned to the center of the element or table-cell box.
* **Align right**: Set the inline-level content aligned to the right edge of the element or table-cell box.
* **Justify content**: Set the inline-level content justified. Text should be spaced to line up its left and right edges to the left and right edges of the line box, except for the last line.
* **Vertical align**: Show a menu list that allows you to select one option or enter a custom value to set vertical alignment for an inline, inline-block, or table-cell box.
* **Paragraph level**: Show a menu list that allows you to change the selected element in a different types of elements, such as headings of different levels (H1 to H6) , blockquote, paragraph or div.
* **Line height**: Show a menu list that allows you to select one option or enter a custom value to set height of a line box.
* **Float**: Show a menu list that allows you to select a value and places the selected element on the left or right side of its container, allowing text and inline elements to wrap around it. Also, it contains a sub-menu list for the **Clear** property and its values.
* **Columns**: Show a menu list that allows you to select a number of columns. For set more columns and options, open the Columns generator dialog at the end of the list.
* **Flow control**: Show a menu list with sub-menus for the properties White space, Word break, Line break and Text overflow. These properties are used to manage how text is displayed within an element, including whitespace handling, how lines of text are broken, and how text overflow is handled.
* **Spacing and indentation**: Show a menu list with sub-menus for the properties Word spacing, Letter spacing and Text indent. These properties are used to control the spacing between words and letters, and the indentation of text.
* **Direction**: Show a menu list that allows you to change the direction of text, table columns, and horizontal overflow.
* **Orientation and writing mode**: Show a menu list with sub-menus for the properties Text orientation and Writing mode. These properties are used to control the orientation of characters and the direction in which lines of text are laid out.

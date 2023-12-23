# Font toolbar

En la barra de herramientas **Font** encontrará comandos para modificar aspectos tipograficos de la seleccion presente en el documento. Si mantiene seleccionado un bloque en el **Inspector de Hojas de Estilos**, estos comandos modificaran directamente las declaraciones dentro del bloque en lugar de la seleccion del documento.&#x20;

{% hint style="success" %}
Para conocer mas detalles del comportamiento sobrecargado de los comandos consulte la pagina **Seleccion de bloque y comandos sobrecargados**.
{% endhint %}

<div>

<figure><img src="../../.gitbook/assets/toolbars-font.jpg" alt=""><figcaption><p>Font toolbar</p></figcaption></figure>

 

<figure><img src="../../.gitbook/assets/toolbars-font-overloaded.jpg" alt=""><figcaption><p>Font toolbar with commands overloaded</p></figcaption></figure>

</div>

### Comandos de la barra:

* **Font family**: This command set/modify the `font-family` property, or his shorthand `font` property if present. You can also open the [Font settings dialog](../dialogs/font-settings-dialog.md) for configuring other font options (`font-size`, `line-height`, `font-weight`). In overloaded mode, this command set/modify `font-family` property, or his shorthand `font` property in the CSS selected block.
* **Font size**: This command set/modify the `font-size` property or his shorthand `font` property if present. You can select one option of the list, or enter a custom value. In overloaded mode, this command set/modify `font-size`property, or his shorthand `font` property in the CSS selected block.
* **Font size increment**: This command set/modify the `font-size` property or his shorthand `font` property if present. The action increase in one the value of the font size. It does not perform any action in overload mode.
* **Font size decrement**: This command set/modify the `font-size` property or his shorthand `font` property if present. The action decrease in one the value of the font size. It does not perform any action in overload mode.
* **Text transform**: This command allows you to choose how to capitalize a text. It can be used to make text appear in all-uppercase or all-lowercase, invert case, sentece or with each word capitalized. It does not perform any action in overload mode.
* **Bold**: Apply bold formatting.
* **Italic**: Apply italic formatting.
* **Underline**: Apply underline formatting.
* **Line through**: Apply the line format through the middle.
* **Overline**: Apply the line format above.
* **Subscript**: Specify inline text which should be displayed as subscript for solely typographical reasons. Subscripts are typically rendered with a lowered baseline using smaller text. Este comando no presenta sobrecarga.
* **Superscript**: Specify inline text which is to be displayed as superscript for solely typographical reasons. Superscripts are usually rendered with a raised baseline using smaller text.
* **Color**: Show a picker for select the color value of an element's text and text decorations. For more colors and options, open the [Color dialog](../dialogs/color-dialog.md) at the end of the picker.
* **Background color**: Show a picker for select the background color value. For more colors and options, open the [Color dialog](../dialogs/color-dialog.md) at the end of the picker.
* **Text shadow**: bla bla bla

{% hint style="warning" %}
**Propiedades shorthand**:

En CSS, ciertas propiedades se incluyen automáticamente dentro de su forma shorthand. Cuando se detecta que una propiedad está contenida en el shorthand existente, el comando no añade la propiedad, sino que modifica el valor dentro del shorthand, optimizando así la eficiencia y legibilidad del código CSS. Para mas detalles consulte el articulo externo [Shorthand properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand\_properties).
{% endhint %}

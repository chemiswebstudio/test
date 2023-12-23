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

* **Font family**: This command sets/modifies the `font-family` property, or its shorthand `font` if present. You can also open the [Font settings dialog](../dialogs/font-settings-dialog.md) for configuring other font options (`font-size`, `line-height`, `font-weight`). In overload mode, it sets/modifies the `font-family` property, or its shorthand `font`, within the selected CSS block.
* **Font size**: This command sets/modifies the `font-size` property, or its shorthand `font` if present. You can select one option of the list, or enter a custom value. In overload mode, it sets/modifies the `font-size` property, or its shorthand `font`, within the selected CSS block.
* **Font size increment**: This command sets/modifies the `font-size` property, or its shorthand `font` if present. The action increase in one the value of the font size. It does not perform any action in overload mode.
* **Font size decrement**: This command sets/modifies the `font-size` property, or its shorthand `font` if present. The action decrease in one the value of the font size. It does not perform any action in overload mode.
* **Text transform**: This command allows you to choose how to capitalize a text. It can be used to make text appear in all-uppercase or all-lowercase, invert case, sentece or with each word capitalized. It does not perform any action in overload mode.
* **Bold**: This command applies bold formatting using the HTML `<strong>` tag. In overload mode, it applies the `font-weight` property, or its shorthand `font`, within the selected CSS block.
* **Italic**: This command applies italic formatting using the HTML `<em>` tag. In overload mode, it applies the `font-style` property, or its shorthand `font`, within the selected CSS block.
* **Underline**: This command applies underlined formatting using the HTML `<u>` tag. In overload mode, it applies the `text-decoration-line` property, or its shorthand `text-decoration`, within the selected CSS block.
* **Line through**: This command applies line through formatting using the HTML `<s>` tag. In overload mode, it applies the `text-decoration-line` property, or its shorthand `text-decoration`, within the selected CSS block.
* **Overline**: This command applies overline formatting using the CSS `text-decoration-line` property, or its shorthand `text-decoration` if present. In overload mode, it applies the `text-decoration-line` property, or its shorthand `text-decoration`, within the selected CSS block.
* **Subscript**: This command transforms text to a subscript using the HTML `<sub>` tag. Subscripts are typically rendered with a lowered baseline using smaller text. It does not perform any action in overload mode.
* **Superscript**: This command transforms text to a superscript using the HTML `<sup>` tag. Superscripts are usually rendered with a raised baseline using smaller text. It does not perform any action in overload mode.
* **Color**: This command sets/modifies the `color` property. The action displays a color picker for selecting the color value of an element's text and text decorations. You can also open the [Color dialog](../dialogs/color-dialog.md) to configure other color options. In overload mode, it sets/modifies the `color` property within the selected CSS block.
* **Background color**: This command sets/modifies the `background-color` property, or its shorthand `background` if present. The action displays a color picker for selecting the background color value of an element. You can also open the [Color dialog](../dialogs/color-dialog.md) to configure other background color options. In overload mode, it sets/modifies the `background-color` property, or its shorthand `background`,  within the selected CSS block.
* **Text shadow**: bla bla bla

{% hint style="warning" %}
**Propiedades shorthand**:

En CSS, ciertas propiedades se incluyen automáticamente dentro de su forma shorthand. Cuando se detecta que una propiedad está contenida en el shorthand existente, el comando no añade la propiedad, sino que modifica el valor dentro del shorthand, optimizando así la eficiencia y legibilidad del código CSS. Para mas detalles consulte el articulo externo [Shorthand properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand\_properties).
{% endhint %}

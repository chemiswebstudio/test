# Drag & Drop from Directory Manager

El administrador de directorios permite arrastrar y soltar ficheros sobre el documento que tenga el foco en el Marco de Diseño. La versatilidad de esta acción se refleja en la variedad de opciones disponibles, las cuales se ajustan dinámicamente según el tipo de archivo que se arrastra y el tipo de documento sobre el cual se realiza el soltado.

## Dragging CSS file

* **Drop over HTML document:** Enlaza mediante una etiqueta \<link> el fichero.css dentro de la etiqueta \<head> del documento HTML.

## Dragging JS file

* **Drop over HTML document:** Muestra un dialogo que permite elegir el tipo de script que se insertará dentro de la etiqueta \<head> del documento HTML.

<figure><img src="../../../.gitbook/assets/drag js over html.jpg" alt=""><figcaption><p>Embbeding JavaScript file over HTML document</p></figcaption></figure>

* **Drop over JS document:** Muestra un dialogo que permite elegir el tipo de importacion que se insertara en el documento JavaScript. Estas importaciones siguen el formato de los modulos de JavaScript, para conocer más detalles sobre el tema, puede leer el siguiente articulo externo: [JavaScript Import Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)

<figure><img src="../../../.gitbook/assets/drag js over js.jpg" alt=""><figcaption><p>Importing JavaScript module over JavaScript document</p></figcaption></figure>

## Dragging multimedia files(image, audio, video)

* **Drop over HTML document:** Inserta el fichero multimedia utilizando la etiqueta HTML correspondiente para su representación.
* **Drop over component slot:** Inserta la URL del recurso multimedia en el atributo sloteado del componente previamente seleccionado.

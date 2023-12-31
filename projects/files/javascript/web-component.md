# Web Component

Un web component es un conjunto de tecnologías web que permiten la creación de elementos personalizados reutilizables en HTML y JavaScript. Es decir, son bloques de código que encapsulan cierta funcionalidad y se pueden utilizar en distintas partes de una página web o de una aplicación. Los web components permiten la creación de componentes personalizados con sus propios estilos, comportamientos y propiedades. Para mas detalles consulte el articulo externo [Web Components](https://developer.mozilla.org/en-US/docs/Web/API/Web\_components).

<div align="center">

<figure><img src="../../../.gitbook/assets/new web component.jpg" alt=""><figcaption><p>New Web Component file</p></figcaption></figure>

</div>

1. **Tag name:** Permite introducir el nombre de la etiqueta del nuevo componente web que se creará. Este nombre debe estar formado por al menos dos palabras separadas por un guion.
2. **Component class name:** Permite introducir el nombre de la clase que se creará para el nuevo componente web.
3. **Base class:** Permite introducir el nombre de la clase base de la cual se extenderá el componente web. Por defecto, se extiende de HTMLElement, una clase que sirve como base para cualquier elemento HTML. Al heredar esta clase, el componente web obtendrá todas las características de un elemento HTML estándar.
4. **Directory & File name:** Permite elegir la ruta de destino donde desee guardar el archivo y establecer un nombre para el mismo.
5. **Disconnected callback:** Al activar, permite agregar al codigo el metodo `disconnectedCallback()`, este metodo es parte de la API de Web Components y se llama cuando un componente personalizado se elimina del DOM (Document Object Model). Es útil para realizar tareas de limpieza o liberar recursos cuando el componente ya no está conectado a la página web.
6. **Adopted callback:** Al activar, permite agregar al codigo el metodo `adoptedCallback()`, este metodo también es parte de la API de Web Components. Se invoca cuando un componente personalizado es adoptado por un nuevo documento. Puede ser útil para manejar acciones específicas cuando el componente es movido o "adoptado" por otro documento.&#x20;
7. **Attribute changed callback:** Al activar, permite agregar al codigo el metodo `attributeChangedCallback()`, este metodo tambien es parte de la API de Web Components. Se llama cuando los atributos del componente personalizado son modificados. Permite reaccionar a cambios en los atributos y realizar acciones correspondientes, como actualizar el estado interno del componente en base a esos cambios.&#x20;
8. **Export class:** Al activar, permite agregar al final del código una declaración de exportación de la clase del componente web.

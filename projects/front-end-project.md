# Front-End Project

Un Proyecto Front-End representa una entidad organizativa que abarca el desarrollo de interfaces de usuario y experiencias visuales. En este tipo de proyecto se pueden construir estructuras como páginas web estáticas, aplicaciones web dinámicas, páginas de destino (landing pages), portafolios y otras estructuras visuales.

## Creando un nuevo proyecto Front-End

1. Haga clic en el botón de menú FILE, seleccione la opción Front-End Project (empty) y presione el botón Continuar.
2. Introduzca el nombre del proyecto y luego haga clic en el botón Create.
   * Por defecto, se propone un scaffolding recomendado para una mejor experiencia de desarrollo en el IDE. Sin embargo, si lo desea, puede seleccionar la opción de crear un scaffolding vacío.
3. A continuación, seleccione la página HTML principal de su proyecto y presione el botón Continuar.
   * Puede elegir crear una nueva página HTML en blanco o una página basada en alguna de las plantillas disponibles.
4. Finalmente, puede editar el título de la nueva página HTML, el nombre del archivo y la ruta que tendrá en su proyecto.
   * Por defecto, la opción para habilitar el [WDK](broken-reference) (Web Development Kit) estará activada y podrá editar el nombre de la clase controladora, el nombre del archivo y la ruta que tendrá en su proyecto.

{% hint style="info" %}
**Sobre el WDK**:

Recomendamos el uso del [WDK](broken-reference) ya que está construido para brindar una experiencia de desarrollo más eficiente, rapida y cómoda.
{% endhint %}

<div align="left">

<figure><img src="../.gitbook/assets/new_front_end_project.jpg" alt=""><figcaption><p>Video gif creando un nuevo proyecto</p></figcaption></figure>

</div>

## Scaffolding de un proyecto Front-End

Al crear un nuevo proyecto y seleccionar el scaffolding por defecto, la estructura de archivos y directorios proporcionada como punto de partida es la que se muestra a continuación:

{% code title="Scaffolding by default" fullWidth="false" %}
```
├── .compiler
├── build
├── libs
│   └── @wdk
├── src
│   ├── components
│   ├── dialogs
│   ├── frames
│   ├── res
│   └── index.js
├── .front-end-project
└── index.html
```
{% endcode %}

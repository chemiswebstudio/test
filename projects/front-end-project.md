# Front-End Project

Un Proyecto Front-End representa una entidad organizativa que abarca el desarrollo de interfaces de usuario y experiencias visuales. En este tipo de proyecto se pueden construir estructuras como páginas web estáticas, aplicaciones web dinámicas, páginas de destino (landing pages), portafolios y otras estructuras visuales.

## Creando un nuevo proyecto Front-End

1. Haga clic en el botón de menú **FILE**, seleccione la opción **Front-End Project (empty)** y presione el botón **Continuar**.
2. Introduzca el nombre para su proyecto.&#x20;
3. Seleccione el [scaffolding](https://en.wikipedia.org/wiki/Scaffold\_\(programming\)) deseado. Se propone un scaffolding recomendado por defecto para una mejor experiencia de desarrollo en el IDE, sin embargo, puede seleccionar la opción de crear un scaffolding vacío.
4. Haga clic en el botón **Create**.

{% hint style="info" %}
Una vez completado el paso anterior, su proyecto habra sido creado satisfactoriamente. Posteriormente, se mostrara de forma automatica el dialogo de creacion de Paginas HTML para continuar con la creacion de la primera pagina de su proyecto si asi lo desea. Vease el **articulo Files / New HTML Page....**
{% endhint %}

<div align="left">

<figure><img src="../.gitbook/assets/new_front_end_project.jpg" alt=""><figcaption><p>Video gif creando un nuevo proyecto</p></figcaption></figure>

</div>

## Scaffolding por defecto

Al crear un nuevo proyecto y seleccionar el scaffolding por defecto, la estructura de archivos y directorios proporcionada como punto de partida es la que se muestra a continuación:

{% code title="Scaffolding by default" fullWidth="false" %}
```
├── .compiler
├── build
├── libs
├── src
│   ├── components
│   ├── dialogs
│   ├── frames
│   └── res
└── .front-end-project
```
{% endcode %}

1. **.compiler:** Carpeta destinada a contener los archivos creados para un [perfil de compilación](files/compiler-profiles/). Los perfiles de compilación se pueden crear haciendo clic en el botón **New** de la barra de herramientas **Project** y seleccionando el tipo de perfil a crear en la lista de menú de archivos.
2. **build: C**arpeta destinada a almacenar los archivos optimizados y listos para la implementación en producción generados después de compilar el código fuente del proyecto.
3. **libs:** Carpeta contenedora de las bibliotecas y/o dependencias externas utilizadas en el proyecto.
4. **src:** Carpeta que generalmente contiene el código fuente del proyecto. Puede contener las siguientes subcarpetas:
   * **components:** Carpeta destinada a contener componentes reutilizables de la interfaz de usuario.
   * **dialogs:** Carpeta destinada a contener los archivos relacionados con la creación de cuadros de diálogos y modales.
   * **frames:** Carpeta destinada a contener los archivos relacionados con la creación de marcos o estructuras más grandes.
   * **res:** Carpeta destinada a contener los recursos como imágenes, fuentes, iconos, etc.
5. **.front-end-project:** Archivo principal del proyecto. Su contenido interno es presentado en formato XML, conteniendo informacion sobre el proyecto tales como nombre y tipo, así como los [Perfiles de Compilación](files/compiler-profiles/) creados.


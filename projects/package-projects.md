# Package Projects

Los Proyectos Paquetes son enfocados a la creación de componentes y extensiones que posteriormente podrán ser activados en el IDE. Cuando un paquete está activo, es cargado inmediatamente durante el proceso de inicialización del IDE.

## Creando un nuevo proyecto Paquete

1. Haga clic en el botón de menú **FILE**, seleccione la opción **Package Project** y presione el botón **Continuar**.
2. Ingrese el nombre de su paquete. Automáticamente, se asignará un nombre a la clase principal del paquete y se definirá la ruta del archivo fachada. Podrá modificar estas asignaciones si así lo desea.
3. Haga clic en el botón **Create**.

<figure><img src="../.gitbook/assets/new_front_end_project.jpg" alt=""><figcaption><p>Video gif creando un nuevo proyecto paquete</p></figcaption></figure>

## Scaffolding

Al crear un nuevo proyecto paquete, la estructura de archivos y directorios proporcionada como punto de partida es la que se muestra a continuación:

{% code title="Scaffolding" %}
```
├── .compiler
├── build
├── libs
├── src
│   ├── components
├── autoload.js
└── .package-project
```
{% endcode %}

# Components

Los componetes de un paquete definen plantillas y funcionalidades que seran interpretadas por el IDE. Los mismo son registrados en el Administrador de Componentes para su posterior uso en los proyectos Front-End

## Puntos a tener en cuenta para la creacion de un componente

* **Importacion base del core:** Es fundamental iniciar el desarrollo de un componente importando las funcionalidades básicas del core del sistema.
* **Definicion y registro:** Para definir y registrar un componente en el paquete, se utiliza el decorador `@component`. Este permite asignar un nombre de clase o etiqueta al componente, así como especificar la ruta de su paquete. Dicha configuración hace que el componente se muestre correctamente en el Administrador de Paquetes.
* **Declaracion de la clase:** La clase del componente que contendra todos sus metodos.
* **Registro de comandos:** A traves del decorador `@command` se posibilita el registro de acciones y la addicion de funciones y logica avanzada en el componente.
* **Registro de slots:** Usando el decorador `@slot` se pueden agregar slots al componente.
* **Registro de atributos y eventos:** Mediante el uso de los decoradores `@attributes` y `@events` es posible registrar atributos y eventos en el Inspector de Nodos.
* **Renderizado:** El metodo `html()` de un componente es usado para definir y renderizar la plantilla del componente.
* **Exportacion de la clase:** Exporta el nombre de la clase del componente para su posterior importacion y registro en el archivo principal del paquete.

## Ejemplo de un componente

```javascript

import * as core from "/@studio/core.js"
const { Component, decorators } = core.Packages
const { component, attributes} = decorators()

// -- MyComponent
@component(
    "*", 
    "MyFirstPackage/MyComponent", {
        imports: `
        `
    }
)
class MyComponent extends Component {

    async html(){
    	return ""
    }
}

export {
	MyComponent
}

```
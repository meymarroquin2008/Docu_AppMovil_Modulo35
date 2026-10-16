# Arquitectura de UniRoute

## 1. Descripción general

UniRoute es un proyecto orientado a facilitar la consulta de información sobre rutas y apoyar a los usuarios durante la navegación.

La aplicación busca organizar la información necesaria para que los usuarios puedan consultar rutas y acceder a las funcionalidades disponibles mediante una interfaz clara y sencilla.

La arquitectura del sistema depende de los componentes, las tecnologías y los mecanismos de almacenamiento implementados en el proyecto.

## 2. Tecnologías utilizadas

El proyecto UniRoute cuenta con documentación técnica y una interfaz web para consultar sus manuales y guías.

Las tecnologías específicas de la aplicación deben identificarse a partir del código fuente del proyecto.

Para completar esta sección, se deben verificar los siguientes elementos:

- Lenguaje de programación utilizado.
- Framework o biblioteca de desarrollo.
- Herramientas de construcción y ejecución.
- Mecanismo de almacenamiento de datos.
- Servicios externos, si existen.
- Herramientas de publicación y despliegue.

La documentación web del proyecto está publicada mediante GitHub Pages.

## 3. Arquitectura de la aplicación

La arquitectura de UniRoute se describe mediante los componentes que intervienen en la interacción con el usuario y el procesamiento de la información.

Los principales elementos funcionales son:

- **Interfaz de usuario:** permite acceder a las funcionalidades disponibles.
- **Lógica de aplicación:** procesa las acciones y valida la información recibida.
- **Gestión de rutas:** organiza o consulta los datos relacionados con los trayectos, según las funciones implementadas.
- **Gestión de datos:** permite acceder a la información necesaria mediante el mecanismo de almacenamiento utilizado.
- **Servicios externos:** pueden intervenir si el proyecto integra servicios de mapas, ubicación o consultas remotas.

La presencia y la tecnología específica de cada componente deben confirmarse mediante la revisión del código fuente.

## 4. Almacenamiento de datos

La gestión de datos de UniRoute depende de la implementación del proyecto.

La información que podría utilizar una aplicación de rutas incluye:

- Puntos de origen y destino.
- Datos relacionados con los trayectos.
- Preferencias del usuario.
- Información complementaria para la navegación.

Estos elementos son ejemplos de información posible y no confirman que todos se almacenen de manera persistente.

El mecanismo de almacenamiento, la estructura de los datos y las claves utilizadas deben documentarse según el código real de UniRoute.

## 5. Flujo principal

El flujo general de consulta de una ruta puede describirse de la siguiente manera:

1. El usuario accede a UniRoute.
2. Consulta las opciones disponibles en la interfaz.
3. Selecciona o introduce el origen.
4. Selecciona o introduce el destino.
5. La aplicación procesa la consulta.
6. Se obtiene la información disponible para el trayecto.
7. Se presentan los resultados al usuario.
8. El usuario consulta la información de la ruta.

Este flujo representa el proceso funcional general. Los pasos específicos pueden variar según las funcionalidades implementadas.

## 6. Diagramas relacionados

La arquitectura de UniRoute se complementa con documentación técnica y diagramas que permiten comprender el funcionamiento del sistema.

Entre los documentos relacionados se encuentran:

- **Diagrama de casos de uso:** representa las interacciones entre los usuarios y el sistema.
- **Diagrama de secuencia:** muestra el orden de las interacciones durante una operación.
- **Arquitectura y despliegue:** describe la organización de los componentes y la publicación del proyecto.
- **Manual de usuario UX:** explica la navegación y el uso de las funcionalidades disponibles.

Los archivos correspondientes se encuentran en la carpeta de documentación del proyecto. Las ubicaciones de las imágenes y diagramas deben comprobarse en el repositorio.

## 7. Limitaciones

La documentación de UniRoute debe distinguir entre las funcionalidades implementadas y las mejoras que podrían incorporarse posteriormente.

Entre los aspectos que deben verificarse se encuentran:

- La existencia de un Backend independiente.
- La utilización de una API externa.
- El almacenamiento local o remoto de información.
- La integración de servicios de mapas.
- La obtención de la ubicación del dispositivo.
- La disponibilidad de información de rutas en tiempo real.

No se deben considerar implementadas las funciones anteriores sin comprobarlas en el código fuente.

El objetivo de esta documentación es describir fielmente la arquitectura de UniRoute y facilitar su comprensión, mantenimiento y evolución.
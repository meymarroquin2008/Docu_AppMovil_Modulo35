# Manual Técnico de Despliegue e Infraestructura - UniRoute

## 1. Arquitectura de Despliegue

UniRoute es un proyecto orientado a facilitar la consulta de información relacionada con rutas y la navegación de los usuarios. Su arquitectura de despliegue depende de las tecnologías utilizadas en la implementación.

Para documentar su funcionamiento, se consideran los siguientes componentes:

- **Capa de Presentación (Frontend):** interfaz con la que interactúa el usuario para consultar la información y utilizar las funcionalidades disponibles.
- **Capa de Lógica de Aplicación:** procesa las acciones del usuario, valida los datos y organiza la información necesaria para las operaciones del sistema.
- **Capa de Datos:** administra la información que necesita la aplicación mediante el mecanismo de almacenamiento que utilice el proyecto.

La utilización de un servidor Backend independiente, una API REST o una base de datos externa debe confirmarse mediante la revisión del código fuente.

## 2. Requisitos Mínimos de Infraestructura

Los requisitos dependen de las tecnologías empleadas y del entorno en el que se ejecute UniRoute.

### Para consultar la documentación web

- **Dispositivo:** computadora, tableta o teléfono inteligente.
- **Navegador:** versión actualizada de un navegador compatible.
- **Conexión a Internet:** necesaria para acceder al sitio publicado.
- **Resolución de pantalla:** adaptable al dispositivo utilizado.
- **Acceso al sitio:** dirección web de la documentación publicada.

### Para desarrollar y mantener el proyecto

- **Procesador (CPU):** compatible con las herramientas de desarrollo utilizadas.
- **Memoria RAM:** suficiente para ejecutar el editor, las dependencias y las herramientas del proyecto.
- **Almacenamiento:** espacio disponible para el código fuente, las dependencias, los recursos multimedia y los archivos de documentación.
- **Sistema operativo:** compatible con el entorno de desarrollo utilizado.

No se establecen cantidades específicas de memoria RAM, almacenamiento o capacidad de procesamiento porque deben determinarse según las tecnologías y herramientas reales de UniRoute.

## 3. Publicación de la Documentación

La documentación de UniRoute está publicada mediante GitHub Pages.

El proceso general de publicación es el siguiente:

1. Modificar los archivos de documentación.
2. Guardar los cambios en el repositorio.
3. Confirmar los cambios mediante Git.
4. Subir los cambios al repositorio remoto.
5. Verificar la publicación del sitio web.
6. Comprobar que las páginas, imágenes y enlaces funcionen correctamente.

La dirección del portal de documentación es:

https://meymarroquin2008.github.io/Docu_AppMovil_Modulo35/

## 4. Requisitos de Red

Para consultar el portal publicado se necesita una conexión a Internet y acceso al servicio de GitHub Pages.

La configuración de puertos, direcciones IP públicas y reglas de firewall depende del entorno de alojamiento.

No es necesario afirmar que UniRoute utiliza un servidor PostgreSQL o que mantiene abierto el puerto 5432 si estos componentes no forman parte de su implementación.

## 5. Consideraciones de Seguridad

Para mantener la documentación y el proyecto en condiciones adecuadas, se recomienda:

- Mantener actualizado el repositorio.
- Revisar los cambios antes de publicarlos.
- No incluir contraseñas, tokens ni credenciales privadas en los archivos.
- Comprobar que los enlaces publicados sean correctos.
- Verificar los archivos multimedia antes de presentar el proyecto.
- Mantener organizados los manuales y recursos de documentación.

## 6. Verificación del Despliegue

Después de publicar los cambios, se deben realizar las siguientes comprobaciones:

1. Abrir el portal desde un navegador.
2. Verificar que la página principal cargue correctamente.
3. Revisar los enlaces del menú de navegación.
4. Comprobar la visualización de imágenes y diagramas.
5. Verificar el acceso al videotutorial.
6. Revisar la sección de preguntas frecuentes.
7. Confirmar que el contenido corresponda al proyecto UniRoute.

## 7. Resumen

El despliegue de la documentación de UniRoute permite que los usuarios consulten los manuales técnicos y las guías de uso desde un sitio web.

La publicación mediante GitHub Pages facilita el acceso a la documentación sin necesidad de instalarla localmente.

La infraestructura específica de la aplicación debe documentarse de acuerdo con las tecnologías, los servicios y los mecanismos de almacenamiento realmente utilizados en el proyecto.
# ImmerseXperience

## Características Principales
- **Tracking de Superficie Interactivo:** Al iniciar la experiencia en AR, ImmerseXperience utiliza un avanzado sistema de tracking para mapear y detectar superficies en tu entorno. Esto permite que puedas interactuar y colocar objetos virtuales de forma precisa y fluida.
  
- **Añadir Objetos con un Clic:** Una vez que el sistema de tracking detecta una superficie, simplemente haz clic en el área marcada para agregar flores virtuales. Cada clic añade una flor al entorno, permitiéndote crear y personalizar tu propia experiencia AR.

## Instalación
No se requiere instalación adicional. Si experimentas problemas al ejecutar la experiencia en la web, puedes descargar este archivo HTML y ejecutarlo en un servidor local. Simplemente configura un servidor local para su uso.

## Uso
- Abre el archivo `index.html` en un navegador web que admita WebXR.
- Haz clic en el botón "Start ImmerseXperience" para iniciar la experiencia WebXR.

## Tecnologías utilizadas
- [three.js](https://threejs.org/): Biblioteca JavaScript para crear y mostrar gráficos 3D en un navegador web.
- [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API): API para renderizar gráficos 2D y 3D en un navegador web.
- [WebXR](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API): API para la creación de experiencias de realidad extendida (XR) en la web.

## Estructura del código
- `index.html`: Archivo HTML principal que contiene la estructura de la página web.
- Estilos CSS y JavaScript están incluidos directamente en el archivo HTML para facilitar la comprensión del código.

## Funcionalidades principales
- Inicia una sesión WebXR inmersiva para experiencias de realidad aumentada (AR).
- Carga modelos 3D y los muestra en el entorno AR.
- Permite colocar objetos 3D en el espacio AR utilizando la función de selección.

## Ejemplo de Uso

```html
<button class="start-button" onclick="activateXR()">Start ImmerseXperience</button>

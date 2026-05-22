# I-HOMOTIC — Visualizador 3D

Visualizador interactivo en 3D para modelos arquitectónicos (formato `.glb`). Está diseñado para ofrecer una experiencia limpia, profesional y de alto rendimiento, similar a Sketchfab, pero embebido directamente y enfocado en la estética de marca de **I-HOMOTIC**.

## 🌟 Características Principales

* **Renderizado de Alta Calidad:** Utiliza el motor WebGL a través de Three.js para renderizar geometría compleja directamente en el navegador.
* **Soporte de Compresión Avanzado:** Compatible con modelos comprimidos utilizando tanto **Draco** como **Meshopt Decoder**, lo que permite cargar archivos de gran tamaño optimizados.
* **Iluminación Realista:** Implementa un entorno HDR de estudio profesional (Studio Small 09) utilizando `RGBELoader` para reflejos precisos y sombras suaves.
* **Diseño UI "Glassmorphism":** Interfaz elegante con fondo de halos radiales, tipografía limpia (Sora) y botones flotantes, adaptada a la identidad visual oscura y minimalista de I-HOMOTIC.
* **Optimización Inteligente para Móviles:** Detecta dispositivos móviles automáticamente para limitar la densidad de píxeles, desactivar sombras costosas y remover el antialiasing, garantizando un framerate fluido sin sobrecalentar el dispositivo.

## 🎮 Controles de Interacción

La cámara está configurada con `OrbitControls` y el visualizador detecta el dispositivo para ofrecer los gestos correctos. Existe un menú de ayuda integrado en la barra superior.

**En Desktop (Computadora):**
* **Rotar:** Clic izquierdo sostenido + arrastrar.
* **Zoom:** Rueda del ratón (Scroll).
* **Mover (Pan):** Clic derecho sostenido + arrastrar.

**En Móvil (Pantalla táctil):**
* **Rotar:** Deslizar con un dedo.
* **Zoom:** Pellizcar con dos dedos.
* **Mover (Pan):** Deslizar con dos dedos.

## 🛠️ Herramientas de la Interfaz

La barra inferior cuenta con herramientas rápidas para manipular la vista:
1. **Centrar y Rotar:** Regresa la cámara a su posición inicial, pone el objetivo en el centro del modelo y reanuda la auto-rotación.
2. **Alternar Fondo (Toggle Background):** Cambia entre el fondo estilizado abstracto de I-HOMOTIC y el entorno fotográfico de estudio (Ciclorama).
3. **Pantalla Completa:** Expande el lienzo para cubrir toda la pantalla, ideal para exhibiciones o stands.

## 💻 Stack Tecnológico

El proyecto es totalmente "Vanilla" (sin frameworks pesados de frontend) para garantizar la carga más rápida posible.

* **HTML5 / CSS3**
* **JavaScript (ES6 Modules)**
* **Three.js (v0.170)**
* Servido íntegramente a través del CDN **jsDelivr** (No requiere `npm install` ni carpetas `node_modules`).

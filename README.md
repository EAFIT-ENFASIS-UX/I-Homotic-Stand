# I-HOMOTIC — Visualizador 3D

Visualizador interactivo de modelos 3D (GLB) construido con **Three.js** desde **jsDelivr CDN**.

## Stack

- **Three.js v0.170** — Motor 3D (cargado vía jsDelivr CDN)
- **HTML + CSS + JS** — Sin frameworks, sin build tools
- **GitHub Pages** — Hosting estático gratuito

## Uso

Abrir `index.html` en un navegador o servir con cualquier servidor estático.

### Controles

| Acción | Control |
|--------|---------|
| Rotar | Clic izquierdo + arrastrar |
| Zoom | Scroll |
| Mover | Clic derecho + arrastrar |
| Pantalla completa | Botón inferior derecho |

## Deploy en GitHub Pages

1. Crear repositorio en GitHub
2. Subir archivos:
   ```bash
   git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
   git push -u origin main
   ```
3. Ir a **Settings → Pages → Source → main branch**
4. Tu visualizador estará en `https://TU_USUARIO.github.io/TU_REPO/`

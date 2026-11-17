# Visor 3D Entorno UNAL - GitHub Pages

Página web interactiva construida con **Three.js** y **WebGL** diseñada para visualizar modelos 3D y entornos en cualquier navegador (PC y móviles), optimizada para hospedarse gratis en **GitHub Pages**.

## 🚀 Características
- **Carga de modelos `.glb` / `.gltf`:** Compatible con compresión **Draco** para carga ultrarrápida.
- **Controles de cámara completos:**
  - 🖱️ Clic izquierdo: Rotar cámara.
  - ✋ Clic derecho: Paneo / Desplazamiento.
  - 🔍 Rueda del mouse / Pellizco en móviles: Zoom in/out.
- **Barra de herramientas interactiva:**
  - 🔄 Reiniciar vista a la perspectiva óptima.
  - 🧭 Vista aérea cenital instantánea.
  - 🌀 Modo auto-rotación 360°.
  - 📐 Inspección en modo malla (Wireframe).
  - ☀️ Alternancia de iluminación (Día, Atardecer, Noche).
  - ⛶ Modo Pantalla Completa.
- **Centrado automático:** Calcula la caja envolvente (Bounding Box) del modelo y ajusta automáticamente la distancia y foco de la cámara sin importar el tamaño del modelo.
- **Previsualización instantánea:** Puedes arrastrar cualquier archivo `.glb` directamente a la pantalla en tu navegador para probarlo.

---

## 📦 Cómo publicar en GitHub Pages (Paso a Paso)

1. **Crear repositorio en GitHub:**
   - Entra a [github.com/new](https://github.com/new).
   - Nómbralo (por ejemplo: `entorno-unal-3d`).
   - Elige **Público** (Public) y dale a **Create repository**.

2. **Subir los archivos:**
   - Sube:
     - `index.html`
     - `Unal.glb` (el modelo 3D exportado).
   - Puedes subirlos directamente arrastrándolos en la web de GitHub usando el botón **"Add file" > "Upload files"** o mediante comandos Git:
     ```bash
     git init
     git add .
     git commit -m "Publicar visor 3D UNAL"
     git branch -M main
     git remote add origin https://github.com/TU-USUARIO/entorno-unal-3d.git
     git push -u origin main
     ```

3. **Activar GitHub Pages (Gratis):**
   - En tu repositorio de GitHub, haz clic en la pestaña **Settings** (Configuración).
   - En el menú lateral izquierdo, haz clic en **Pages**.
   - En **Build and deployment > Source**, selecciona **Deploy from a branch**.
   - En **Branch**, selecciona `main` y la carpeta `/(root)`, luego haz clic en **Save**.

4. **¡Listo!**
   - En 1 o 2 minutos, GitHub te dará el enlace público:  
     `https://TU-USUARIO.github.io/entorno-unal-3d/`

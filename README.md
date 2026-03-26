# Retiro Interior — Guía PWA

Guía de trabajo interior pre y post retiro con plantas sagradas.

## Cómo publicar en GitHub Pages

### Paso 1 — Crear el repositorio

1. Ve a [github.com/new](https://github.com/new)
2. Nombre: `retiro-interior` (o el que prefieras)
3. Marca **Public**
4. Haz clic en **Create repository**

### Paso 2 — Subir los archivos

Opción A — desde la interfaz web de GitHub:
1. En el repositorio, haz clic en **Add file → Upload files**
2. Sube todos los archivos de esta carpeta:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Haz clic en **Commit changes**

Opción B — desde terminal:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/retiro-interior.git
git push -u origin main
```

### Paso 3 — Activar GitHub Pages

1. En tu repositorio ve a **Settings → Pages**
2. En "Source" selecciona **main** branch, carpeta **/ (root)**
3. Haz clic en **Save**
4. En ~2 minutos tu app estará en:
   `https://TU_USUARIO.github.io/retiro-interior`

### Instalar como PWA en el celular

**iPhone (Safari):**
1. Abre la URL en Safari
2. Toca el botón de compartir ⬆
3. Selecciona "Agregar a pantalla de inicio"
4. Confirma — ya está instalada como app

**Android (Chrome):**
1. Abre la URL en Chrome
2. Aparece automáticamente un banner "Agregar a pantalla de inicio"
3. O ve al menú ⋮ → "Instalar app"

La app funciona offline una vez instalada.

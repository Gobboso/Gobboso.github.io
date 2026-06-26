# Gabriel García — Portfolio

Portfolio personal de Gabriel García, Desarrollador de Software Junior.

## 🚀 Cómo publicar en GitHub Pages

### Paso 1 — Crear el repositorio en GitHub
1. Ve a [github.com/new](https://github.com/new)
2. Nombre del repositorio: `Gobboso.github.io` (exactamente así, con tu username)
3. Márcalo como **Public**
4. No marques ninguna opción adicional
5. Clic en **Create repository**

### Paso 2 — Subir los archivos

Opción A — Desde la web (más fácil):
1. Entra al repositorio recién creado
2. Clic en **Add file → Upload files**
3. Arrastra el archivo `index.html`
4. Clic en **Commit changes**

Opción B — Desde terminal con Git:
```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/Gobboso/Gobboso.github.io.git
git branch -M main
git push -u origin main
```

### Paso 3 — Activar GitHub Pages
1. Ve a **Settings** del repositorio
2. En el menú izquierdo: **Pages**
3. En **Source**: selecciona **main** branch y carpeta **/ (root)**
4. Clic en **Save**

### Paso 4 — Tu sitio está listo 🎉
Después de ~2 minutos estará disponible en:
```
https://Gobboso.github.io
```

## 📝 Personalizar proyectos
Abre `index.html` y busca la sección `<!-- PROJECTS -->`.
Cada tarjeta tiene esta estructura:

```html
<a class="project-card" href="URL_DEL_REPO" target="_blank" rel="noopener">
  ...
  <div class="project-name">Nombre del Proyecto</div>
  <div class="project-desc">Descripción breve.</div>
  <div class="project-tags">
    <span class="project-tag">Tecnología</span>
  </div>
</a>
```

Reemplaza los 4 proyectos de ejemplo con tus repos reales de GitHub.

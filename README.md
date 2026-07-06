# Portafolio — Juan Guzmán

Página estática de un solo archivo (`index.html`, sin build step) con:
- Trayectoria profesional (Visiting Galapagos, Hexnex, Fuerzas Armadas, CNE)
- Proyectos de desarrollo (Calipso Dive, TurismoV1, Fundar Galápagos, Dental CRM, etc.)
- Documentos legales y compliance (Reglamento Interno, contrato IBE)
- Formación académica (Derecho — UIDE, curso de drones)

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `juanguzman-portfolio`.
2. Sube este `index.html` a la raíz del repositorio (puedes arrastrarlo desde la web de GitHub, o con git):
   ```bash
   git init
   git add index.html README.md
   git commit -m "Portafolio inicial"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/juanguzman-portfolio.git
   git push -u origin main
   ```
3. En el repositorio: **Settings → Pages → Source → Deploy from a branch → main / (root)** → Save.
4. En un par de minutos tu portafolio queda publicado en:
   `https://TU_USUARIO.github.io/juanguzman-portfolio/`

## Actualizar contenido

Todo el contenido (proyectos, trayectoria, textos) está directamente en el HTML, dentro de bloques `<div class="card">...</div>` para proyectos y `<div class="tl-item">...</div>` para trayectoria. Puedes copiar un bloque existente y editar el texto para agregar un proyecto nuevo — no requiere reconstruir nada.

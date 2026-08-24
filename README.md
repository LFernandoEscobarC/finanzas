# Econometría — material de curso

Sitio del curso, construido con Jekyll (GitHub Pages lo publica solo).

## Cómo publicarlo

1. Creá un repo **público** en GitHub llamado `econometria`.
2. Subí todo el contenido de esta carpeta a la raíz del repo.
3. **Settings → Pages** → Source: `Deploy from a branch` → rama `main` → `/ (root)`.
4. Tu curso queda publicado en:
   **https://lufesc.github.io/econometria/**
   (y ya está enlazado desde `docencia.md` de tu sitio principal)

## Cómo agregar una clase nueva

1. Duplicá la carpeta `clases/clase-2/` y renombrala, por ejemplo `clases/clase-3/`.
2. Editá `index.md` adentro: cambiá el título, el `permalink`
   (`/clases/clase-3/`) y el contenido de Explicación / Práctica guiada /
   Práctica independiente.
3. Subí tus archivos (PDF, datasets, scripts) a `materiales/`.
4. Agregá la tarjeta de la nueva clase en el `index.md` de la raíz,
   copiando el bloque `<li class="class-item">...</li>` de una clase existente.

## Estructura

```
index.md                 → temario general
clases/clase-1/index.md  → contenido de cada clase
materiales/               → PDFs, datasets, scripts
_config.yml               → configuración del sitio
_layouts/default.html     → plantilla visual
assets/css/style.css      → estilos (compartidos con el sitio principal)
```

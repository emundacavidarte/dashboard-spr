# Dashboard de Vacunación SPR — Cuidador 360°

Tablero interactivo de monitoreo nominal de la vacunación contra **Sarampión, Paperas y Rubéola (SPR)** de la población objetivo del **Programa Nacional Cuna Más (PNCM – MIDIS)**, niñas y niños de 0 a menor de 36 meses.

## Contenido del repositorio

- **`index.html`** — Aplicación completa y autocontenida en un solo archivo. Se abre en cualquier navegador moderno; no requiere servidor ni conexión a internet.
- **`.nojekyll`** — Indica a GitHub Pages que publique el sitio sin procesarlo con Jekyll.
- **`README.md`** — Este archivo.

## Fuentes de datos

- Padrón oficial PNCM — abril 2026 (modalidades SAF y SCD).
- Base HIS MINSA — marzo 2026.

## Publicar en GitHub Pages

1. Subir los tres archivos a la raíz del repositorio.
2. Ir a **Settings → Pages** y seleccionar la rama de publicación y la carpeta raíz (`/`).
3. El tablero quedará disponible en la URL de GitHub Pages del repositorio.

## Notas técnicas

- La edad de cada niña o niño se calcula de forma dinámica al día de consulta.
- Todas las cifras responden a los filtros activos y al Modo Emergencia Sanitaria.
- La cobertura se mide según el criterio del MINSA (Ficha Técnica N°06).
- Diseño responsivo: optimizado para escritorio y teléfono móvil.

---

Programa Nacional Cuna Más — MIDIS · UOAI · CGSE

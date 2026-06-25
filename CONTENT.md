# Edicion de contenido

La home ahora separa contenido de presentacion:

- `_home_panels/`: banner principal y bloque de inscripcion.
- `_home_galleries/`: galerias de fotos y sus listas de imagenes.
- `_home_spotlights/`: bloques destacados con imagen lateral y texto en Markdown.
- `_team_sections/`: titulos y orden de las secciones del equipo.
- `_team_members/`: una persona por archivo, con bio en Markdown y metadatos en front matter.
- `_includes/home/`: templates Liquid/HTML que renderizan cada bloque.

Reglas practicas:

- Si queres cambiar texto, links o orden, hacelo primero en las colecciones Markdown.
- Si queres cambiar la estructura visual pero mantener el contenido, tocá `_includes/home/`.
- `index.html` ahora solo compone las secciones del home.

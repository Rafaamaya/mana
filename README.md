# Maná — Sitio web (Proyecto DW1)

Sitio web estático dedicado a la banda **Maná**, desarrollado como proyecto para la materia **Desarrollo Web. Incluye páginas informativas, discografía, formulario de contacto y recursos multimedia.

## Demo local (cómo verlo)

No requiere servidor ni dependencias.

1. Abrí `index.html` en el navegador (doble click o “Open with…”).
2. Opción universal (Windows/macOS/Linux): **VS Code + Live Server** (recomendado si querés evitar instalar Python).

  - Instalá Visual Studio Code.
  - Instalá la extensión **Live Server**.
  - Abrí la carpeta del proyecto en VS Code.
  - Click derecho sobre `index.html` → **Open with Live Server**.

3. Alternativa: servidor con Python (si lo tenés instalado):

```bash
# desde la carpeta del proyecto
python3 -m http.server 5500
```

Luego abrí: `http://localhost:5500/`

## Páginas

- `index.html`: Home / presentación general, secciones informativas y multimedia.
- `discografia.html`: Discografía.
- `formulario.html`: Formulario de contacto.
- `gracias.html`: Página de confirmación / agradecimiento.

## Estructura del proyecto

```text
mana/
  index.html
  discografia.html
  formulario.html
  gracias.html

  css/
    common.css
    index.css
    discografia.css
    formulario.css
    gracias.css

  img/
    (imágenes y recursos gráficos)

```

## Tecnologías y criterios aplicados

- **HTML5 semántico** (estructura por secciones, citas, listas, etc.).
- **CSS3**: layout responsive, grid, estilos por página + estilos compartidos.
- **Multimedia embebida** (videos YouTube y mapa).
- **JS/Librerías** (si aplica en el proyecto): integración de galería (jQuery + Fancybox).

## Notas

- Íconos/redes y estilos globales se encuentran centralizados en `css/common.css`.

## Autor

- Nombre: Rafael amaya
- Curso/Materia: DW1
- Año: 2026

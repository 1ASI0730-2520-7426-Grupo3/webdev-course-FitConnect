# Guion Lección 4 - CSS básico: `:root`, variables y selectores

**Objetivo: que el estudiante practique:**
- Crear una **paleta con nombres de color** usando `:root` y **variables** (`--bg`, `--text`, `--brand`, `--muted`, `--accent`).
- Aplicar **selectores por etiqueta** (`body`, `h1`, `p`, `a`, `img`), **clase** (`.subtitulo`) e **id** (`#presentacion`, `#recursos`).
- Mejorar **legibilidad**: tipografía, interlineado, ancho máximo y centrado.
- Hacer la **imagen responsiva** con `max-width: 100%`.
- Mostrar **accesibilidad** con `:focus`.

**Pasos sugeridos:**
1. Abrir `starter-files/lesson4/index.html` en el editor online (CodePen/JSFiddle) y el panel **CSS** vacío.
2. En el CSS, crear `:root` con variables de color **por nombre**:  
   `--bg: white; --text: black; --muted: dimgray; --brand: royalblue; --accent: orange;`
3. Agregar el “reset suave”:  
   `html { box-sizing: border-box; }` y `*, *::before, *::after { box-sizing: inherit; }`.
4. En `body`, aplicar **tipografía compatible**, `line-height: 1.6`, `margin: 0`, `color: var(--text)` y `background: var(--bg)`.
5. Centrar el contenido con `main { max-width: 860px; margin: 24px auto; padding: 0 16px; }`.
6. Estilizar `header` y `footer` **sin decoraciones avanzadas**: `background: whitesmoke;` y `padding` básico; en `footer` usar `color: var(--muted)`.
7. Estilizar títulos y párrafos:  
   `h1 { color: var(--brand); font-size: 2rem; }`, `h2 { font-size: 1.35rem; }`, `p { margin-bottom: 12px; }`.  
   Crear `.subtitulo { color: var(--muted); }`.
8. Estilizar enlaces accesibles: `a { color: var(--brand); text-decoration: underline; } a:hover { text-decoration: none; }`.
9. Hacer imágenes **responsivas**: `img { max-width: 100%; height: auto; display: block; }`.
10. Pequeños ajustes por **id** (solo separación): `#presentacion`, `#recursos` con `margin-top`.
11. Accesibilidad con `:focus { outline: 3px solid var(--accent); outline-offset: 2px; }` y probar con la tecla **Tab**.
12. (Mini reto) Cambiar **solo** `--brand` y observar el efecto global en títulos y enlaces.
13. Mostrar la solución final en `completed-examples/lesson4-CSS_Basics.html`.
# Guion Lección 6 - Mini proyecto: página personal sencilla

**Objetivo: que el estudiante practique:**
- Integrar **HTML + CSS básico** (variables con nombre, tipografía, enlaces, listas, imagen responsiva).
- Estructurar secciones: **Sobre mí**, **Proyectos**, **Contacto**.
- Aplicar **legibilidad** y **accesibilidad** (`:focus`) en una página completa.

**Pasos sugeridos:**
1. Abrir `starter-files/lesson6/index.html` y el CSS base (puede derivar del de la Lección 4).
2. En `:root`, mantener variables por **nombre**:  
   `--bg: white; --text: black; --muted: dimgray; --brand: royalblue; --accent: orange;`.
3. Base general: `body` con tipografía legible, `line-height: 1.6`, colores desde variables, `margin: 0`.
4. Cabecera: `header { padding: 16px; background: whitesmoke; }`, `h1 { color: var(--brand); }`, `.subtitulo { color: var(--muted); }` (si se usa).
5. Contenedor de contenido: `main { max-width: 860px; margin: 24px auto; padding: 0 16px; }`.
6. Sección **Sobre mí**:  
   - Añadir 3–4 líneas de presentación.  
   - Insertar una imagen con `img { max-width: 100%; height: auto; display: block; }`.
7. Sección **Proyectos**:  
   - Crear una lista (`<ul>`) con 2–3 proyectos, cada uno con una frase breve.  
   - Asegurar `ul { padding-left: 20px; }` y `li { margin: 6px 0; }`.
8. Sección **Contacto**:  
   - Añadir un `mailto:` (p. ej., `<a href="mailto:tu_correo@ejemplo.com">` …).  
   - Estilizar enlaces como en L4: `a { color: var(--brand); text-decoration: underline; } a:hover { text-decoration: none; }`.
9. Accesibilidad: añadir `:focus { outline: 3px solid var(--accent); outline-offset: 2px; }` y probar navegación con **Tab**.
10. Revisión móvil rápida: reducir el ancho del panel/editor y verificar que el texto e imágenes **no se desbordan**.
11. (Mini reto) Cambiar `--brand` a `blue` o `teal` y comprobar el impacto en títulos y enlaces; agregar un tercer proyecto.
12. Mostrar la solución final en `completed-examples/lesson6-Mini_Proyecto.html`.
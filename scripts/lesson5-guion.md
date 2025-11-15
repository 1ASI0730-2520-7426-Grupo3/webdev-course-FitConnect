# Guion Lección 5 - CSS: Box Model (contenido, padding, borde, margin)

**Objetivo: que el estudiante practique:**
- Comprender el **Box Model**: contenido, `padding`, `border`, `margin`.
- Aplicar **bordes simples** usando nombres de color (p. ej., `gainsboro`).
- Diferenciar **espacio interno** (padding) vs **espacio externo** (margin).
- Mantener la página legible (ancho, interlineado, tipografía).

**Pasos sugeridos:**
1. Abrir `starter-files/lesson5/index.html` (bloques tipo `.bloque`) y el CSS asociado.
2. Definir variables mínimas en `:root` (por **nombre**):  
   `--bg: white; --text: black; --brand: royalblue; --muted: dimgray; --line: gainsboro;`.
3. Asegurar el “reset suave” (`box-sizing`) y base de `body` (tipografía, `background`, `color`, `margin: 0`).
4. Dar estructura ligera: `header { padding }`, `h1 { color: var(--brand) }`, `main { max-width: 860px; margin: 24px auto; padding: 0 16px; }`.
5. Explicar el **Box Model** en `.bloque` **propiedad por propiedad**:  
   - `background: whitesmoke;` → color de **contenido**.  
   - `padding: 12px;` → **espacio interno** (el texto se separa del borde).  
   - `border: 1px solid var(--line);` → **borde** sutil alrededor.  
   - `margin: 10px 0;` → **espacio externo** entre bloques.
6. Demostración práctica: aumentar `padding` a `24px` y ver que crece hacia **adentro**; luego `margin` a `24px 0` y ver que crece hacia **afuera**.
7. Ajustar `h2 { margin-bottom: 12px; }` para separar el título de los bloques.
8. (Opcional) Crear `.bloque.importante` con `border: 2px solid royalblue; padding: 16px;` y comparar con `.bloque` normal.
9. (Mini reto) Cambiar `--line` en `:root` a `lightgray` y observar cómo **todos** los bordes cambian a la vez.
10. Mantener enlaces del documento con el estilo básico heredado de la lección 4 (si aplica).
11. Mostrar la solución final en `completed-examples/lesson5-Box_Model.html`.
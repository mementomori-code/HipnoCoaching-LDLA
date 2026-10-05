# Tareas de Setting — tablero por día

Tablero publicado: https://claude.ai/artifact/1oZC11u9JxM2yuC1cewyfp
Fuente de la página: [`tablero.html`](tablero.html).

## Cómo funciona
1. Braian manda una grabación (link de Fathom o transcripción).
2. Claude la analiza, actualiza la ficha del setter en `setters/` y **carga en el
   tablero las tareas de ese día** (fecha de la llamada).
3. Braian marca lo que resuelve y deja una nota de ejecución en cada tarea.
   Lo marcado queda guardado en el tablero (no en el navegador).

## Modelo de datos (base del tablero)
- `dias/<AAAA-MM-DD>` — `fecha`, `titulo`, `resumen`, `grabaciones[] {nombre, url}`.
- `tareas/d<AAAAMMDD>-<nn>` — `fecha`, `setter` (Equipo, Yaris, Kelly, Rosario,
  Brenda, Tobías), `titulo`, `detalle`, `prioridad` (alta/media/baja), `plazo`,
  `orden`, `done`, `doneAt`, `nota`.

## Cargado hasta ahora
| Día | Origen | Tareas |
|---|---|---|
| 2026-09-29 | Entrevistas 1:1 Yaris, Rosario, Kelly | 21 |
| 2026-09-30 | Definición de alcance (Brenda, Tobías) | 3 |
| 2026-10-05 | Daily del equipo ([nota](../equipo/dailies/2026-10-05.md)) | 11 (Equipo) |

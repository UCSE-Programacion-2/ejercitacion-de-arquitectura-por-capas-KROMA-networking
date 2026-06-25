---
title: "Paso 3: Búsquedas Especializadas"
labels: "auto-issue"
---

Para llevar la API al siguiente nivel, necesitamos formas de filtrar la información.

## Tareas

- [ ] **GET /partidos/torneo/:torneo**: Permite obtener todos los partidos de un torneo específico.
- [ ] **GET /partidos/equipo/:equipo**: Permite obtener todos los partidos en los que haya jugado un equipo específico (ya sea como local `home_team` o visitante `away_team`).
  * _Pista: en MongoDB puedes usar el operador `$or` para buscar en múltiples campos a la vez._
- [ ] **GET /partidos/fecha/:fechaInicio-:fechaFin**: Permite obtener los partidos que se jugaron en un rango de fechas determinado (ej. `2021-01-01-2021-12-31`).

¡Al finalizar estas tareas, habrás completado la ejercitación!

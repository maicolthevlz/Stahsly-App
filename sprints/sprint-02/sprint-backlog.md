# 🏃 Sprint 2 — Cierre del flujo principal

## 📌 Estado

**Estado:** 🔄 En curso  
**Objetivo:** cerrar los pendientes que separan a Stashly de un flujo principal sólido y consistente.

> Nota: el tablero Jira actual de KAN está configurado como tablero simple/Kanban y no admite sprints nativos. Este documento conserva la planificación Scrum del proyecto hasta que Jira se migre o habilite para Scrum.

---

## 🎯 Objetivo del Sprint

Completar y validar:

1. filtros de búsqueda;
2. cambio y fallback de fuentes;
3. prueba de disponibilidad de providers;
4. continuidad de reproducción;
5. experiencia responsive;
6. organización de Mi Stash.

---

## 📋 Historias

### HU02 — Filtrar resultados — 🔄 En curso

- Filtrar por tipo de contenido.
- Filtrar por provider.
- Mantener la consulta al cambiar filtros.
- Estado vacío cuando no existan coincidencias.

### HU05 — Cambiar fuente de reproducción — 👀 En revisión

- Mostrar fuentes disponibles.
- Identificar la fuente activa.
- Permitir cambio manual.
- Ofrecer fallback cuando una fuente falle.
- No exponer errores técnicos crudos al usuario.

### HU13 — Probar una fuente — 👀 En revisión

- Probar disponibilidad/conexión.
- Mostrar estado comprensible.
- Aislar fallos por provider.
- No alterar configuración al probar.

### HU15 — Continuar reproducción — 👀 En revisión

- Persistir progreso cuando el provider/formato lo permita.
- Retomar desde la posición guardada.
- Mostrar progreso visual.
- Retirar contenidos finalizados de “Continuar”.

### HU18 — Experiencia responsive — 🔄 En curso

- Desktop con navegación lateral.
- Mobile con navegación inferior.
- Estados de carga/error/empty state.
- Controles táctiles adecuados.
- Consistencia visual del design system.

### HU10 — Organizar Mi Stash — ⏳ Por hacer

- Filtrar por tipo.
- Ordenar por nombre/fecha.
- Mantener una biblioteca usable con muchos elementos.

---

## ✅ Criterio de cierre del Sprint

El Sprint se considera terminado cuando el flujo:

```text
Buscar
→ filtrar
→ abrir detalle
→ reproducir
→ cambiar/fallback de fuente
→ continuar reproducción
→ guardar offline
→ cola
→ Mi Stash
```

funcione de forma coherente en escritorio y móvil, con errores controlados y sin depender de una única fuente.

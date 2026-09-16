# ESTADO — Memoria compartida entre PC casa y PC trabajo

> Lee esto al empezar. Actualízalo al terminar. Siempre push.

## Proyecto
Vender ebooks. Dos vías en paralelo, en **chats separados**, mismo repo y misma rama `main`:
- **Vía 1 — ebook propio** → carpeta `ebook-propio/`
- **Vía 2 — reventa / PLR** → carpeta `reventa-plr/`

Regla: cada chat toca SOLO su carpeta. `CLAUDE.md` y `docs/ESTADO.md` son comunes a ambos.

## Última sesión
- **Fecha**: 2026-09-16
- **Equipo**: PC trabajo (Claude Code web)
- **Rama**: main

## Qué se hizo
- `CLAUDE.md`: reglas de estilo + protocolo de sincronización entre los 2 PCs.
- `main` creada como rama principal.
- `ebook-propio/BRIEF.md` y `reventa-plr/BRIEF.md`: briefs de cada vía.

## Pendiente / siguiente paso
- [ ] **Vía 1**: validar indice del PLAN-02 y empezar a escribir (Fase B)
- [ ] **Vía 2**: abrir chat nuevo y arrancar por `reventa-plr/BRIEF.md`
- [ ] Cambiar la rama por defecto a `main` en GitHub (Settings → General)

## Decisiones tomadas
- Sincronización entre equipos vía GitHub, no conexión directa PC↔PC.
- Un solo repo y una sola rama (`main`); la separación es por carpetas, no por ramas.
- Plataforma de venta tentativa: Payhip (gratis, sin mensualidad).

## Actualización 2026-09-16 (vía 1)
- Nicho definido: **inspección QA/QC de soldadura y pintura** (autor es inspector QA/QC).
- Creados 3 planes completos en `ebook-propio/planes/`. Se ejecutan en serie: **02 activo**, luego 01, luego 03.
- `ebook-propio/ROADMAP.md`: cartera, fases comunes e infraestructura.
- **Restricción legal**: prohibido copiar normas (AWS/ASME/ISO/API/AMPP) o material confidencial del empleador. Se cita y se explica con palabras propias.

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
- [ ] **Vía 1**: responder las 3 preguntas de `ebook-propio/BRIEF.md` (definir nicho)
- [ ] **Vía 2**: abrir chat nuevo y arrancar por `reventa-plr/BRIEF.md`
- [ ] Cambiar la rama por defecto a `main` en GitHub (Settings → General)

## Decisiones tomadas
- Sincronización entre equipos vía GitHub, no conexión directa PC↔PC.
- Un solo repo y una sola rama (`main`); la separación es por carpetas, no por ramas.
- Plataforma de venta tentativa: Payhip (gratis, sin mensualidad).

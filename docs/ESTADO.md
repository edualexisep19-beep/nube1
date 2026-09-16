# ESTADO — Memoria compartida

> Lee esto al empezar cualquier chat. Actualízalo al terminar. Siempre `git push`.

**Última actualización**: 2026-09-16 · PC trabajo (Claude Code web) · rama `main`

---

## 1. El proyecto
Vender ebooks. Dos vías en paralelo, en **chats separados**, mismo repo y misma rama `main`:

| Vía | Qué es | Carpeta | Chat |
|-----|--------|---------|------|
| 1 | Ebook propio (nicho QA/QC) | `ebook-propio/` | Chat A |
| 2 | Reventa / PLR | `reventa-plr/` | Chat B |

**Regla**: cada chat toca SOLO su carpeta. `CLAUDE.md` y `docs/ESTADO.md` son comunes.

---

## 2. Dónde vamos

### Vía 1 — Ebook propio ▸ EN MARCHA
- **Nicho**: inspección QA/QC de soldadura y pintura. El autor es inspector QA/QC.
- **Producto activo**: *Manual práctico del inspector de soldadura y pintura* (PLAN-02).
- **Avance**: índice validado (12 caps) + front matter + **capítulo 1 escrito**.
- **Siguiente**: escribir capítulo 2 (los documentos).
- En backlog, con plan completo: PLAN-01 (de soldador a inspector) y PLAN-03 (lectura de planos).

### Vía 2 — Reventa / PLR ▸ SIN EMPEZAR
- **Siguiente**: abrir chat nuevo y arrancar por `reventa-plr/BRIEF.md`.

### Infraestructura ▸ PENDIENTE
- [ ] Cambiar la rama por defecto a `main` en GitHub (Settings → General)
- [ ] Crear cuenta en Payhip
- [ ] Crear perfil público en redes (no personal)

---

## 3. Decisiones tomadas (no volver a discutir)
1. Sincronización entre PC casa y PC trabajo **vía GitHub**. No hay conexión directa PC↔PC.
2. **Un repo, una rama (`main`)**. La separación es por carpetas, no por ramas.
3. Plataforma de venta: **Payhip** (gratis, sin mensualidad, entrega automática).
4. Los 3 ebooks se ejecutan **en serie** (02 → 01 → 03) y al final se venden como pack.
5. **Restricción legal permanente**: prohibido copiar texto, tablas o figuras de normas (AWS, ASME, ISO, API, AMPP/SSPC) y prohibido usar material confidencial del empleador. Se cita la cláusula y se explica con palabras propias. Detalle en `ebook-propio/ROADMAP.md`.

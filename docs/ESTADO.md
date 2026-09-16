# ESTADO — Memoria compartida entre PC casa y PC trabajo

> Lee esto al empezar. Actualízalo al terminar. Siempre push.

## Última sesión
- **Fecha**: 2026-09-16
- **Equipo**: PC trabajo (Claude Code web)
- **Rama**: claude/brave-lamport-7sg2qf

## Qué se hizo
- Creada la **vía 2 — reventa de ebooks PLR** en `reventa-plr/`.
- Documentos: `README.md`, `PLAN.md` (5 fases), `fuentes-plr.md`, `checklist-licencia.md`, `canales-venta.md`.
- Plantillas: ficha de producto, descripción de venta, secuencia de email.
- Scaffold `productos/_plantilla/` para cada ebook en curso.
- **`ANALISIS.md`**: análisis de mercado con datos verificados (proveedores y precios reales,
  políticas de KDP/Etsy/Payhip/Gumroad, nichos, números de arranque).
- Publicado como página web consultable desde el móvil (incluye comparador de margen por canal):
  **https://claude.ai/artifact/SzKp2fQHfxLkRJx9CZ6c2Y**

## Pendiente / siguiente paso
- [ ] Abrir cuenta **gratis en PLR.me** (10 créditos/mes = 1 ebook) y evaluar calidad real.
- [ ] Elegir nicho: finanzas personales localizadas o IA para una profesión concreta.
- [ ] Verificar en la licencia el **permiso de traducción** antes de traducir nada.
- [ ] Rellenar `checklist-licencia.md` antes de publicar nada.
- [ ] Abrir tienda en **Payhip** (5%, gestiona IVA UE).
- [ ] Vía 1 (`ebook-propio/`) sin empezar — se trabaja en otro chat.

## Decisiones tomadas
- La sincronización entre equipos es vía GitHub, no conexión directa.
- `CLAUDE.md` se carga automáticamente en Claude Code (web y local).
- Dos vías separadas por carpeta: `ebook-propio/` (vía 1) y `reventa-plr/` (vía 2). Cada chat toca solo la suya.
- Ningún PLR se publica sin el checklist de licencia completo.
- Comprar **PLR editable**, no MRR (el MRR se revende idéntico → saturación y guerra de precios).
- La ventaja competitiva es **traducir y adaptar EN→ES**: 6.315 ebooks PLR en inglés vs ~27 en español.
- Canal inicial **Payhip**, no KDP ni Etsy (ambos rechazan contenido PLR poco diferenciado).
- El artifact se actualiza pasando su URL como `url` desde cualquier sesión; sin `url` se crea otro distinto.

---
### Plantilla para la próxima sesión
```
## Última sesión
- Fecha / Equipo / Rama:
## Qué se hizo
-
## Pendiente
- [ ]
```

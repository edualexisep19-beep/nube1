# nube1

Repositorio puente entre **PC de casa** (Claude Code local) y **PC de trabajo** (Claude Code web).
Proyecto: venta de ebooks.

## Empieza aquí
1. `CLAUDE.md` → reglas de estilo y protocolo. Se carga solo en cada sesión.
2. `docs/ESTADO.md` → dónde vamos y qué sigue. **Léelo primero.**

## Estructura
```
nube1/
├── CLAUDE.md                 Reglas para Claude (estilo + sincronización)
├── docs/
│   └── ESTADO.md             Memoria compartida entre chats y equipos
├── ebook-propio/             VÍA 1 — ebook propio (nicho QA/QC)
│   ├── BRIEF.md              Nicho, público, promesa, precio
│   ├── ROADMAP.md            Cartera de 3 ebooks, fases y reglas legales
│   ├── planes/               Un plan completo por cada ebook
│   ├── manuscrito/           El libro que se está escribiendo
│   └── plantillas/           Bonus editables (checklists, NCR, informes)
└── reventa-plr/              VÍA 2 — reventa de ebooks PLR
    └── BRIEF.md
```

## Regla de oro
`git pull origin main` al empezar · `git push` al terminar.

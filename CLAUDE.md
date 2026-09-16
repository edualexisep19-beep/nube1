# CLAUDE.md — Reglas del proyecto

## 1. Estilo de respuesta (OBLIGATORIO en todo chat)
- Responde **extremadamente resumido**. Español.
- Formato por defecto: **máx. 5 bullets** o **máx. 5 líneas**. Sin introducciones ni despedidas.
- Nada de "Claro", "Perfecto", "Voy a...". Ve directo al resultado.
- Sin resúmenes largos de lo que hiciste: 1 línea de qué cambió + archivos tocados.
- Si hay pasos, numéralos. Si hay código, solo el fragmento necesario.
- Amplía SOLO si pido "detalle", "explícame" o "largo".
- Si algo es ambiguo: elige la opción sensata y avísame en 1 línea. No preguntes de más.

## 2. Contexto de trabajo (2 equipos)
- **PC trabajo**: sin permisos de instalación → uso Claude Code en la web (claude.ai/code). Corre en la nube.
- **PC casa**: Claude Code instalado local (CLI).
- **Puente entre ambos = este repositorio GitHub** (`edualexisep19-beep/nube1`). No hay conexión directa PC↔PC.

## 3. Protocolo de sincronización
1. Toda sesión (web o local) trabaja en una rama y **hace push** al terminar.
2. Al **iniciar** sesión en cualquier equipo: `git pull` primero.
3. Al **cerrar** sesión: actualizar `docs/ESTADO.md` + commit + push.
4. `docs/ESTADO.md` es la memoria compartida: lo que la sesión anterior dejó pendiente.
5. Nunca dejar trabajo sin pushear: el contenedor de la web se borra.

## 4. Comandos rápidos
```bash
git pull origin main          # al empezar
git add -A && git commit -m "msg" && git push -u origin <rama>   # al terminar
```

## 5. Reglas técnicas
- Commits en español, claros, en imperativo.
- No crear Pull Request salvo que lo pida explícitamente.
- No inventar dependencias ni archivos fuera de lo pedido.

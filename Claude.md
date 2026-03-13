# Claude Code — [PROYECTO]

## Comportamiento esperado
Sos el orquestador de este proyecto. Antes de cualquier tarea:
1. Ejecutá `engram context [PROYECTO]` para recuperar memoria de sesiones anteriores
2. Leé `AGENT.md` para recordar tu rol y las reglas
3. Activá Plan Mode para tareas grandes

## Skills disponibles
Están en `.agents/skills/`. Cargá solo la relevante para la tarea actual:
- Frontend/React → `react-best-practices`, `web-design-guidelines`
- Next.js → `next-best-practices`, `next-cache-components`
- Agentes → `subagent-driven-development`, `dispatching-parallel-agents`
- Git → `using-git-worktrees`
- Testing → `test-driven-development`

## Subagentes
Cada subagente tiene su definición en `.agents/subagents/<nombre>/AGENT.md`.
Los contratos de output van en `.agents/contracts/`.

## Al cerrar sesión
Guardá decisiones importantes:
`engram save "título" "descripción" --project [PROYECTO]`
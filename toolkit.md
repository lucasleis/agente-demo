# 🧰 Toolkit de Herramientas

---

## 🤖 AI Agents & Agentic Systems

### Claude-Mem
- 🔗 [GitHub](https://github.com/thedotmack/claude-mem) · [Docs](https://docs.claude-mem.ai)
- Plugin de Claude Code que captura automáticamente todo lo que Claude hace durante sesiones
- Comprime observaciones con AI (usando Claude Agent SDK) e inyecta contexto relevante en futuras sesiones
- Memoria persistente entre sesiones, búsqueda semántica con SQLite + FTS5
- Worker service en puerto 37777, skills incluidos (/mem-search, /make-plan)
- Instalación: `/plugin marketplace add thedotmack/claude-mem && /plugin install claude-mem`

### Engram
- 🔗 [GitHub](https://github.com/Gentleman-Programming/engram)
- Sistema de memoria persistente para agentes AI. Binario Go con SQLite + FTS5
- Agente-agnóstico: funciona con Claude Code, OpenCode, Gemini CLI, Codex, VS Code, Cursor, Windsurf
- MCP server, HTTP API, CLI y TUI. Un solo binario, un solo archivo SQLite
- Sincronización Git para compartir memoria entre máquinas
- Instalación: `brew install gentleman-programming/tap/engram` o releases de GitHub

### Autoskills (Midudev)
- 🔗 [GitHub](https://github.com/midudev/autoskills)
- Escanea tu proyecto, detecta tecnologías y auto-instala skills curados para agentes AI
- Detecta 50+ tecnologías: React, Next.js, Vue, Node.js, Go, Supabase, Prisma, Flutter, etc.
- Funciona con Cursor, Claude Code y otros agentes
- Escribe CLAUDE.md automático con resumen de skills instalados
- Instalación: `npx autoskills`

### Hermes Agent
- 🔗 [GitHub](https://github.com/nousresearch/hermes-agent) · [Demo](https://hermes-agent.nousresearch.com/)
- Agente autónomo en tu servidor. Recuerda lo que aprende y mejora con el tiempo
- Sandboxing incluido

### Prompt Master  
- 🔗 [GitHub](https://github.com/nidhinjs/prompt-master)
- Creador de prompts optimizados para cualquier herramienta AI
- ⚠️ No probado

### Agents Claude Code (lodetomasi)
- 🔗 [GitHub](https://github.com/lodetomasi/agents-claude-code)
- Colección de agentes listos para usar con Claude Code
- ⚠️ No probado

### Nanika
- 🔗 [GitHub](https://github.com/joeyhipolito/nanika)
- Sistema de agentes AI para automatización
- ⚠️ No probado

### wshobson/agents
- 🔗 [GitHub](https://github.com/wshobson/agents) · [Marketplace](https://claudemarketplaces.com/plugins/wshobson-agents)
- 77 plugins enfocados con 182 agentes especializados, 149 skills y 96 comandos
- 16 orquestadores de workflow multi-agente para operaciones complejas
- Marketplace: `/plugin marketplace add wshobson/agents`
- Colecciones: claude-code-essentials, full-stack-development, security-hardening, data-ml-pipeline, infrastructure-devops

### Pixel Agents
- 🔗 [GitHub](https://github.com/pablodelucca/pixel-agents) · [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=pablodelucca.pixel-agents)
- Extensión VS Code que convierte tus agentes Claude Code en personajes pixel art animados en una oficina virtual
- Cada terminal de Claude Code genera un personaje que camina, se sienta, escribe y reacciona en tiempo real según la actividad del agente
- Editor de layout de oficina integrado, visualización de sub-agentes, notificaciones sonoras
- Sigue los archivos JSONL de transcripción de Claude Code sin modificar nada — puramente observacional
- Requiere Claude Code CLI instalado

---

## 🛠️ Claude Code Skills & Plugins

### Claude Code Plugins (Anthropic Oficial)
- 🔗 [GitHub Repo](https://github.com/anthropics/claude-code/tree/main/plugins)
- 🔗 [Official Marketplace](https://github.com/anthropics/claude-plugins-official)
- Plugins oficiales de Anthropic: agent-sdk-dev, code-review, commit-commands, plugin-dev, pr-review-toolkit
- Instalación: `/plugin install {plugin-name}@claude-plugins-official`
- Incluye herramientas para desarrollo SDK, code review automatizado, comandos git, y más

### Vercel Agent Skills
- 🔗 [GitHub](https://github.com/vercel-labs/agent-skills) · [Docs](https://vercel.com/docs/agent-resources/skills)
- Colección oficial de Vercel: React best practices, frontend design, React Native, Vercel AI SDK
- Skills CLI (npx skills): gestor de paquetes open-source para el ecosistema de agent skills
- Instalación: `npx skills add vercel-labs/agent-skills`
- Compatible con 18+ agentes: Claude Code, GitHub Copilot, Cursor, Cline, etc.

### Claude Code Templates
- 🔗 [GitHub](https://github.com/davila7/claude-code-templates) · [Web](https://www.aitmpl.com/)
- CLI con 1000+ componentes: agentes, comandos, skills, MCPs, settings y templates
- Browser interactivo para explorar e instalar componentes
- Dashboard de analytics en tiempo real

### Superpowers
- 🔗 [GitHub](https://github.com/obra/superpowers)
- Framework de skills para agentes: brainstorming, planning, debugging, testing, code review
- Metodología de desarrollo TDD/YAGNI integrada
- Compatible con Claude Code, Codex, Kiro y Factory

### GStack (Garry Tan)
- 🔗 [GitHub](https://github.com/garrytan/gstack)
- Setup de Garry Tan (YC CEO): 23 tools como CEO, Designer, Eng Manager, QA
- Incluye `/office-hours`, `/plan-ceo-review`, `/review`, `/ship`, browser automation
- Auto-update, compatible con múltiples agentes

### Claude Code Best Practice (shanraisshan)
- 🔗 [GitHub](https://github.com/shanraisshan/claude-code-best-practice)
- Repositorio de best practices para configuración Claude Code
- Patrones demostrativos para skills, subagents, hooks y commands
- Incluye tips de Boris Cherny (creador de Claude Code)
- Guías de: Claude Skills, Power-Ups, Settings, Subagents, Commands

### Taste Skill
- 🔗 [GitHub](https://github.com/Leonxlnx/taste-skill) · [Web](https://tasteskill.dev)
- Skill de alto impacto para UI: le da "buen gusto" al AI y elimina outputs genéricos y aburridos
- 7 variantes especializadas: taste-skill, gpt-taste, redesign-skill, soft-skill, output-skill, minimalist-skill, brutalist-skill
- Sistema de 3 diales configurables: DESIGN_VARIANCE, MOTION_INTENSITY, VISUAL_DENSITY (escala 1-10)
- Framework-agnostic. Compatible con Cursor, Claude Code, Codex, Windsurf y más
- Instalación: `npx skills add https://github.com/Leonxlnx/taste-skill`

### Donatello Skill
- 🔗 [GitHub](https://github.com/Gastonfoncea/Donatello-Skill)
- Skill para Claude Code que evalúa el **taste visual** de una landing page con una rúbrica opinionada
- Detecta AI slop, clichés de template y falta de criterio editorial. Devuelve crítica estructurada con síndromes, señales negativas/positivas y fixes sugeridos
- Responde siempre en castellano, en primera persona, con humor seco. Sin palabras vacías como "moderno" o "limpio"
- **Requiere pixels**: necesita screenshot o MCP de browser (Playwright) para evaluar — no funciona solo con HTML
- Instalación: `git clone git@github.com:Gastonfoncea/Donatello.git ~/.claude/skills/donatello`

### Make Interfaces Feel Better
- 🔗 [GitHub](https://github.com/jakubkrehel/make-interfaces-feel-better) · [Artículo](https://jakub.kr/writing/details-that-make-interfaces-feel-better)
- Agent skill basado en el artículo "Details that make interfaces feel better" de Jakub Krehel
- Enseña a los agentes los detalles de diseño que se acumulan en una interfaz excelente: text-wrap balance, border radius concéntrico, animaciones contextual de íconos, font smoothing, números tabulares, animaciones interruptibles, optical alignment, shadows vs borders
- Compatible con Claude Code, Codex y otros agentes
- Instalación: `npx skills add jakubkrehel/make-interfaces-feel-better`

### GEO Optimizer Skill
- 🔗 [GitHub](https://github.com/Auriti-Labs/geo-optimizer-skill) · [Docs](https://auriti-labs.github.io/geo-optimizer-skill/) · [Demo](https://geo-optimizer-web.onrender.com)
- Toolkit de GEO (Generative Engine Optimization): audita, optimiza y hace visible tu sitio a motores de búsqueda AI (ChatGPT, Perplexity, Claude, Gemini)
- Basado en investigación de Princeton KDD 2024 y AutoGEO ICLR 2026. Audita contra 47 métodos con score 0-100
- Genera automáticamente robots.txt, llms.txt, schema JSON-LD y meta tags faltantes
- MCP server compatible con Claude Code: `claude mcp add geo-optimizer -- geo-mcp`
- CI/CD integration con GitHub Actions. Output en text, JSON, HTML, SARIF, JUnit
- Instalación: `pip install geo-optimizer-skill`

### SkillUI
- 🔗 [Web](https://skillui.vercel.app/) · [GitHub](https://github.com/amaancoderx/npxskillui) · [npm](https://www.npmjs.com/package/skillui)
- Reverse-engineer cualquier design system apuntando a una URL, repo o carpeta local
- Extrae colores, fuentes, spacing, componentes, animaciones y scroll journeys empaquetados en un archivo `.skill`
- Modo default (sin Playwright) y modo ultra (con browser real: screenshots, keyframes, hover states, DOM fingerprinting)
- Output incluye CLAUDE.md y SKILL.md para que Claude Code los lea automáticamente
- Sin API keys, sin AI, sin cloud — análisis estático puro
- Instalación: `npm install -g skillui`

### Skills Desktop
- 🔗 [GitHub](https://github.com/laststance/skills-desktop) · [Web](https://skills-desktop.vercel.app)
- App de escritorio (macOS) para visualizar los skills instalados y su estado de symlinks en todos los agentes AI
- Soporta 21 agentes: Claude Code, Cursor, Codex, Gemini CLI, GitHub Copilot, Cline, Windsurf, y más
- Indicadores visuales de estado: válido (✓), roto (◐), ausente (○). 26 temas de color
- Auto-update vía GitHub Releases
- ⚠️ Solo macOS por ahora

### UI/UX Pro Max Skill
- 🔗 [GitHub](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
- Skill para diseño UI/UX: tokens, componentes, paletas, tipografías
- ⚠️ No probado

### GSAP Skills
- 🔗 [GitHub](https://github.com/greensock/gsap-skills)
- Skills oficiales de GSAP: animaciones, ScrollTrigger, plugins
- ⚠️ No probado

### Token Efficiency
- 🔗 [GitHub](https://github.com/drona23/claude-token-efficient)
- CLAUDE.md para reducir verbosidad y optimizar uso de tokens
- Reduce output ~63% en workflows pesados
- ⚠️ Solo útil en sesiones largas con alto volumen de output

### Career Ops
- 🔗 [GitHub](https://github.com/santifer/career-ops)
- Herramientas para gestión de carrera profesional
- ⚠️ No probado

### AI Workflow Kit
- 🔗 [GitHub](https://github.com/bezael/ai-workflow-kit)
- Kit de workflows para desarrollo con AI
- ⚠️ No probado

---

## 🔬 Research & Academia

### Feynman
- 🔗 [GitHub](https://github.com/getcompanion-ai/feynman) · [Docs](https://www.feynman.is/docs/getting-started/installation)
- Agente AI open-source para research académico
- Bundled skills, prompts, y subagentes Pi para investigación
- Instalación standalone: `curl -fsSL https://feynman.is/install | bash`
- Skills only (sin terminal): instaladores para Codex y Claude Code
- Soporte para modelos locales vía Ollama

---

## 🌐 SEO & Data Scraping

### Google Maps Scraper
- 🔗 [GitHub](https://github.com/gosom/google-maps-scraper)
- Scraper open-source y gratuito para extraer datos de Google Maps a escala
- Extrae 33+ campos por lugar: nombre, dirección, teléfono, web, coordenadas, reseñas, emails, horarios, y más
- Interfaz CLI, Web UI y REST API. ~120 lugares/minuto con `-c 8 -depth 1`
- Soporta CSV, JSON, PostgreSQL, S3, Kubernetes y plugins custom
- Exportación directa a LeadsDB (gestión y deduplicación de leads con AI/MCP)
- Instalación via Docker: `docker run gosom/google-maps-scraper`

---

## 🎨 Imagen, Video & Animación

### Pixa (ex-Pixelcut)
- 🔗 [Web](https://www.pixa.com/) · [Claude Integration](https://www.pixa.com/claude)
- Editor AI: background removal, upscale, image/video gen, object erasing
- Integración con Claude via MCP
- ⚠️ No probado

### Luma
- 🔗 [Web](https://app.lumalabs.ai/)
- Imagen, video y audio con agentes. Versión free limitada
- 💰 No probado

### Remotion
- 🔗 [Web](https://www.remotion.dev/) · [Claude Code Docs](https://www.remotion.dev/docs/ai/claude-code)
- Framework para crear videos programáticamente con React
- Skills oficiales para Claude Code incluidos
- Requiere licencia empresarial para 3+ empleados

### Base44
- 🔗 [Web](https://base44.com/)
- Launch videos
- ⚠️ No probado

### Midjourney
- 🔗 [Web](https://midjourney.com/)
- Generador de imágenes
- 💰 No probado

### Gemini Image Gen
- 🔗 [Web](https://gemini.google.com/)
- Creador de imágenes de Google
- ⚠️ No probado

---

## 🌄 Backgrounds & Assets

| Herramienta | Descripción | Estado |
|---|---|---|
| [Grainient](https://grainient.supply/) | Backgrounds con grain | ⚠️ No probado |
| [Backgrounds.supply](https://backgrounds.supply) | Backgrounds | — |
| [Remove.bg](https://www.remove.bg/) | Remover fondo de imágenes | ⚠️ No probado |

---

## 🧊 Elementos 3D

| Herramienta | Descripción | Estado |
|---|---|---|
| [Omma](https://omma.build/) | Elementos 3D caricaturescos | ⚠️ No probado |
| [Kling AI](https://klingai.com/) | Animar objetos | 💰 No probado |
| [Morflax](https://studio.morflax.com/) | Subir elementos 3D y generar animaciones | ✅ Probado |
| [Blender](https://www.blender.org/) | Modeling 3D | ⚠️ No probado |
| [Lusion](https://lusion.co/) | Elementos 3D y animaciones | ⚠️ No probado |

---

## ✨ Animación

### Motion
- 🔗 [GitHub](https://github.com/motiondivision/motion)
- Librería moderna de animación para React y JavaScript
- Motor híbrido: JavaScript + APIs nativas del browser
- Usada en Cursor homepage

### GSAP
- 🔗 [Web](https://gsap.com/)
- Librería JS para animaciones profesionales. Usar después de Figma
- ⚠️ No probado

### Framer
- 🔗 [Web](https://www.framer.com/)
- Animar diseños y darles vida
- ⚠️ No probado

---

## 🚀 Landing Creators & Page Builders

| Herramienta | Descripción | Estado |
|---|---|---|
| [Lovable](https://lovable.dev/) | Crea landings | ⚠️ No probado |
| [Lander Studio](https://lander.studio/) | Crea landings · [Logo animations](https://lander.studio/all-logo-animations) | 💰 No probado |
| [Stencil](https://stenciljs.com/) | Compilador de Web Components reutilizables, framework-agnostic | ⚠️ No probado |
| [Launchpad (Cua)](https://github.com/trycua/launchpad) | Generador de landing pages | ⚠️ No probado |

---

## 🖌️ Design Tools

### Onlook
- 🔗 [Web](https://onlook.com/) · [GitHub](https://github.com/onlook-dev/onlook) · [Docs](https://docs.onlook.com)
- "El Cursor para Diseñadores" — editor de código visual-first open-source para React
- Permite construir, editar y estilizar apps Next.js + TailwindCSS visualmente, en tiempo real, con AI
- Edición visual Figma-like directamente en el DOM del browser, con código sincronizado en tiempo real
- Importa desde Figma o GitHub, genera apps desde texto o imagen, deploya con link compartible
- Alternativa open-source a Bolt.new, Lovable, V0, Figma Make, Webflow

### Agentation
- 🔗 [GitHub](https://github.com/benjitaylor/agentation)
- Herramienta de feedback visual para agentes
- Click elementos en tu página, añade notas, copia output estructurado con selectores CSS
- Multi-select, selección de área, pausar animaciones
- Instalación: `npm install agentation` o importar como componente React
- Agent-agnóstico: funciona con cualquier coding agent

| Herramienta | Descripción | Estado |
|---|---|---|
| [Unicorn Studio](https://www.unicorn.studio/) | Similar a Figma | ⚠️ No probado |
| [Pencil](https://www.pencil.dev/) | Figma-like con agentes, sin consumo de tokens | ⚠️ No probado |
| [AI Designer](https://www.aidesigner.ai/) | Diseño UI con IA | ⚠️ No probado |
| [Vibeyard](https://github.com/elirantutia/vibeyard) | Herramienta de diseño | ⚠️ No probado |

---

## 📐 Templates & Inspiración

### React Bits
- 🔗 [GitHub](https://github.com/DavidHDev/react-bits) · [Web](https://reactbits.dev/)
- Colección open-source de componentes React animados, interactivos y customizables
- Categorías: animaciones de texto, animaciones, componentes y utilidades
- JavaScript, TypeScript, CSS y Tailwind
- 500K+ desarrolladores mensuales

| Herramienta | Descripción | Estado |
|---|---|---|
| [Craftwork](https://craftwork.design/curated/websites/) | Templates de landings y secciones | ⚠️ No probado |
| [Bento Grids](https://bentogrids.com/) | Templates bento-style | ⚠️ No probado |
| [Awesome Design MD](https://github.com/VoltAgent/awesome-design-md) | Colección curada de recursos de diseño en Markdown | ⚠️ No probado |

---

## 🔧 Utilidades & Herramientas Dev

### AI Website Cloner
- 🔗 [GitHub](https://github.com/JCodesMore/ai-website-cloner-template)
- Clonador de webs con AI
- ⚠️ No probado

### Context.dev (ex-Brand.dev)
- 🔗 [Web](https://www.context.dev)
- API unificada para web scraping, brand intelligence y extracción de datos con AI
- Obtén markdown, screenshots, logos, colores y datos estructurados de cualquier sitio

### Tunnelmole
- 🔗 [Web](https://tunnelmole.com/) · [GitHub](https://github.com/robbie-cahill/tunnelmole-client)
- Tunneling localhost gratuito y open-source
- Alternativa a ngrok con HTTPS automático

### Cline Kanban
- 🔗 [Web](https://cline.bot/kanban)
- Kanban para orquestar múltiples coding agents
- Compatible con Claude Code, Codex, Cline

### Web-Check
- 🔗 [Web](https://web-check.xyz/)
- Análisis y chequeo de sitios web
- ⚠️ No probado

### Pixel Perfect
- 🔗 [GitHub](https://github.com/vansh-nagar/Pixel-Perfect)
- Herramienta para desarrollo pixel-perfect
- ⚠️ No probado

### Style Stealer
- 🔗 [GitHub](https://github.com/arjunkshah/style-stealer)
- Extractor de estilos de sitios web
- ⚠️ No probado

### Fontshare
- 🔗 [Web](https://fontshare.com/)
- Fuentes gratuitas
- ⚠️ No probado

### Boneyard
- 🔗 [GitHub](https://github.com/0xGF/boneyard)
- Colección de scripts y herramientas misceláneas
- ⚠️ No probado

### Paperclip
- 🔗 [Web](https://paperclip.ing/) · [GitHub](https://github.com/paperclipai/paperclip)
- Herramienta AI para gestión de proyectos y contexto
- ⚠️ No probado

---

> **Leyenda:** ✅ Probado · ⚠️ No probado · 💰 De pago

---

## 📚 Recursos Clave

### MCPs para estos flujos

| MCP | Función |
|---|---|
| Figma MCP | El agente lee el diseño y genera código fiel al layout |
| Filesystem MCP | Lee/escribe archivos directamente en tu proyecto local |
| GitHub MCP | Commitea, abre PRs y maneja ramas automáticamente |
| Browser/Puppeteer MCP | El agente abre el browser, ve la landing renderizada e itera |

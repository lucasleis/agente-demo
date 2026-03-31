# 🧰 Toolkit de Herramientas

---

## 🤖 AI Agents

### Hermes Agent
- 🔗 [GitHub](https://github.com/nousresearch/hermes-agent) · [Demo](https://hermes-agent.nousresearch.com/)
- Agente autónomo en tu servidor. Recuerda lo que aprende y mejora con el tiempo.
- Sandboxing incluido

### Prompt Master
- 🔗 [GitHub](https://github.com/nidhinjs/prompt-master)
- Creador de prompts
- ⚠️ No probado

---

## 🎨 Imagen & Video

| Herramienta | Descripción | Estado |
|---|---|---|
| [Midjourney](https://midjourney.com/) | Generador de imágenes | 💰 No probado |
| [Gemini Image Gen](https://gemini.google.com/) | Creador de imágenes | ⚠️ No probado |
| [Base44](https://base44.com/) | Launch videos | ⚠️ No probado |
| [Luma](https://app.lumalabs.ai/) | Imagen, video y audio con agentes. En versión free anda medio medio. | 💰 No probado |

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

| Herramienta | Descripción | Estado |
|---|---|---|
| [GSAP](https://gsap.com/) | Librería JS para animaciones profesionales. Usar después de Figma. | ⚠️ No probado |
| [Framer](https://www.framer.com/) | Animar diseños y darles vida | ⚠️ No probado |

---

## 🚀 Landing Creators

| Herramienta | Descripción | Estado |
|---|---|---|
| [Lovable](https://lovable.dev/) | Crea landings | ⚠️ No probado |
| [Lander Studio](https://lander.studio/) | Crea landings · [Logo animations](https://lander.studio/all-logo-animations) | 💰 No probado |
| [Stencil](https://stenciljs.com/) | Compilador de Web Components reutilizables, framework-agnostic | ⚠️ No probado |

---

## 🖌️ Design Tools (Figma-like)

| Herramienta | Descripción | Estado |
|---|---|---|
| [Unicorn Studio](https://www.unicorn.studio/) | Similar a Figma | ⚠️ No probado |
| [Pencil](https://www.pencil.dev/) | Figma-like con agentes, sin consumo de tokens | ⚠️ No probado |

---

## 📐 Templates & Inspiración

| Herramienta | Descripción | Estado |
|---|---|---|
| [Craftwork](https://craftwork.design/curated/websites/) | Templates de landings y secciones | ⚠️ No probado |
| [Bento Grids](https://bentogrids.com/) | Templates bento-style | ⚠️ No probado |

---

## 🔧 Utilidades

| Herramienta | Descripción | Estado |
|---|---|---|
| [AI Website Cloner](https://github.com/JCodesMore/ai-website-cloner-template) | Clonador de webs | ⚠️ No probado |
| [Fontshare](https://fontshare.com/) | Fuentes gratuitas | ⚠️ No probado |
| [Figmify](https://figmify.ai/) | Conversión imagen → Figma | ⚠️ No probado |

---

> **Leyenda:** ✅ Probado · ⚠️ No probado · 💰 De pago

---

# 🔁 Flujos de Trabajo

---

## 🌐 Flujo 1 — Landing completa desde cero (rápido)
**Objetivo:** Lanzar una landing funcional y visualmente potente en poco tiempo.

```
Claude (copy + estructura)
  → Craftwork / Bento Grids (inspiración y template base)
  → Lovable (generar la landing con código)
  → Gemini Image Gen / Midjourney (imágenes hero y secciones)
  → Remove.bg (limpiar fondos de assets)
  → Grainient / Backgrounds.supply (background final)
  → Fontshare (tipografía)
```

---

## 🎬 Flujo 2 — Landing con video hero o demo (impacto visual máximo)
**Objetivo:** Landing con video de producto o animación como pieza central.

```
Claude (guión y concepto del video)
  → Gemini Image Gen (imágenes base / storyboard)
  → Luma o Base44 (generar el video/launch video)
  → Lovable (integrar en la landing)
  → GSAP o Framer (scroll animations, transiciones)
```

---

## 🧊 Flujo 3 — Landing premium con elementos 3D
**Objetivo:** Landing de alto impacto con objetos 3D animados.

```
Blender (modelar el elemento 3D)
  → Morflax (generar animación del modelo)
  → Kling AI (animar objetos si no tenés el modelo)
  → Unicorn Studio o Pencil (integrar 3D en el diseño)
  → GSAP (animaciones al hacer scroll)
  → Stencil (empaquetar como Web Component reutilizable)
  → Lovable o Lander Studio (armar la landing final)
```

---

## 🔄 Flujo 4 — Clonar y personalizar una web existente
**Objetivo:** Partir de algo que ya funciona y hacerlo propio rápido.

```
AI Website Cloner (clonar estructura base)
  → Figmify (convertir screenshots a Figma para editar)
  → Pencil o Unicorn Studio (editar el diseño)
  → Claude (reescribir copy y adaptar contenido)
  → Midjourney / Gemini (reemplazar imágenes genéricas)
  → Remove.bg + Grainient (pulir assets)
```

---

## ⚙️ Flujo 5 — Sistema de componentes escalable (para múltiples landings)
**Objetivo:** No empezar de cero cada vez, construir una librería reutilizable.

```
Claude (definir arquitectura y componentes necesarios)
  → Pencil (diseñar los componentes visualmente)
  → Stencil (compilar como Web Components framework-agnostic)
  → Fontshare + Grainient (tokens de diseño: fuentes y fondos)
  → Lovable (armar landings nuevas tirando de la librería)
```

---

> 💡 **Notas:** Framer y GSAP se solapan — elegir según preferencia: no-code (Framer) vs control total (GSAP). Luma y Base44 también se solapan en video, vale testear los dos. Hermes Agent puede meterse como orquestador en cualquier flujo para automatizar pasos repetitivos.

# 🎬 "The Janitor" — 3D Faceless Cinematic Micro-Series

This project is a high-end cinematic look-development created as a technical test assignment for a mobile-first micro-series production pipeline.

## 📌 Project Overview
* **Style:** 3D Faceless Documentary Narrative (inspired by channels like Blackfiles, fern, and Outplayed).
* **Core Constraint:** Maintaining strict visual and character consistency using custom AI pipelines. 
* **Character Specification:** Matte white humanoids with oval heads, features completely blank, wearing highly realistic and detailed contextual clothing.

## 🛠️ AI Toolset Used
* **Google Whisk:** Scene composition, look-development, and architectural/character style-locking.
* **Google Veo 3 (Flow):** High-fidelity text-to-video generation, volumetric fog rendering, fluid physics, and camera movement control.
* **Suno AI:** Sound design, atmospheric dark scoring, and audio background matching.

---

## 🎞️ Shot-by-Shot Production Breakdown & Prompts

### 🏢 Shot 1: The Cartel Vault (Timing: 00:00 - 00:01)
* **Visual Focus:** Volumetric dust particles catching sharp overhead light beams. Stacks of cartel cash and clean paper documents on a dark wooden desk. Noir/crime aesthetic.
* **Key AI Assets:** `1 Image_202602021312.jpg`, `2 Image_202602021320.jpg`
* **Video Generation:** Animated via Google Veo 3 to add rolling smoke/vapor effects rising from the background.

### 🧹 Shot 2: Character Intro & Fluid Physics (Timing: 00:01 - 00:04)
* **Visual Focus:** Detailed close-up of the matte white humanoid wearing realistic industrial janitor overalls next to a cleaning bucket. Transition to a wide shot tracking the character mopping a dark concrete basement floor.
* **Technical Achievement:** Smooth reflection of green industrial neon lights on wet surfaces and dynamic fluid physics as the mop interacts with a deep red liquid stain (`3 Remove_the_red_2k_202602012014.jpeg`).

### 🚨 Shot 3: The Heist Aftermath & Escape (Timing: 00:04 - 00:07)
* **Visual Focus:** The janitor carrying a metallic bucket walks undetected past heavily armed tactical guards (`4Image_202602011942.jpg`). Cuts to a bird's-eye view of a semi-truck driving down an isolated highway enveloped in thick morning fog, followed by the final reveal of an empty, chaotic corporate office littered with stolen paper documents (`6 Remove_the_janitors_2k_202602021229.jpeg`).

---

## ⚙️ Technical Optimization & Key Takeaways
1. **Prompt Debugging:** Leveraged a structured prompt architecture to force Google Whisk and Veo 3 to strictly isolate the "matte white" surface texture without applying default human facial features or shadows.
2. **Environmental Cohesion:** Successfully locked the dark, desaturated color grading across three distinct environments (vault, industrial basement, foggy highway).

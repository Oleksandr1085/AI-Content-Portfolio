# 🎬 "The Janitor" — 3D Faceless Cinematic Micro-Series

This project showcases a high-end cinematic look-development and visual pipeline created as a technical test assignment for a mobile-first micro-series production.

## 📌 Project Strategy: The Two-Phase Pipeline
To ensure maximum production efficiency and quality control, the project was split into two distinct execution phases:
1. **Phase 1: Look-Development & Style Locking (Final Stills):** Establishing a flawless, unified *3D Faceless* aesthetic across multiple complex environments with strict character consistency.
2. **Phase 2: Motion Production Tests (Video Prompts):** Testing high-fidelity physics, environmental lighting dynamics, and fluid interaction using advanced text-to-video tools.

## 🛠️ AI Toolset
* **Google Whisk:** Structural composition, environmental world-building, and character style-locking.
* **Google Veo 3 (Flow):** Cinematic motion control, volumetric fog/lighting rendering, and liquid simulation.
* **Suno AI:** Cinematic low-end ambient scoring and audio asset creation.

---

## 🎞️ Shot-by-Shot Look-Development (Visual Script)

### 🛣️ Shot 1: The Hook (Opening Scene)
* **Concept Focus:** Establishing the atmospheric mood. An empty foggy highway lit only by the bright moon, followed by a dramatic bird's-eye view of a semi-truck cutting through the dense morning mist.
* **Visual Identity:** Cinematic volumetric fog and desaturated blue-grey grading.

<p align="center">
  <img src="9 Add_a_perspective_2k_202602021245.jpeg" width="700" alt="Shot 1 - Highway Fog"/>
</p>

---

### 🏢 Shot 2: The Setup (Inside the Vault)
* **Concept Focus:** The heist environment. High-contrast overhead spotlighting illuminating neat stacks of currency bills and administrative documents spread across a dark wooden table.
* **Visual Identity:** Rich shadows, high-fidelity texture rendering on paper/money assets.

<p align="center">
  <img src="4Image_202602011942.jpeg" width="45%;" style="margin-right: 2%;" alt="Vault Setup 1"/>
  <img src="2 Image_202602021320.jpeg" width="45%;" alt="Vault Setup 2"/>
</p>

---

### 🧹 Shot 3: The Protagonist (Character Concept)
* **Concept Focus:** Deep dive into character identity and strict visual constraints. The 3D faceless janitor profile shot standing next to a glowing wall clock, transitioning to a wide shot of him working in a dimly lit, industrial green concrete basement.
* **Technical Milestone:** Flawless isolation of the smooth, featureless matte white head geometry combined with realistic fabric folds on the work uniform.

<p align="center">
  <img src="13 Remove_the_characters_2k_202602021309.jpeg" width="45%;" style="margin-right: 2%;" alt="Janitor Profile"/>
  <img src="7Remove_knife_and_2k_202602011953.jpeg" width="45%;" alt="Janitor Working"/>
</p>

---

### 🚨 Shot 4: The Heist & Aftermath (The Climax)
* **Concept Focus:** Narrative storytelling through environment. The janitor carrying a disposal bin, blending in while moving past corporate management and white-collar personnel. Cut to the aftermath: a completely ransacked office floor littered with documents and dramatic crime scene elements (blood tracking).
* **Technical Milestone:** Maintaining stable object placement and structural continuity between the populated office scene and the destroyed aftermath scene.

<p align="center">
  <img src="5 Remove_the_money_2k_202602021155.jpeg" width="31%;" style="margin-right: 1%;" alt="Office Scene 1"/>
  <img src="8 28c79fe3-8657-49ec-b759-4202d9d0eaef.png" width="31%;" style="margin-right: 1%;" alt="Office Scene 2"/>
  <img src="6 Remove_the_janitors_2k_202602021229.jpeg" width="31%;" alt="Office Aftermath"/>
</p>

---

## ⚙️ Key Technical Takeaways & QA Insights

* **Character Anchor Control:** Successfully bypassed default AI facial generation biases by structuring precise negative prompts and text weights to enforce a perfectly smooth, featureless matte texture without introducing artifacts or unwanted shadowing.
* **Environmental Cohesion:** Locked color grading parameters across four distinct setting shifts (night highway, dark vault, green basement, lit office), ensuring a seamless viewer experience during rapid editing cuts.
* **Physics Debugging:** Utilized video generation test blocks to evaluate how complex elements (like trailing liquids on concrete floor surfaces and moving headlight shafts through fog layers) respond to dynamic camera panning.

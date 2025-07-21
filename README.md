# 🪞 Munizer – Emotional AI Mirror (Concept Prototype)

**Munizer** is a concept for an AI-powered emotional mirror that detects a user's mood through facial expressions and responds with personalized music suggestions. Though the hardware was not physically built, this project focuses on **design thinking**, **technical feasibility**, and **end-to-end product workflow**.

---

## 💡 Idea Brief

Munizer enriches daily emotional wellness by integrating emotion recognition with intuitive responses. When a user stands in front of the mirror, it detects their face, analyzes emotion, and offers a choice to engage. If the user agrees, it plays mood-aligned music; otherwise, it enters standby.

This mirrors how emotionally intelligent interfaces can be embedded into smart home products.

---

## 🎯 Goals (For Product/PM Roles)

- Apply product thinking to emotional tech.
- Design a low-friction, high-value user journey.
- Research feasibility with real-world tools.
- Prioritize emotional wellness in everyday interaction.
- Create a component-level functional breakdown for future MVP development.

---

## 🛠️ Conceptual Workflow

- 📷 Detect face → 🎭 Predict emotion → 🎤 Ask to engage → 🎵 Play music
- Designed using tools and methods from:
  - **Python + OpenCV** for image processing
  - **TensorFlow** or equivalent for emotion classification
  - **SpotiPy/API-based** music mapping by emotion

View full logic flow and component roles:
- [`Components Workflow.pdf`](./Components%20Workflow.pdf)
- [`Moods.pdf`](./Moods.pdf)

---

## 📦 Product Design Elements

| Component         | Description |
|------------------|-------------|
| **Camera**        | Captures facial expression input |
| **Emotion Model** | Predicts emotion from image (e.g., happy, sad, angry) |
| **Music DB/API**  | Plays a track based on predicted emotion |
| **User Input**    | User speaks or confirms whether to play music |
| **Mirror Display**| Optional UI showing emotion and music feedback |
| **Raspberry Pi**  | (Planned) Edge processor to handle all logic |

🖼️ View design sketches: [`IMG20240405142016.jpg`](./IMG20240405142016.jpg)

---

## 📐 Focused Outcomes

- 🎯 Product thinking from ideation to interaction
- 🧠 Emotional AI + music = mental health intervention
- 🛠️ Future-ready architecture (Raspberry Pi + OpenCV + SHAP or Spotify API)

---

## 🧠 Future Opportunities

- Integrate Spotify API or YouTube Music
- Use LLM for voice-based conversation with the user
- Add smart lighting or scent emitters to expand sensory experience
- Explore wearable emotion sensors (biometric input)

---

## 👩‍💻 Author

**Sanika Jhanwar**  
Product-minded Computer Science Engineer | AI & Emotional Tech Enthusiast  

---

> 🧪 This is a **design + concept** project meant to showcase product vision, technical grounding, and end-user empathy. Not a final working prototype.

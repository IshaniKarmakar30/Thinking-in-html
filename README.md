# Project 2: Thinking in HTML (Bharat Space Education Research Centre)

This repository contains 5 interactive, single-file HTML applications built entirely using AI prompt engineering (Claude) without manually writing the code, as part of the GenAI Internship (Week 1).

Each page is responsive (desktop and mobile friendly), self-contained with internal CSS and JavaScript, and includes 5+ interactive controls (buttons, sliders, dynamic calculations, filters, and state toggles).

---

## 🚀 Live Demos (GitHub Pages)

- **Page 1: Revision & Teaching Dashboard**  
  👉 [Live Preview](https://ishanikarmakar30.github.io/Thinking-in-html/page1.html)
- **Page 2: Money Explorer**  
  👉 [Live Preview](https://ishanikarmakar30.github.io/Thinking-in-html/page2.html)
- **Page 3: Interactive 2D/3D Model (Solar System)**  
  👉 [Live Preview](https://ishanikarmakar30.github.io/Thinking-in-html/page3.html)
- **Page 4: Decision Helper**  
  👉 [Live Preview](https://ishanikarmakar30.github.io/Thinking-in-html/page4.html)
- **Page 5: Interactive Presentation Deck**  
  👉 [Live Preview](https://ishanikarmakar30.github.io/Thinking-in-html/page5.html)

---

## 📁 Project Overview

### 1. `page1.html` — CN & OS Revision Dashboard
- **Target User:** Computer science student preparing for semester exams.
- **Key Features:** Live exam countdown timer, checklist synced to a real-time progress bar, 3D flip-cards with flashcard definitions, multiple-choice quiz with scoring, and dark/light theme switch.

### 2. `page2.html` — Money Explorer
- **Target User:** Student managing monthly personal and hostel expenses.
- **Key Features:** Dynamic bar chart with category filtering, live savings target range slider, duplicate transaction alerts with confirm/dismiss actions, dynamic add-expense modal, and complete state reset.

### 3. `page3.html` — Interactive Solar System
- **Target User:** Learner exploring planetary physics and orbital mechanics.
- **Key Features:** Orbit speed regulation slider (0.5x–5x), play/pause animation control, clickable planets with fact sheets, zoom in/out controls, and toggles for orbit rings and labels.

### 4. `page4.html` — Decision Helper Matrix
- **Target User:** Developer evaluating tech career paths and project frameworks.
- **Key Features:** Weightage sliders across multiple evaluation criteria, real-time dynamic re-ranking animations, top-rank visual indicators, and default settings reset.

### 5. `page5.html` — Interactive Presentation Deck
- **Target User:** Speaker presenting modern web and GenAI technologies.
- **Key Features:** Arrow-key and button navigation, thumbnail slide navigator, fullscreen mode toggle, interactive live dataset charts, and an embedded wrap-up quiz.

---

## 🛠️ Prompt Engineering Methodology

All pages were constructed following the 4-part prompting framework:
- **Who:** Target audience persona.
- **What:** Core data schema and dashboard layout requirements.
- **Do:** Five or more interactive controls, event listeners, and dynamic DOM updates.
- **Rules:** Output constrained to a single standalone `.html` file with embedded styling and vanilla JavaScript.

Each interface underwent a minimum of **3 iterative refinement rounds** focusing on UI polishing, dynamic event handling, mobile touch optimization, and error resolution. The full sequence of prompts and refinement rounds is documented in [`prompts.txt`](./prompts.txt).

---

## 💻 How to Run Locally

1. Clone or download this repository.
2. Open any `.html` file directly in any modern browser (Google Chrome, Microsoft Edge, Firefox, Safari).
3. No server or external build steps required.

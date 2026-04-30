# LLM Persona Activation Simulator

A visually immersive, interactive simulation of how Large Language Models (LLMs) navigate their "knowledge network" to adopt different personas.

**[🌐 Live Demo](https://juniormichieletto.github.io/llm-mindgraph-llm-demo/)**

![Project Preview](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🚀 Overview

This project provides a conceptual visualization of the internal workings of an LLM. It demonstrates how "attention" and "weights" shift across a neural-like network when a specific persona prompt is activated.

When you select a persona (e.g., Pirate, Software Engineer, or Poet), the simulator visualizes:
1. **Network Activation:** Connections (edges) between concept clusters light up.
2. **Particle Flow:** Information "packets" travel from the base language model to specialized knowledge domains.
3. **Weight Matrix:** A low-level view of mathematical weights shifting in real-time.

## ✨ Features

- **Interactive Graph View:** A dynamic 2D network representing semantic clusters.
- **Matrix Visualization:** A "weight-level" view showing the activation of different dimensions within the model.
- **Bilingual Support:** Fully localized in **Portuguese (PT)** and **English (EN)**.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Typewriter Effect:** Simulates model output generation in real-time.
- **High-Performance Canvas:** Smooth animations using HTML5 Canvas and optimized physics.

## 🛠️ Tech Stack

- **HTML5 Canvas:** For high-performance network and matrix animations.
- **Tailwind CSS:** For a modern, sleek UI overlay.
- **Vanilla JavaScript:** Core logic, physics engine, and state management (no heavy frameworks required).
- **Google Fonts (Inter):** For clean, readable typography.

## 🕹️ How to Use

1.  **Open `index.html`** in any modern web browser.
2.  **Switch Views:** Use the "View" button to toggle between the **Graph (Network)** and **Matrix (Weights)** modes.
3.  **Select a Persona:** Click on the buttons (Default, Pirate, Software Eng., Poet) to see how the model's attention shifts.
4.  **Change Language:** Use the PT/EN toggles in the top right.

## 🧠 Conceptual Explanation

- **The Base:** The central cluster represents core language understanding (syntax, grammar, common knowledge).
- **The Clusters:** Peripheral groups represent specialized training data or "fine-tuned" domains.
- **Activation:** The glow and particle flow represent the **Attention Mechanism**, where the model prioritizes certain neurons/weights based on the input prompt.

## 👨‍💻 Created By

**AJ (juniormichieletto)**
- [GitHub](https://github.com/juniormichieletto)

---
*Developed as a pedagogical tool to help visualize the abstract concepts of LLM prompting and weights.*

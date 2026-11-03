---
name: eli5
description: >-
  Explain complex topics, system architectures, data pipelines, and mathematical
  formulas like the user is someone who knows nothing about the topic, using a
  rich HTML visual explainer with big pictures, visual diagrams, step-by-step
  cards, formula breakdowns, and minimal text walls. Activate when the user
  mentions "eli5", "/eli5", "visual explainer", or asks to explain system logic
  and formulas visually.
---

# ELI5 — HTML Visual Explainer Skill

Explain like the reader is someone who knows nothing about this topic, using an **HTML Visual Explainer** (standalone HTML page, dashboard tab, or interactive artifact) with **big visual diagrams and few words**.

## Core Principles (Visual-First Architecture)

1. **Audience Calibration (零基礎友善 + 專家級精準)**
   - Start from the simplest mental model ("What goes in? What happens inside? What comes out?").
   - Pair every intuitive visual metaphor with the exact formula, numerator/denominator, and real-world numerical example.

2. **Visual-First Structure (大圖表、少文字、分步驟)**
   - **Never output a wall of text.** Replace long paragraphs with:
     - **Step-by-Step Visual Pipelines**: Numbered flow cards connected by arrows (`Step 1 ➔ Step 2 ➔ Step 3 ➔ Step 4`).
     - **Color-Coded Formula Anatomy Cards**: Highlight the **Numerator (分子)**, **Denominator (分母)**, and **Result (計算結果)** in distinct color badges, followed by a live plug-in calculation example.
     - **Side-by-Side Comparison Cards**: Contrast easily confused concepts (e.g., `人次 Applications` vs. `人數 Unique Headcount`, `甄選入學` vs. `申請入學`, `人數外推` vs. `報到率建模`).
     - **Red Error-Correction Callouts (`#dc2626`)**: When explaining data audits or formula reconciliations, highlight corrected figures and key denominators in bold red badges so discrepancies are immediately clear.

3. **HTML Design Standards**
   - Self-contained responsive HTML/CSS using clean grid layouts (`grid-template-columns`), high-contrast typography (`Noto Sans TC`, `Outfit`), FontAwesome icons, and interactive tabs or accordions.
   - Include a one-glance **"Cheat Sheet / Formula Dictionary"** table summarizing every metric's definition, mathematical formula, data source, and concrete example.


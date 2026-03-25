---
title: Pokémon Battle Arena & Explorer
publishDate: 2025-05-20 00:00:00
img: /assets/pokemon-project.webp
img_alt: Pokemon Alt
link: "https://pokemon-vue-sandy.vercel.app"
description: |
  I create this page for a code challenge interview, was developed in just one day.
tags:
  - Design
  - Dev - Vue
  - API
  - Deploy
repo: "https://github.com/Villarreal24/pokemon-vue3"
---

## Pokémon Battle Arena & Explorer

> A high-performance gaming web application built with Vue 3 (Composition API) and Vite

Formerly a lookup tool, this project has evolved into a full-scale battle simulator that leverages complex algorithms and premium UI patterns to deliver a "videogame-like" experience.

⚔️ Advanced Battle Simulation
* Turn-Based Engine: Implemented a sophisticated combat system where turns are calculated based on the Pokémon's native Speed stats.
* Intelligent Damage Algorithm: Developed a balanced combat logic considering:
    * Type Effectiveness: Dynamic multipliers for elemental advantages (Weakness/Resistance).
    * Critical Hits & Random Variance: A randomized +/- 20% modifier and 15% crit-chance for unpredictable, high-stakes combat.
* Real-time Combat Log: A scrollable history that tracks every move, damage dealt, and directional feedback, ensuring a transparent and engaging user experience.

🎨 Premium UI/UX & Animations
* Glassmorphism Design: Developed a modern aesthetic using translucent layers, backdrop blurs, and dynamic gradients that adapt visually to each Pokémon's primary type.
* Interactive Motions: Integrated Vue Transitions and custom Tailwind keyframes for "shaking" hit effects, countdown zooms, and smooth entrance/exit animations.
* Dynamic HP Feedback: Real-time health bars that transition color (Emerald > Amber > Red) and size during the battle sequence.

📱 Full Responsive Optimization
* Mobile-First Battle Layout: Unlike standard vertical stacking, I engineered a custom side-by-side grid for mobile battles, optimizing vertical space for the Combat Log and action controls.
* Elastic Components: Search bars and card containers perfectly adapt to any screen size, from tiny mobile devices to ultrawide monitors.

🔍 Discovery & Architecture
* Smart Filtering: Advanced pagination and elemental filtering system.
* Reactive State Management: Efficiently handles complex battle states (Intro, Fighting, Results) using Vue's ref and reactive primitives.
* Clean Code Standards: The entire codebase and UI have been standardized to English for professional maintainability.
Technical Stack: Vue 3 (Composition API), Vite, TypeScript, Tailwind CSS, PokeAPI Integration, Asynchronous Data Handling.

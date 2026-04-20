# 🏋️‍♂️ IRONPEAK | Cinematic Fitness Club Landing Page

> Premium fitness club landing page designed to provide a highly cinematic, scroll-driven web experience.

![IRONPEAK Banner](https://img.shields.io/badge/IRONPEAK-Premium_Fitness-E63946?style=for-the-badge)

IRONPEAK is an elite fitness club landing page boasting a striking cinematic aesthetic with scroll-driven frame animations, high-performance styling, and a seamless feature callout system. Built strictly with HTML, CSS, and Vanilla JavaScript, it offers lightning-fast performance and incredible visual depth designed to "wow" potential gym members.

## ✨ High-End Features
* **🎬 Cinematic Scroll Animation**: Hardware-accelerated frame sequence canvas powered by vanilla JS that scrolls dynamically based on user interaction.
* **💪 Premium Design System**: Employs dark themes, sleek glassmorphic UI cards, aesthetic typography (`Bebas Neue` & `Poppins`), & smooth micro-animations.
* **📱 Fully Responsive**: Fluid, dynamic layouts ensuring flawless execution across desktop, tablet, and mobile platforms.
* **⚡ Blazing Fast Delivery**: Progressively loaded experiences, optimized static generation, and aggressive static asset cache invalidation rules using Vercel.
* **📊 Live Elements**: Interactive animated KPI counters, Before & After transformation image sliders, and sticky chapter dot navigation.

## 🛠️ Technology Stack
* **Structure**: Semantic HTML5
* **Styling**: Vanilla CSS (Custom Properties, Flex/Grid Layouts, Transform Keyframes)
* **Logic & Interactions**: Vanilla JavaScript (Canvas API, `requestAnimationFrame`, Intersection Observers)
* **Deployment Ready**: Optimized via Vercel Engine (`vercel.json` configuration included for caching assets).

## 🚀 Running Locally

To experience the scroll-driven frame animation locally, you must serve the files through a development server (to bypass CORS restrictions for the local canvas element).

### Using Node.js
If you have Node installed, simply run:
```bash
npx serve .
```
Access the site at `http://localhost:3000`.

### Using Python
```bash
# Python 3+
python -m http.server 3000
```
Access the site at `http://localhost:3000`.

## ☁️ Deployment
This project is mapped and optimized for **Vercel**. 
The repository includes a `vercel.json` that sets aggressive cache control directives (specifically around the HD cinematic images within the `frames/` structure) allowing edge caching. This grants zero-latency scroll synchronization when deployed to production.

---
*Built with power, designed for performance.*



A polished, scroll-animated **3D landing page** built with Next.js, React Three Fiber, Three.js, and GSAP—designed to hit Awwwards-level polish.

---

## ✨ Features

- 🔥 3D visuals powered by **React Three Fiber** and **Drei**
- ⚡ Smooth transitions and scroll-based animations using **Framer Motion**
- 🎨 Clean, responsive UI with **TailwindCSS**
- 💌 Working contact form using **EmailJS**
- 🧱 Beautiful UI enhancements with **Aceternity UI** and **Magic UI**
- 🚀 Lightning-fast development with **Vite**

---

## 📁 Project Structure

```bash
app/
 ├── shirts/[slug]/page.tsx   # Dynamic product routes
 ├── layout.tsx               # Root layout
 ├── page.tsx                 # Main landing page
components/
 ├── Header.tsx / Footer.tsx  # UI components
 ├── Scene.tsx / Rig.tsx      # 3D scene setup
 ├── ScrollIndicator.tsx      # UI + animation helper
 ├── LoadingSkeleton.tsx      # Custom loader
 ├── FirstGrayModel.tsx       # 3D product models
 └── ViewCanvas.tsx           # Three.js canvas wrapper
lib/
 ├── colors.ts                # Theme colors
 ├── material.ts              # Reusable materials
 ├── patchThreeLoadingManager.ts # Preloading manager
 ├── useFirstAnimation.ts     # Custom animation hook
 └── useTextures.ts           # Texture loading helper
public/
 ├── icons/                   # Static icons
 ├── models/                  # 3D models
 ├── test/                    # Misc assets
 └── textures/                # Texture assets
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 15.x  
- npm or Yarn or pnpm  
- Basic familiarity with React / Three.js  



### Development

```bash
npm run dev
```
Open http://localhost:3000.

### Production Build

```bash
npm run build
npm run start
```
---

## 🧠 What You’ll Learn / Why Use This

This repo demonstrates how to blend modern UI and immersive 3D in a production-grade, high-performance web experience. If you're aiming to:

- Build portfolio-level interactive websites
- Level up in React + Three.js
- Learn real-world optimizations (preload, lazy load, smooth transitions)
- Understand scalable file structure and clean code
  
…then this is a solid starting point.


## 📖 Contributing

Contributions are welcome! If you spot a bug, want to add a new feature, or improve documentation:

1. Fork the repo
2. Create a branch feature/your-feature or fix/issue-name
3. Make your changes & test
4. Submit a Pull Request

Please keep PRs focused, include tests or screenshots when possible, and describe your change.

Thanks for checking it out! 🙌

---

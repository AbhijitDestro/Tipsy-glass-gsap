# 🍸 Tipsy Glass - GSAP Cocktail Experience

<div align="center">
  
  ![Tipsy Glass Banner](public/readme/hero.png)
  
  <p align="center">
    <strong>An immersive cocktail website powered by cutting-edge GSAP animations</strong>
  </p>
  
  <div align="center">
    <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=flat-square&logo=react&logoColor=white" />
    <img src="https://img.shields.io/badge/GSAP-3.12.2-88CE02?style=flat-square&logo=greensock&logoColor=white" />
    <img src="https://img.shields.io/badge/Tailwind-3.3.0-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/Vite-4.4.5-646CFF?style=flat-square&logo=vite&logoColor=white" />
  </div>
  
  <div align="center" style="margin-top: 20px;">
    <a href="#-demo">🎯 Demo</a> •
    <a href="#-features">✨ Features</a> •
    <a href="#-installation">🚀 Setup</a> •
    <a href="#-tech-stack">🛠️ Tech</a>
  </div>
  
</div>

---

## 🎯 Demo

Experience the magic of scroll-driven animations and immersive cocktail storytelling. This project showcases advanced GSAP techniques including parallax effects, scroll-triggered animations, and cinematic video synchronization.

> **Live Demo**: [View Project](https://tipsy-glass-gsap.vercel.app) | **Repository**: [GitHub](https://github.com/AbhijitDestro/Tipsy-glass-gsap)

## 🌟 What Makes This Special

Tipsy Glass isn't just another website—it's a **scroll-driven experience** that transforms how users interact with content. Every scroll reveals new animations, every section tells a story, and every interaction feels magical.

### 🎨 Animation Highlights

- **Scroll-Synced Storytelling**: Video playback tied to scroll position
- **Dynamic Text Reveals**: SplitText animations that bring typography to life
- **Parallax Depth**: Multi-layer scrolling for immersive depth
- **Pinned Sections**: Content that locks and transforms as you scroll
- **Fluid Transitions**: Seamless animations between sections

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎬 **Advanced Animations**

- SplitText reveals for impactful typography
- ScrollTrigger-powered timeline control
- Smooth parallax scrolling effects
- Pinned sections with scroll interactions
- Scroll-synced video playback

</td>
<td width="50%">

### 🎨 **Visual Effects**

- Image masking with scroll triggers
- Custom animated carousel
- Seamless multi-section timelines
- Responsive animation scaling
- Optimized performance

</td>
</tr>
</table>

## 🛠️ Tech Stack

<div align="center">

| Technology       | Purpose           | Version |
| ---------------- | ----------------- | ------- |
| **React**        | UI Framework      | 18.2.0  |
| **GSAP**         | Animation Library | 3.12.2  |
| **Tailwind CSS** | Styling           | 3.3.0   |
| **Vite**         | Build Tool        | 4.4.5   |

</div>

### Why These Technologies?

- **GSAP**: Industry-leading animation library with powerful ScrollTrigger capabilities
- **React**: Component-based architecture perfect for modular animation systems
- **Tailwind CSS**: Utility-first approach for rapid, responsive design
- **Vite**: Lightning-fast development with instant HMR for animation testing

## 🚀 Installation

### Prerequisites

Ensure you have these installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [Git](https://git-scm.com/)
- npm or yarn package manager

### Quick Start

```bash
# Clone the repository
git clone https://github.com/AbhijitDestro/Tipsy-glass-gsap.git

# Navigate to project directory
cd Tipsy-glass-gsap

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to view the project.

### Available Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
npm run lint     # Run ESLint
```

## 📁 Project Structure

```
tipsy-glass-gsap/
├── src/
│   ├── components/     # Reusable UI components
│   ├── sections/       # Page sections with animations
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Helper functions
│   └── assets/         # Images, videos, fonts
├── public/             # Static assets
└── README.md
```

## 🎨 Animation Techniques

### ScrollTrigger Implementation

```javascript
// Example: Parallax scrolling effect
gsap.to(".parallax-element", {
  yPercent: -50,
  ease: "none",
  scrollTrigger: {
    trigger: ".parallax-container",
    start: "top bottom",
    end: "bottom top",
    scrub: true,
  },
});
```

### SplitText Animations

```javascript
// Example: Text reveal animation
const splitText = new SplitText(".animated-text", { type: "chars" });
gsap.from(splitText.chars, {
  opacity: 0,
  y: 100,
  stagger: 0.02,
  duration: 0.8,
});
```

## 🎯 Performance Optimizations

- **Lazy Loading**: Images and videos load on demand
- **Animation Cleanup**: Proper GSAP timeline disposal
- **Responsive Scaling**: Animations adapt to screen size
- **Optimized Assets**: Compressed images and videos
- **Code Splitting**: Dynamic imports for better loading

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **GSAP Team** for the incredible animation library
- **React Team** for the robust framework
- **Tailwind CSS** for the utility-first approach
- **Vite Team** for the blazing-fast build tool

---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/AbhijitDestro">Abhijit</a></p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>

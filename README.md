# 🎨 Responsive Design Recreation

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=vercel)](https://omni-market-jet.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/bareeraaftab123-dev/Omni-market)

A complete, responsive web page built with **HTML**, **CSS**, and **JavaScript** — implementing desktop, tablet, and mobile layouts with modern UI/UX principles.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Acceptance Checks](#-acceptance-checks)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Responsive Breakpoints](#-responsive-breakpoints)
- [Live Demo](#-live-demo)
- [Author](#-author)

---

## 🎯 Overview

A fully responsive web page that adapts seamlessly across all device sizes using:

- **CSS Grid** for complex layouts
- **Flexbox** for flexible alignment
- **Media Queries** for breakpoint management
- **Responsive Images** with aspect-ratio preservation

The design features a modern, eye-catching dark theme with gold accents and smooth animations.

---

## ✨ Features

### Layout & Design
- ✅ **Fully Responsive** — Desktop, Tablet, Mobile
- ✅ **CSS Grid** — For main layout structures
- ✅ **Flexbox** — For navigation, forms, and flexible components
- ✅ **Glass-morphism UI** — Modern translucent effects
- ✅ **Gradient Accents** — Eye-catching color schemes
- ✅ **Smooth Animations** — Hover effects and transitions

### Components
- ✅ **Responsive Navigation** — Sticky header
- ✅ **Hero Section** — With gradient text and call-to-action
- ✅ **Product Cards** — Grid layout with images and hover effects
- ✅ **Contact Form** — Fully responsive with focus states
- ✅ **Difference Log** — Comparison with reference design
- ✅ **Device Preview** — Screenshot bar showing responsive views

### Accessibility
- ✅ **Focus States** — Visible outlines for keyboard navigation
- ✅ **Aspect-Ratio Preservation** — Images maintain proportions at any zoom level
- ✅ **Readable Text** — Rem/em units for scalable typography
- ✅ **200% Zoom Support** — Text remains readable at 200% zoom

---

## 📁 Project Structure

```
responsive-design-recreation/
│
├── index.html                 # Main HTML file
├── css/
│   └── style.css              # All styles (CSS Grid, Flexbox, Responsive)
├── js/
│   └── script.js              # JavaScript functionality
└── README.md
```

---

## ✅ Acceptance Checks

| Check | Status | Description |
|-------|--------|-------------|
| ✅ No layout breakage at common widths | Pass | Smooth transitions at all breakpoints |
| ✅ Text remains readable at 200% zoom | Pass | Relative units ensure scalability |
| ✅ Images preserve aspect ratio | Pass | `aspect-ratio` + `object-fit: cover` |
| ✅ Interactive elements have visible focus states | Pass | `:focus-visible` with contrast outlines |

---

## 🛠️ Technologies Used

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Styling
- **CSS Grid** — Main layout structure
- **Flexbox** — Component alignment
- **Media Queries** — Responsive breakpoints
- **Glass-morphism** — `backdrop-filter: blur()`
- **Gradients** — Linear gradients for accents
- **CSS Animations** — Keyframes for hover effects

---

## 📱 Responsive Breakpoints

| Device | Breakpoint | Columns | Layout |
|--------|------------|---------|--------|
| **Desktop** | 1024px+ | 3 columns | Full navigation, multi-column grid |
| **Tablet** | 768px - 1024px | 2 columns | Collapsed navigation, 2-column grid |
| **Mobile** | < 768px | 1 column | Single-column grid |

---

## 🎨 Color Palette

| Color | Name | Hex |
|-------|------|-----|
| 🟣 | Dark Purple | `#0f0c29` |
| 🔵 | Navy Blue | `#302b63` |
| 🟣 | Dark Blue | `#24243e` |
| 🟡 | Gold | `#fbbf24` |
| 🟠 | Dark Gold | `#f59e0b` |
| 🟣 | Light Purple | `#a78bfa` |

---

## 🚀 Installation

### Option 1: Download ZIP
1. Click **Code** → **Download ZIP**
2. Extract the folder
3. Open `index.html` in your browser

### Option 2: Clone Repository
```bash
git clone https://github.com/bareeraaftab123-dev/Omni-market.git
cd Omni-market
```

---

## 🎯 Usage

### Open in Browser
1. Navigate to the project folder
2. Double-click `index.html`
3. Or use Live Server in VS Code:
   - Right-click `index.html`
   - Select **"Open with Live Server"**

### View Responsive Design
1. Open browser DevTools (`F12`)
2. Click the device icon (📱)
3. Select different devices to test responsiveness

---

## 📸 Screenshots

### Desktop View
```
┌─────────────────────────────────────────────────────┐
│  OmniMarket  Products  Cart  Login  Register       │
│                                                     │
│      🍽️ Taste the Tradition                        │
│      Handcrafted Dishes · Fresh Ingredients        │
│                                                     │
│  ┌──────┐  ┌──────┐  ┌──────┐                    │
│  │ Card  │  │ Card  │  │ Card  │                    │
│  └──────┘  └──────┘  └──────┘                    │
└─────────────────────────────────────────────────────┘
```

### Mobile View
```
┌─────────────┐
│ ☰ OmniMarket │
│              │
│ 🍽️ Taste the │
│  Tradition   │
│              │
│ ┌──────────┐ │
│ │  Card    │ │
│ └──────────┘ │
│              │
│ ┌──────────┐ │
│ │  Card    │ │
│ └──────────┘ │
└─────────────┘
```

---

## 🔗 Live Demo

🌐 **Live URL:** [https://omni-market-jet.vercel.app](https://omni-market-jet.vercel.app)

---

## 📝 Difference Log

| Feature | Reference Design | My Recreation |
|---------|------------------|---------------|
| **Color Palette** | Minimalist | Vibrant with gradients |
| **Card Design** | Plain | Image-based with hover effects |
| **Animations** | None | Smooth transitions & keyframes |
| **Typography** | Standard | Custom fonts with gradient text |
| **UI Effects** | Flat | Glass-morphism & shadows |
| **Accessibility** | Basic | Focus states & keyboard nav |
| **Images** | Placeholders | High-quality Unsplash images |

---

## 👩‍💻 Author

**Bareera Aftab**
- GitHub: [@bareeraaftab123-dev](https://github.com/bareeraaftab123-dev)
- Project Link: [Omni Market](https://github.com/bareeraaftab123-dev/Omni-market)

---

## 📊 Project Status

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)

---

<div align="center">
  <sub>Built with ❤️ by Bareera Aftab</sub>
</div>
```



---

Your README is now ready! 🎉

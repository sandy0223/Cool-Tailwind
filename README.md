# 🚀 Learning Tailwind CSS

A modern React + Tailwind CSS project featuring vibrant space-inspired typography, animations, and minimalist UI design.

---

## ✨ Features

* 🌌 Space-themed UI
* 🎨 Gradient and image text effects
* ⚡ Tailwind CSS v4 utilities
* 🎥 Smooth custom animations
* 📱 Fully responsive layout
* 🧩 Reusable React components

---

## 📦 Tech Stack

* React
* Tailwind CSS v4
* Vite

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repo-url>
```

### 2. Navigate into the project

```bash
cd <project-folder>
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start development server

```bash
npm run dev
```

---

## 📁 Project Structure

```bash
src/
│
├── assets/
│   └── Space.png
│
├── components/
│   └── Test.jsx
│
├── App.jsx
└── main.jsx
```

---

## 🎨 Tailwind Custom Animation Example

```css
@import "tailwindcss";

@theme {
  --animate-float: float 3s ease-in-out infinite;

  @keyframes float {
    0%, 100% {
      transform: translateY(0px);
    }

    50% {
      transform: translateY(-10px);
    }
  }
}
```

Usage:

```jsx
<h1 className="animate-float">
```

---

## 🖼 Background Image Text Effect

```jsx
<h1
  className="text-9xl font-bold text-transparent bg-clip-text bg-cover bg-center"
  style={{
    backgroundImage: `url(${image})`,
  }}
>
  Exploring the Space
</h1>
```

---

## 📸 Preview

Minimal colorful astronomy-inspired design with animated typography.

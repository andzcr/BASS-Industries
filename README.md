# ✨ BASS Industries - Immersive Web Experience

![Video Live-Preview](https://github.com/andzcr/BASS-Industries/blob/main/bass-preview.gif?raw=true)

> **Live Preview:** https://andz-bass.netlify.app

## 💡 About This Concept

This isn't just a standard portfolio site. It is an **immersive digital concept** designed for a high-end architecture firm. The goal was to translate a "brutalist luxury" aesthetic into a fluid web experience. The focus was on making the user *feel* the quality and weight of the brand through every interaction, rather than just reading about it.

I steered clear of complex JS frameworks (like React) and bet on a heavily optimized "vanilla" approach, letting specialized libraries handle the motion and feel.

---

## 🚀 Key Features ("Under the Hood")

### 1. Premium "Feel" & Interaction
* **Smooth Scrolling (Lenis):** Integrated **Lenis** to eliminate choppy browser scrolling, replacing it with a fluid, inertial motion that gives the page a "heavy," premium sensation.
* **Custom Cursor:** A dynamic cursor using `mix-blend-mode` for visibility on all backgrounds. It subtly changes state and expands when hovering over interactive elements (buttons, links, cards).

### 2. Advanced Animation Engine
Powered by **GSAP (GreenSock)** and **ScrollTrigger**:
* **Horizontal Scroll:** The reviews section pins the page and transforms vertical scrolling into a smooth horizontal glide.
* **Parallax Depth:** Project images move at different speeds relative to the viewport to create a 3D depth effect.
* **Dynamic Stats:** Numbers in the "About" section feature count-up animations triggered exactly when they enter the viewport.

### 3. Robust Theming System
* **Native CSS Variables:** A robust Dark/Light mode system that performs instantly.
* **Global Updates:** Toggling the theme updates backgrounds, text, accents, and glassmorphism intensities simultaneously without performance hits.

### 4. Modern Architecture
* **Semantic HTML5:** Clean, accessible structure.
* **Tailwind CSS:** Used for rapid layout and responsiveness.
* **Custom CSS:** Heavily utilized for specific effects like flowing gradient borders and footer reveals.

---

## 🛠️ Tech Stack

* **Core:** HTML5, Vanilla JavaScript, CSS3
* **Styling:** Tailwind CSS, CSS Variables
* **Animation:** GSAP (ScrollTrigger core)
* **Smooth Scroll:** @studio-freight/lenis

---

## 📦 Getting Started

To run this project locally:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/bass-industries.git](https://github.com/yourusername/bass-industries.git)
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

4.  **Build for production**
    ```bash
    npm run build
    ```

---

## 📄 License

[MIT License](LICENSE)

# DeltaByte - High Performance Landing Page

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

**DeltaByte** is a modern, responsive landing page template designed for SaaS companies and high-tech startups. It features a sophisticated glassmorphism aesthetic, a mesh gradient background, and a lightweight Single Page Application (SPA) architecture without the need for heavy frameworks like React or Vue.

The project is contained entirely within a single HTML file, utilizing CDN links for libraries, making deployment instant and modification effortless.

## 🌟 Key Features

* **⚡ Zero-Lag Animations:** All animations (floating elements, gradients, hover states) are optimized for the GPU using `transform` and `opacity` properties to prevent layout thrashing.
* **💎 Glassmorphism UI:** Features backdrop-blur effects and translucent cards that work consistently across modern browsers.
* **📱 Fully Responsive:** Adaptive layout with a custom mobile navigation drawer.
* **🔄 Lightweight Router:** A custom vanilla JavaScript router handles navigation between "Home", "Toolkit", "Process", and "Intake" views without page reloads.
* **✨ Scroll Revelations:** Uses the `IntersectionObserver` API to lazily animate elements as they enter the viewport.
* **🎨 Animated Mesh Background:** A CSS-only animated gradient background that adds depth without compromising scroll performance.

## 🛠️ Tech Stack

* **Structure:** Semantic HTML5
* **Styling:** Tailwind CSS (via CDN) + Custom CSS for animations
* **Icons:** Feather Icons
* **Font:** Inter (Google Fonts)
* **Logic:** Vanilla JavaScript (ES6+)

## 🚀 Getting Started

Since this project is built as a single file, there is no build process or package installation required.

### Prerequisites
* A modern web browser (Chrome, Firefox, Safari, Edge).
* An internet connection (to load Tailwind and Fonts via CDN).

### Installation
1.  **Clone the repository:**
    ```bash
    git clone https://aakashjamali91.github.io/Scaleyourpotential.Deltabytes/
    ```
2.  **Run the project:**
    Simply open `index.html` in your browser.

    *Alternatively, if you use VS Code, right-click the file and select "Open with Live Server".*

## 🎨 Customization

### Changing the Color Scheme
The project uses Tailwind's arbitrary value syntax and custom CSS variables. To change the brand accent color, locate the `script` tag containing the Tailwind config:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: { 
                'brand-accent': '#6366f1', // Change this hex code
            },
            // ...
        }
    }
}

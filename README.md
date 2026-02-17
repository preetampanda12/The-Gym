# THE GYM — Forge Yourself

A premium, high-performance landing page designed for modern fitness centers and gyms. This project focuses on a sleek, athletic aesthetic with smooth animations and a mobile-first user experience.

## 🚀 Live Demo
You can view the live deployment at: [https://the-gym-forge-hq.pages.dev](https://the-gym-forge-hq.pages.dev)

## ✨ Features

-   **Premium Visuals**: Dark mode design with glassmorphism, high-quality typography (Bebas Neue & Barlow), and red accenting.
-   **Mobile-Optimized Slider**: Custom-built pricing slider for mobile users with touch-swipe support and smooth state transitions.
-   **Dynamic Navigation**: Single-page application (SPA) style navigation with smooth scroll and active state tracking.
-   **Interactive UI**: 
    -   Custom magnetic cursor effect.
    -   Intersection Observer for "scroll-reveal" animations.
    -   Interactive monthly/annual billing toggle.
    -   Testimonial carousel with auto-play and manual controls.
-   **SEO Ready**: Semantic HTML5 structure and optimized meta tags.

## 🛠️ Tech Stack

-   **Structure**: HTML5
-   **Styling**: Vanilla CSS3 (Custom properties, Flexbox, Grid)
-   **Logic**: Vanilla JavaScript (ES6+)
-   **Deployment**: Cloudflare Pages
-   **Tools**: Wrangler CLI, Node.js/npm

## 💻 Local Development

1.  **Clone the repository** (if applicable) or enter the project directory.
2.  **Install dependencies**:
    ```bash
    npm install
    ```
3.  **Start local server**:
    ```bash
    npm start
    ```
    This will launch a local development server (usually at `http://localhost:8080`).

## ☁️ Deployment

This project is configured for **Cloudflare Pages**. To deploy your changes:

1.  **Login to Cloudflare** (if not already):
    ```bash
    npx wrangler login
    ```
2.  **Deploy**:
    ```bash
    npm run deploy
    ```
    This command will build the assets and push them to your Cloudflare Pages project.

## 📁 Project Structure

-   `index.html`: The main entry point containing all structure and styling.
-   `package.json`: Project metadata and script configurations.
-   `wrangler.toml`: Cloudflare Pages deployment configuration.
-   `.gitignore`: Specifies files to be ignored by Git.

---
*Forged with iron & fire.*

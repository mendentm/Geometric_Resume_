# Thomas Mendenhall // Intelligent Systems Architect

This portfolio showcases the work of Thomas Mendenhall, an AI specialist and software engineer, highlighting expertise in advanced computational systems, data management, and full-stack development. The site features a dual aesthetic design: a minimalist, high-contrast **International Typographic Style (Swiss Style)** main page and a detailed, immersive **Technical Terminal** project archive.

---

## 🎨 Aesthetic & Design
The site utilizes two distinct themes to separate high-level branding from technical detail:

* **Main Page (`retro.html`):** Implements the **Swiss Style** (also known as the International Typographic Style). It is characterized by clean, asymmetrical grid layouts, stark typography (Inter, JetBrains Mono), and a high-contrast palette of Off-White, Black, and Vibrant Red/Orange.
    * **Goal:** To establish precision, order, and strong visual hierarchy.
* **Project Archive (`projects.html`):** Shifts to a **"Soft Technical" / "Cassette Futurism"** aesthetic.
    * **Palette:** Uses a specialized color scheme (Teal, Orange, Mustard Yellow) on a dark, grid-textured background.
    * **Interactivity:** Projects are displayed as technical modules with custom, subtle animations (Raster Plots, Data Flow diagrams) to visually represent the complexity of the code.

---

## 🛠️ Technical Overview

### Core Content
The portfolio is structured to validate high-level AI claims with concrete evidence:

1.  **Featured Projects:**
    * **Spiking Neural Simulation:** Advanced SNN modeling of Izhikevich neurons featuring autonomous pattern discovery.
    * **Evolutionary Game of Life:** A hybrid system using PyTorch and Genetic Algorithms to evolve CNNs for cellular automata prediction.
    * **WikiNews AI Analyzer:** A full-stack (Svelte/FastAPI) web application utilizing HuggingFace Transformers for real-time multilingual sentiment analysis and summarization.
2.  **Academic Foundations:** The **Technical Specifications** section directly lists relevant university coursework and high grades (e.g., AI 400 NLP, ROBAI 240 ML) from Bellevue College to substantiate core skills.

### Technologies & Principles
* **Frontend:** Pure HTML/CSS (No frameworks used for the structure).
* **Design Language:** Extensive use of CSS Grid and Flexbox for precise, responsive layout.
* **Branding:** Custom CSS animations (`@keyframes`) are used for element reveals, the name badge, and the scrolling footer banner to create a distinctive, branded user experience.

---

## 💡 Potential Improvements

This section lists features and optimizations that could be implemented to enhance performance, accessibility, and user experience.

* **Accessibility (A11y) Check:** The site utilizes high visual contrast, but a full audit should be performed, particularly ensuring all custom interactive elements (like the navigation) are fully accessible via keyboard input and screen readers.
* **Semantic HTML Refinement:** While basic structure is sound, ensure all decorative elements (like `hero-red-bar` and visual markers) carry `aria-hidden="true"` tags to optimize screen reader performance.
* **Lazy Loading:** Implement native image loading or a JavaScript solution for any project screenshots added later to prevent initial load times from slowing down the single-page scroll experience.
* **Modular CSS:** The CSS is currently contained in the `<style>` block. For long-term maintainability, the CSS should be externalized and ideally organized into modular files (e.g., `_variables.css`, `_layout.css`, `_projects.css`).

---

## 🚀 Next Steps (What to do Next)

To complete the portfolio, the following steps are required:

1.  **Insert Live Links:** Update the placeholder repository links (`href="#"` and `href="https://github.com/YOUR_USERNAME/REPO"`) in both `retro.html` and `projects.html` with the actual GitHub URLs.
2.  **Add Professional Details:** Populate the `mailto:` and social media links in the Contact section of `retro.html`.
3.  **Deploy and Test:** Host the two files (`retro.html` and `projects.html`) on a platform like GitHub Pages, Vercel, or Netlify, and test the cross-page links and anchor scrolling (e.g., clicking **Works** on the main page).
4.  **Aesthetics:** Increase spacing from name to title.
    Change red to darker or different color altogether 
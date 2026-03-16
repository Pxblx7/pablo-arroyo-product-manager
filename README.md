# Pablo Arroyo - Interactive CV | Product Manager

**[See the live CV at pxblx7.github.io/pablo-arroyo-product-manager](https://pxblx7.github.io/pablo-arroyo-product-manager)**

![Demo](https://github.com/pxblx7/pablo-arroyo-product-manager/blob/main/demo.gif?raw=true)

---

### 🚀 About This Project

This is not a traditional CV. It's an interactive web portfolio designed to present my career as a **Technology Product Manager** in a dynamic and memorable way. The concept is inspired by the "player cards" from the world of sports, using visualizations and animations to tell a story of impact, strategy, and results.

The project was recently migrated to a modern architecture, transforming an initial `index.html` prototype into a powerful, component-driven personal branding tool that demonstrates not only my experience but also my ability to pivot, architect solutions, and build products leveraging AI ("Vibecoding").

### 🛠️ Tech Stack

This site was rebuilt from the ground up to ensure maintainability, scalability, and high performance using a modern web stack:

* **Engine:** [Astro 5](https://astro.build/)
* **CSS Framework:** [Tailwind CSS v4](https://tailwindcss.com/)
* **Animations:** [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/)
* **Data Visualization:** Canvas API with [Chart.js](https://www.chartjs.org/)
* **Analytics:** [PostHog](https://posthog.com/)

The application leverages Astro's partial hydration and static site generation to guarantee maximum loading speed, shipping zero JavaScript except where strictly required for interactive elements.

### ✨ Key Features

* **100% Responsive Design:** Adaptable to any device with carefully tailored breakpoints.
* **Fluid Animations with GSAP:** Scroll-triggered micro-interactions and entrance animations that guide the user through the content.
* **Component-Driven Architecture:** Code structured modularly within Astro (`.astro` files) ensuring strict separation of concerns.
* **Interactive Radar Chart:** A dynamically rendering native HTML Canvas skill visualization.
* **Career Timeline:** A visual journey through my professional experience, enriched with logos and animations.
* **Achievements Carousel:** An interactive showcase for my main achievements and academic background.
* **Seamless i18n Localization:** Deep native bilingual functionality supporting English and Spanish seamlessly, with content decoupled into individual JSON configurations (`src/i18n/`).
* **Vibecoding Showcase:** A newly featured "AI Prototypes & Projects" section mapping real-world artifacts created via AI tooling.

### 📈 Analytics

To understand user interaction and continuously improve the experience, this project uses PostHog for product analytics. The following custom events are tracked:

* `contact_button_clicked`: Fired when a user clicks the main "Contact" button or the footer CTA.
* `language_switched`: Fired when the user toggles the application target locale.
* `download_cv_clicked`: Fired when a user attempts to download the PDF CV.

### 🔗 Contact

Interested in "signing"? Let's talk.

* **LinkedIn:** [linkedin.com/in/pablo-estéfano-arroyo-garrido](https://www.linkedin.com/in/pablo-estéfano-arroyo-garrido)
* **Email:** `pab.arroyo@outlook.com`

---

*This project was designed and built by Pablo Arroyo in collaboration with Antigravity / Gemini.*

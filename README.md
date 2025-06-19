# AeroInsight Weather Dashboard 

This is a dynamic and visually engaging single-page web application featuring an immersive parallax hero section, a fully interactive weather dashboard, and several modern UI effects. The project is built with vanilla HTML, CSS, and JavaScript, demonstrating a range of front-end development techniques.

## 🚀 Live Demo

You can see the live project in action here:

**[➡️ View Live Project](https://21ambuj.github.io/IITBhacathon/)**

## ✨ Key Features

Here are the six most important features of the application:

| Feature | Description |
| :--- | :--- |
| **1. Immersive Homepage** | A stunning, multi-layered parallax hero section that creates a 3D depth effect on scroll. It uses random, high-quality images for a unique experience on every visit, drawing the user into the application. |
| **2. Live Ripple Animation** | A beautiful, water-like ripple effect that follows the mouse cursor in real-time. This provides a delightful and modern interaction, making the UI feel more alive and responsive. |
| **3. Interactive Graph** | A powerful and responsive bar chart visualizes weather data. Built with Chart.js, it's fully interactive and updates dynamically based on user selections. |
| **4. Dynamic Info Cards** | The parallax homepage features animated information cards that appear to float in a 3D space. These cards display contextual details like location and temperature, enhancing the immersive experience. |
| **5. Detailed Stats Dashboard** | Below the hero, a complete dashboard allows users to dive into the data. You can filter statistics by season and weather condition, and the graph updates instantly to reflect your choices. |
| **6. Smooth Loader** | A clean loading spinner provides visual feedback to the user while page assets are being prepared in the background, ensuring a smooth and professional initial experience. |


## 🚀 Full Feature List

* **Immersive Parallax Hero:** A stunning, multi-layered hero section that creates a 3D depth effect on scroll. It uses random high-quality images from Unsplash for a unique experience on every visit.
* **Interactive Weather Dashboard:**
    * A bar chart that visualizes randomly generated weather data for various cities.
    * Dynamic filtering by season (Summer, Winter, All) and weather condition (Sunny, Rainy).
    * Visual thresholds for high and low temperatures are displayed directly on the chart using the Chart.js Annotation Plugin.
* **Light & Dark Theme Toggle:**
    * Seamlessly switch between a light and dark mode.
    * The user's theme preference is saved in `localStorage` and automatically applied on their next visit.
    * All components, including the charts, adapt to the selected theme.
* **Live Mouse Ripple Trail:** A beautiful, water-like ripple effect that follows the mouse cursor, providing a delightful and modern user interaction.
* **Loader Animation:** A clean loading spinner that provides feedback while the page assets are being prepared.
* **Responsive Design:** The layout is designed to be functional and aesthetically pleasing on a wide range of devices, with specific adjustments for mobile, tablet, and desktop screens.
* **Sticky Header:** The navigation header becomes opaque and sticks to the top of the viewport as the user scrolls past the hero section, ensuring easy navigation.

## 💻 Technologies Used

* **HTML5:** For the core structure and content of the web page.
* **CSS3:** For all styling, including theming with variables, complex layouts with Flexbox and Grid, animations, and the parallax effect.
* **JavaScript (ES6+):** For all interactivity, including:
    * DOM manipulation for the parallax scroll, theme switching, and ripple effect.
    * Data generation and state management for the dashboard.
* **Chart.js:** A powerful JavaScript library used to create the interactive and responsive bar chart for the weather dashboard.
* **Chart.js Annotation Plugin:** An official plugin for Chart.js used to draw lines and labels over the chart area for the temperature thresholds.
* **Unsplash API:** Used via `source.unsplash.com` to fetch random, high-quality images for the parallax hero section.


    * For the best experience and to avoid potential CORS issues with local file access (though not expected with this setup), it's recommended to use a simple local server. If you have VS Code, the "Live Server" extension is an excellent choice.

---

*This project was created to showcase modern front-end development practices and creative UI/UX implementations.*

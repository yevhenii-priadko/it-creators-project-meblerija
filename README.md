# 🛋️ Mebleuria — Creating the Space of Your Dreams

<p align="center">
  <img src="src/public/img/hero-section-preview.png" alt="Mebleuria Preview" width="100%">
</p>

---

## 🎯 About the Project

📄 **Live Page:** [View the project](https://evgeniy-sub8way.github.io/it-creators-project-meblerija/)

**Mebleuria** is a concept website for discovering and ordering modern furniture. The project is built as a high-performance landing page with full REST API integration, advanced filtering functionality, and a strong focus on UX/UI.

We created a product that combines a minimalist visual design with a solid technical foundation, providing fast loading times and smooth interactions across different devices.

---

## 🚀 Features

- **🧩 Dynamic Catalog:** Products and categories are dynamically loaded from the API.
- **🔍 Smart Filtering:** Filter and sort furniture instantly without reloading the page.
- **📦 Progressive Loading:** A Load More feature is implemented to optimize data loading and improve performance.
- **🖼️ Retina-Ready:** Graphics are optimized for high-density displays with 2x resolution support.
- **✨ Interactive Elements:** 
    - Responsive burger menu with scroll locking.
    - Reviews slider built with Swiper.js, including custom rating-rounding logic.
    - Interactive FAQ accordion for convenient access to additional information.
- **📩 Order Form:** Form validation with integration of iziToast for user notifications.

---

## 🛠 Tech Stack

[![My Skills](https://skillicons.dev/icons?i=js,html,css,github,vite,nodejs,figma&theme=light)](https://skillicons.dev)

| Component         | Technology / Library                     |
| :-------------    | :--------------------------------------- |
| **Styling**       | SCSS (BEM Methodology), CSS3 Transitions |
| **Logic**         | JavaScript (ES6+ Modules), Axios         |
| **Interactions**  | Swiper.js, Accordion-js, CSS Star Rating |
| **Notifications** | iziToast                                 |
| **Build Tool**    | Vite                                     |

---

## 📐 Responsiveness & Optimization

The project was thoroughly tested to ensure accurate implementation of the design across different screen sizes:

📱 _Mobile First:_  Fluid layout starting from 375px.

📟 _Tablet:_ Responsive layout from 768px, including custom burger menu positioning.

💻 _Desktop:_ Full-width layout optimized for 1440px.

🟡 _Performance:_ Loading indicators are displayed while waiting for server responses, with API request errors handled through try/catch.

---

## 👥 Our Team

|                                  Avatar                                   | Developer                                              | Role             | Section & Technical Contribution                                                                                                      |
| :-----------------------------------------------------------------------: | :----------------------------------------------------- | :--------------- | :------------------------------------------------------------------------------------------------------------------------------ |
| <img src="https://github.com/yevhenii-priadko.png" width="50" height="50"> | [Yevhenii Priadko](https://github.com/yevhenii-priadko) | **Team Lead**    | **Hero Section:** Project architecture, Vite build configuration, development of the main hero section, and coordination of technical decisions.     |
|    <img src="https://github.com/MyLyashok.png" width="50" height="50">    | [Mykola Lyashok](https://github.com/MyLyashok)         | **Scrum Master** | **About Us Section:** Development of the About Us section, README documentation, deadline tracking, and internal team communication.     |
|  <img src="https://github.com/Ivan-Shkilnyi.png" width="50" height="50">  | [Ivan Shkilnyi](https://github.com/Ivan-Shkilnyi)      | Frontend Developer     | **Order Modal:** Development of the order form, API-based data validation, and integration of iziToast notifications.    |
|    <img src="https://github.com/Liliia-2.png" width="50" height="50">     | [Liliia Pastushenko](https://github.com/Liliia-2)      | Frontend Developer   | **Global Loader & UI Logic:** Implementation of loading indicators (Spinner) and global error handling for API requests. |
|  <img src="https://github.com/alex-asriian.png" width="50" height="50">   | [Oleksii Asriian](https://github.com/alex-asriian)             | Frontend Developer     | **FAQ Section:** Development of an interactive FAQ accordion using the accordion-js library.              |
|  <img src="https://github.com/OlhaBorzhynska.png" width="50" height="50">  | [Olha Borzhynska](https://github.com/OlhaBorzhynska)     | Frontend Developer     | **Feedback Section:** Integration of the Swiper.js slider, rendering reviews from the database, and displaying ratings using Star Rating.           |
|  <img src="https://github.com/Olechka-coder.png" width="50" height="50">  | [Olga Tsasiuk](https://github.com/Olechka-coder)       | Frontend Developer     | **Details Modal:** Development of a product details modal with an image gallery, color selection markers, and product specifications.      |
|  <img src="https://github.com/SerdiukSerhii.png" width="50" height="50">  | [Serhii Serdiuk](https://github.com/SerdiukSerhii)     | Frontend Developer     | **Furniture List Section:** Dynamic catalog, product card rendering from the database, category filtering, and Load More functionality. |
|   <img src="https://github.com/Vika0605-av.png" width="50" height="50">   | [Viktoria Alexandrova](https://github.com/Vika0605-av) | Frontend Developer     | **Footer:** Footer development, social media integration, and configuration of secure external links using rel="noopener".  |
|   <img src="https://github.com/YuliaKozak.png" width="50" height="50">    | [Yuliia Kozak](https://github.com/YuliaKozak)          | Frontend Developer     | **Header:** Responsive navigation, smooth anchor scrolling, and burger menu logic with scroll locking.               |

---

## 🏗️ Project Structure

**The codebase is organized into modules to simplify maintenance and further development:**

🔹 src/partials/ — HTML fragments and page components.

🔹 src/js/ — JavaScript modules responsible for API logic, modals, and filtering.

🔹 src/css/ — Component styles written in SCSS.

🔹 public/ — Static assets.

---

## 💡 Additional Information

- **Backend API:** The project is integrated with the [Furniture Store API](https://furniture-store-v2.b.goit.study/api-docs/).
- **UI Kit:** Custom solutions for ratings and interactive elements were implemented according to the Figma design.
- **Deployment:** Automated deployment using GitHub Actions / GitHub Pages.

---

## ⚙️ Getting Started

**Clone the repository:**

```bash
git clone https://github.com/Evgeniy-sub8way/it-creators-project-meblerija.git
```

**Install dependencies:**

```bash
npm install
```

**Run the development server:**

```bash
npm run dev
```

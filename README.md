# DDCET Exam Study Material & Previous Papers Hub

A mobile-optimized, single-page web application providing one-click access to DDCET (Diploma to Degree Common Entrance Test) preparation resources. This front-end interface acts as a central hub for students to view, download, and access complete study guides and previous years' question papers hosted securely on Google Drive.

## 🚀 Live Preview
* **Updated Edition:** March 2024
* **Design Framework:** Vanilla CSS Custom Properties (CSS variables) + Flexbox/Grid
* **Iconography:** Font Awesome v6.4.0

---

## 📊 Repository Features & Statistics

The landing page provides structural components built to host and catalog the following metrics:
* **1 Complete Study Book:** The DDCET Master Guide 2024 (850+ pages, 45 MB, PDF format).
* **4+ Previous Papers:** Highly structured collection cards for multi-year question sheets.
* **Direct Cloud Access:** Seamless async loader triggers that forward users directly to Google Drive resources.
* **Responsive Engine:** Built-in breakpoint scaling for smooth rendering across Desktop, Tablet, and Mobile viewport sizes.

---

## 🛠️ Architecture & Tech Stack

* **HTML5:** Semantic architecture for search engine optimization and accessibility.
* **CSS3 Custom Properties:** The layout uses modern variable architecture for effortless rebranding:
    ```css
    :root {
        --primary: #2c3e50;
        --secondary: #3498db;
        --accent: #e74c3c;
        --light: #ecf0f1;
        --dark: #1a252f;
    }
    ```
* **UI Components Implemented:**
    * Sticky multi-device Navigation Header.
    * Flex-grid based Quick Statistics dashboard.
    * Hover-animated dynamic "Book Feature" list.
    * Clean multi-variant Button UI states (`.view`, `.download`, `.drive`).
    * Full-viewport `@keyframes spin` loading overlay module.

---

## 📦 Local Installation & Deployment

Since this project consists entirely of static client-side web assets, deployment requires no build compilation tools.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   

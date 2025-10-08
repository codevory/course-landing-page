# Skillshift - Python Course Landing Page

A fully responsive landing page for a "Python for Specialization" course, designed for a fictional e-learning platform called Skillshift. This project showcases a clean, modern layout with a focus on providing key information to attract potential students.

**🚀 [View the Live Demo](https://codevory.github.io/course-landing-page/)**

![Skillshift Landing Page Preview](./127.0.0.1_5500_dist_index.html(iPad Air\)%20(1).jpg)
*(Note: You'll need to add your screenshot to the repository for the image to display here)*

---

## ✨ Features

-   **Fully Responsive Design:** Adapts seamlessly to desktop, tablet, and mobile screens.
-   **Built with Tailwind CSS:** A utility-first CSS framework for rapid UI development and maintainable styling.
-   **Informative Sections:** Includes sections for curriculum, skills you'll gain, testimonials, and instructor details.
-   **Interactive UI Elements:** Features a tabbed layout for course info and collapsible curriculum details.

---

## 🛠️ Tech Stack

[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![GitHub Pages](https://img.shields.io/badge/github%20pages-%23121013.svg?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)

---

## 🔧 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need a basic development environment. Using the **Live Server** extension in VS Code is highly recommended for the best experience.

### Local Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/codevory/course-landing-page.git](https://github.com/codevory/course-landing-page.git)
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd course-landing-page
    ```

3.  **View the website:**
    -   Simply open the `dist/index.html` file in your browser.
    -   Or, for a better experience with live reloading, right-click on `dist/index.html` in VS Code and select "Open with Live Server".

### Building from Source (Optional)
If you want to modify the styles, you'll need to run the Tailwind CSS build process.

1.  **Run the Tailwind CLI watch command:**
    This command will watch for any changes in your source CSS files and automatically rebuild the `output.css` file.
    ```sh
    npx tailwindcss -i ./src/style.css -o ./dist/output.css --watch
    ```

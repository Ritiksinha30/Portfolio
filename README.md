# Personal Portfolio Website By Ritik Kumar Sinha
![image_alt]("https://github.com/user-attachments/assets/7e544877-1ee5-44ec-b22a-bedd8b792276")

A modern, fully responsive personal portfolio website designed to showcase skills, projects, and contact information. This project features a clean UI with dark/light mode support, smooth animations, and a custom-built static FAQ chatbot.

## 🚀 Features

-   **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices.
-   **Dark/Light Mode**: Toggle between themes with persistent preference saving (using `localStorage`).
-   **Smart FAQ Chatbot**: A pure JavaScript chatbot that answers common questions (Skills, Projects, Contact) with a smooth UI.
-   **Interactive UI**:
    -   Animated skill progress bars that fill on scroll.
    -   Floating "Hire Me" button that appears when scrolling.
    -   Smooth scrolling navigation.
    -   Fade-in animations for sections.
-   **Modern Styling**: Built with CSS Variables, Flexbox, and Grid for a polished look.

## 🛠️ Tech Stack

-   **HTML5**: Semantic structure and accessibility.
-   **CSS3**: Custom styling, animations, and responsive layout (No frameworks like Bootstrap or Tailwind used).
-   **JavaScript (ES6+)**: Logic for the chatbot, theme toggle, scroll animations, and mobile menu.
-   **Font Awesome**: Icons for social links and UI elements.
-   **Google Fonts**: Typography (Outfit font family).

## 🤖 Chatbot Details

The chatbot is built entirely with **Vanilla JavaScript** and does not require a backend server.

-   **Logic**: It uses keyword matching to find answers from a predefined `faq` object.
-   **Keywords**:
    -   `hello`, `hi` -> Greeting
    -   `skills` -> Lists technical skills
    -   `projects` -> Directs to projects section
    -   `contact`, `email`, `hire` -> Provides contact info
-   **Fallback**: If a question isn't recognized, it provides a helpful default response.

## 📂 Project Structure

```
/
├── index.html      # Main HTML file
├── style.css       # Global styles and themes
├── script.js       # Application logic (Chatbot, Animations, Theme)
├── assets/         # Images and static assets
└── README.md       # Project documentation
```

## 🚀 How to Run

1.  Clone the repository or download the files.
2.  Open `index.html` in any modern web browser.
3.  Enjoy!

## 📝 License

Copyright (c) 2025 Ritik Kumar Sinha

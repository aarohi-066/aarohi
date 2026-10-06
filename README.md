# Aarohi Suman - Personal Portfolio Website

A modern, responsive, and clean personal portfolio website created for **Aarohi Suman**, undergraduate student in **B.Tech Computer Science** at **JECRC University, Jaipur**.

---

## 🌟 Overview & Design Philosophy

This portfolio was designed specifically to represent an authentic undergraduate computer science student:
- **100% Honest & Accurate**: No fake projects, invented certifications, or fabricated experience.
- **Modern & Professional UI**: Built with responsive layouts, glassmorphism cards, subtle ambient glows, and dark/light mode toggle.
- **Modular & Easy to Edit**: Every section contains clear HTML comments (`<!-- EDIT HERE: ... -->`) pointing directly to where personal details can be added as skills, projects, and certifications are earned.

---

## 📂 Project Structure

```
Digital Data AG/
├── index.html       # Semantic HTML5 structure for all sections
├── style.css        # Modern CSS design tokens, dark/light themes, animations & responsive media queries
├── script.js        # Theme toggling, mobile drawer navigation, scrollspy active link tracking & contact form
└── README.md        # Documentation and customization guide
```

---

## 🚀 How to Run the Website

You don't need any complex dependencies or web servers to run this site:
1. Simply double-click `index.html` in your file explorer to open it directly in any modern browser (Chrome, Edge, Firefox, Safari).
2. Alternatively, if you use **Visual Studio Code**, install the **Live Server** extension, right-click `index.html`, and select **"Open with Live Server"**.

---

## ✏️ Step-by-Step Customization Guide

When you're ready to update your details, open `index.html` in any text editor (such as VS Code or Notepad) and make the following edits:

### 1. Education (`#education`)
- Locate `<div class="edu-placeholder-box">`.
- Update your expected graduation year (e.g., `2024 – 2028`) or add current semester coursework (e.g., *Data Structures, Discrete Mathematics, OOP*).

### 2. Technical Skills (`#skills`)
- Search for the `<div class="skills-grid">` section.
- Replace the placeholder spans:
  ```html
  <span class="skill-pill placeholder-pill">[Programming Language 1]</span>
  ```
  with your actual learned skills (e.g., `C++`, `Java`, `Python`, `HTML/CSS`, `Git`).

### 3. Projects (`#projects`)
- Search for `<div class="projects-grid">`.
- Replace the upcoming project cards with your real project details:
  - Project Title
  - Problem statement & description
  - Technologies used (e.g., `Python`, `Flask`, `SQLite`)
  - Replace the disabled button with your GitHub repository link:
    ```html
    <a href="https://github.com/your-username/your-project" target="_blank" class="btn btn-secondary">
      GitHub Repository
    </a>
    ```

### 4. Certifications & Achievements (`#certifications`)
- Search for `<div class="certifications-grid">`.
- Replace the placeholder certification cards with any course certificates (e.g., Coursera, NPTEL, HackerRank) or hackathon awards.

### 5. Contact Information (`#contact`)
- In `<div class="contact-info-pane">`:
  - Update `mailto:your.email@example.com` with your real email address.
  - Update `+91 XXXXX XXXXX` with your phone number.
  - In the social links section, replace `https://linkedin.com/in/your-profile` and `https://github.com/your-username` with your real URLs.

### 6. Connecting the Contact Form
- Currently, the form has a client-side JavaScript handler that validates inputs and displays a success alert.
- To receive actual emails directly to your inbox without a backend server, you can use free services like:
  - [Formspree](https://formspree.io/) (simply set `<form action="https://formspree.io/f/your_form_id" method="POST">`)
  - [Web3Forms](https://web3forms.com/)
  - [EmailJS](https://www.emailjs.com/)

---

## 📱 Features Included
- **Dark / Light Theme Toggle**: Persistent via `localStorage`.
- **Responsive Layout**: Tailored for Mobile, Tablet, Laptop, and Desktop screens.
- **Scrollspy Navigation**: Automatically highlights the active section in the navbar as you scroll.
- **Mobile Drawer Menu**: Smooth animated hamburger navigation for small screens.
- **Accessible & Semantic**: Uses semantic HTML5 tags and accessible contrast ratios.

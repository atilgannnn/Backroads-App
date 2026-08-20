# 🌍 Backroads Web Application

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=netlify)](https://temp-backroads-react-app.netlify.app)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Netlify](https://img.shields.io/badge/Deployment-Netlify-00C7B7?style=for-the-badge&logo=netlify)](https://www.netlify.com/)

A modern, responsive travel agency landing page built with **React** and deployed via **Netlify**. This project demonstrates React component architecture, modular data rendering, smooth scrolling, and deployment workflow.

🌐 **Live Application:** [temp-backroads-react-app.netlify.app](https://temp-backroads-react-app.netlify.app)

---

## 🚀 Key Features

* **Modular Component Architecture:** Clean separation of concerns with components (`Navbar`, `Hero`, `About`, `Services`, `Tours`, `Footer`, `Title`).
* **DRY Data Management:** Dynamic content rendering driven by structured JavaScript data models (`data.js`).
* **Smooth Navigation:** In-page smooth scrolling with custom CSS offsets.
* **Responsive Layout:** Cross-device UI built with modern HTML5/CSS3 and FontAwesome vector icons.
* **Continuous Deployment:** Integrated CI/CD pipeline hosted on Netlify via GitHub.

---

## 🛠️ Tech Stack & Dependencies

* **Frontend:** React, HTML5, CSS3, JavaScript (ES6+)
* **Iconography:** FontAwesome 
* **Deployment & Hosting:** Netlify, Git, GitHub

---
## 📁 Component & Project Structure

src/
├── components/
│   ├── About.js         # About section
│   ├── Footer.js        # Footer with dynamic year & social links
│   ├── Hero.js          # Hero banner
│   ├── Navbar.js        # Top navigation with smooth scroll
│   ├── Services.js      # Offered services grid
│   ├── Title.js         # Reusable section title component
│   └── Tours.js         # Featured tours list
├── data.js              # Centralized data source for links & content
├── App.js               # Root component assembling all modules
├── index.css            # Global styling
└── index.js             # React DOM entry point

---

## 💻 Local Development Setup

Follow these steps to run the project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/atilgannnn/backroads-app.git](https://github.com/atilgannnn/backroads-app.git)
   cd backroads-app/final

2. **Install dependencies:**
   ```bash
   npm install

3. **Start the development server:**
   ```bash
   npm start

4. **Build for production:**
   ```bash
   npm run build

The application will run locally at : http://localhost:3000       


   

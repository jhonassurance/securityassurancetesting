# 🚀 Quantix - Task 3

A modern, responsive multi-page web application built using **HTML5, CSS3, and Vanilla JavaScript** as part of the internship program. This project extends the previous Quantix website by integrating real-world JavaScript functionality, including a live Weather Dashboard powered by the OpenWeather API and a fully functional Todo Manager with Local Storage support.

---

## 📌 Project Overview

Quantix is a responsive technology website designed to demonstrate practical front-end development skills. In **Task 3**, the project focuses on implementing advanced JavaScript concepts such as API integration, Local Storage, DOM manipulation, modular JavaScript, and interactive UI components.

The application provides users with live weather information, a task management system, interactive product previews, and a clean responsive interface.

---

## ✨ Features

### 🌤️ Weather Dashboard

* Search weather by city name
* Live weather data using OpenWeather API
* Current temperature
* Feels like temperature
* Humidity
* Wind speed
* Atmospheric pressure
* Visibility
* Sunrise & Sunset (city local time)
* Weather description
* Weather icon
* Input validation
* Responsive weather interface

---

### âœ… Todo Manager

* Add new tasks
* Mark tasks as completed
* Edit existing tasks
* Delete individual tasks
* Search tasks instantly
* Filter:

  * All
  * Active
  * Completed
* Mark all tasks as completed
* Clear completed tasks
* Automatic progress tracking
* Data saved using Local Storage

---

### 🛍️ Product Experience

* Interactive product cards
* Product quick-view modal
* Responsive product layout
* Smooth animations

---

### ðŸŽ¨ User Interface

* Fully responsive layout
* Dark & Light mode support
* Mobile-first design
* Smooth transitions
* Modern card-based UI
* Reusable JavaScript modules

---

## ðŸ› ï¸ Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript (ES6 Modules)
* OpenWeather API
* Local Storage API

---

## ðŸ“‚ Project Structure

```text
Quantix/
â”‚
â”œâ”€â”€ css/
â”‚   â”œâ”€â”€ style.css
â”‚   â”œâ”€â”€ weather.css
â”‚   â””â”€â”€ todo.css
â”‚
â”œâ”€â”€ images/
â”‚
â”œâ”€â”€ js/
â”‚   â”œâ”€â”€ main.js
â”‚   â”œâ”€â”€ weather.js
â”‚   â”œâ”€â”€ todo.js
â”‚   â”œâ”€â”€ storage.js
â”‚   â”œâ”€â”€ modal.js
â”‚   â”œâ”€â”€ navigation.js
â”‚   â”œâ”€â”€ slider.js
â”‚   â”œâ”€â”€ theme.js
â”‚   â”œâ”€â”€ validation.js
â”‚   â”œâ”€â”€ config.example.js
â”‚   â””â”€â”€ config.js (ignored)
â”‚
â”œâ”€â”€ index.html
â”œâ”€â”€ about.html
â”œâ”€â”€ products.html
â”œâ”€â”€ weather.html
â”œâ”€â”€ todo.html
â”œâ”€â”€ contact.html
â””â”€â”€ README.md
```

---

## ðŸ”‘ Weather API Setup

This project uses the **OpenWeather API**.

Create a file named:

```text
js/config.js
```

Add your API key:

```javascript
export const OPENWEATHER_API_KEY = "YOUR_API_KEY";
```

An example configuration file is already included:

```text
js/config.example.js
```

---

## â–¶ï¸ Running the Project

1. Clone the repository

```bash
git clone <repository-url>
```

2. Open the project folder.

3. Create:

```text
js/config.js
```

4. Add your OpenWeather API key.

5. Launch the project using **Live Server** in VS Code.

---

## ðŸ“± Responsive Design

The application has been optimized for:

* Desktop
* Laptop
* Tablet
* Mobile Devices

---

## ðŸŽ¯ Task 3 Objectives Completed

* Responsive web pages
* JavaScript modules
* DOM manipulation
* Event handling
* Weather API integration
* Local Storage implementation
* Todo Manager
* Product quick-view modal
* Form validation
* Interactive UI components
* Modern responsive design

---

## ðŸ”’ Security

The OpenWeather API key is **not committed** to GitHub.

* `config.js` is ignored using `.gitignore`
* `config.example.js` is provided as a template for setup

---

## 👨‍💻 Author

**Dheeraj Yadav**

Internship Project – Task 3

Built with â¤ï¸ using HTML, CSS, and JavaScript.



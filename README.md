## 🚀 30-Day Coding Challenge: Day 17

This project is the seventeenth entry in my 30-day coding challenge. Today's goal was to build a live search filter, a common UI pattern, and to learn one of React's most important hooks: `useEffect`.

### 📖 Project Overview

This is a clean and responsive search filter application built with React. It displays a list of countries and allows the user to filter the list in real-time by typing into a search input. The application demonstrates how to manage user input as "controlled components" and how to perform side effects with the `useEffect` hook.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jun-25-2025 15-58-45](https://github.com/user-attachments/assets/dea24707-92a9-4f31-ae56-351d053a92fe)

### 🌟 Key Features

* **Real-Time Filtering:** The list of countries updates instantly as the user types into the search field.
* **Controlled Component:** The search input's value is controlled by React state, which is a fundamental pattern in React for handling forms.
* **Efficient Filtering:** The filtering logic is performed on every render, ensuring the displayed list is always in sync with the search term.
* **`useEffect` Hook:** Demonstrates the use of the `useEffect` hook to perform side effects, such as logging the search term to the console whenever it changes.
* **Dynamic Rendering:** The list of results is dynamically rendered by mapping over the filtered data array.
* **Modern & Responsive UI:** Styled with Tailwind CSS for a clean, modern, and fully responsive layout.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.
* **Font Awesome:** For icons.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-search-filter.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-search-filter
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a crucial exercise for understanding two of the most important hooks in React:

* **The `useEffect` Hook:** Learning how to perform side effects after a component renders and how to control when the effect runs by using a dependency array.
* **The `useState` Hook (Reinforced):** Further practice with managing component state.
* **Controlled Components:** Mastering the pattern of linking form input values directly to React state.
* **Real-time Data Filtering:** Implementing logic to filter an array based on user input without modifying the original data source.

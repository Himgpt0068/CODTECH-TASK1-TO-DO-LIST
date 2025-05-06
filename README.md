
## TO-DO-LIST
NAME: HIMANSHU GUPTA.


Domain: Web Development.


## Table of Content
1. [Introduction](#1-introduction)
2. [Project Overview](#2-project-overview)
3. [Getting Started](#3-getting-started)
4. [Code Structure](#4-code-structure)
5. [Dependencies](#5-dependencies)
6. [Code Refactoring](#6-code-refactoring)
7. [Deployment](#7-deployment)
8. [Usage](#8-usage)
9. [License](#9-license)

## 1. Introduction
 
Welcome to the documentation for the TO-DO-LIST App, a simple and refactored project designed to manage your tasks efficiently. This document provides an overview of the project, its code structure, refactoring details, clean code practices, design patterns, deployment information, and usage instructions.

## 2. Project Overview

The TO-DO-LIST App is a web-based application developed to help users manage their tasks by providing a user-friendly interface for adding, editing, and deleting tasks. The app also supports task filtering based on status (All, Pending, Completed) and incorporates a theme switcher for a personalized user experience.

## 3. Getting Started

To get started with the TO-DOIT App, follow these steps:

### Prerequisites

Make sure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox, Safari)
- An internet connection (for fetching external dependencies)

### Installation

1. **Clone the Repository:**

   ```bash
   https://github.com/Himgpt0068/TO-DO-LIST
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd TO-DO-LIST
   ```

3. **Open `index.html` in a Browser:**

   Open the `index.html` file in your preferred web browser.

## 4. Code Structure

The project follows a modular and organized structure to enhance readability, maintainability, and scalability. Key components include:

- **HTML (`index.html`):** The main structure of the web page.
- **CSS (`style.css`):** Styles to define the appearance of the web page.
- **JavaScript (`main.js`):** Logic for handling user interactions, managing tasks, and implementing theme switching.
- **Fonts (`Poppins`):** Imported from Google Fonts for consistent typography.

## 5. Dependencies

- **Tailwind CSS:** Used for styling the components. It's linked through CDN in the `index.html` file.
- **Daisy UI:** A CSS library for UI components, linked through CDN.
- **Boxicons:** Icons library, linked through CDN.
- **Google Fonts (Poppins):** Font used for the app, linked in the `style.css` file.

## 6. Code Refactoring

### Code Smells Addressed:

1. **Monolithic Structure:**
   - **Code Smell:** Original code had a monolithic structure, making it harder to maintain.
   - **Refactoring:** Introduced modularization through separate classes (`TodoItemFormatter`, `TodoManager`, `UIManager`, and `ThemeSwitcher`), each with a distinct responsibility.

2. **Global Functions:**
   - **Code Smell:** Original code used global functions for event handling, reducing modularity.
   - **Refactoring:** Event handling encapsulated within the `UIManager` class, promoting better organization and separation of concerns.

3. **HTML Manipulation in Multiple Places:**
   - **Code Smell:** Original code directly manipulated HTML in scattered locations.
   - **Refactoring:** Centralized HTML manipulation within the `UIManager` class for consistency.

4. **Lack of Error Handling:**
   - **Code Smell:** Original code lacked proper error handling.
   - **Refactoring:** Introduced error handling in the `UIManager` class for improved user experience and robustness.

## 7. Deployment

The TO-DO-LIST App is deployed and accessible online.

## 8. Usage

1. **Adding a Task:**
   - Enter the task in the input field.
   - Optionally, set a due date using the date input.
   - Press Enter or click the "+" button to add the task.

2. **Editing a Task:**
   - Click the "Edit" button on a task.
   - Modify the task details.
   - Click the "Check" button to save changes.

3. **Completing a Task:**
   - Click the "Check" button on a task to toggle its completion status.

4. **Deleting a Task:**
   - Click the "Trash" button on a task to delete it.

5. **Filtering Tasks:**
   - Use the "Filter" dropdown to filter tasks by status (All, Pending, Completed).

6. **Clearing All Tasks:**
   - Click the "Delete All" button to clear all tasks.

7. **Theme Switching:**
   - Use the palette icon in the top-right corner to open the theme switcher.
   - Select a theme from the available options.

## 9. License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) and was originally developed by [Himgpt0068](https://github.com/Himgpt0068/CODTECK-TASK1).

## Screenshots
#   <img src="https://github.com/Himgpt0068/CODTECK-TASK1/blob/main/Screenshot%20(176).png?raw=true" width="100%">





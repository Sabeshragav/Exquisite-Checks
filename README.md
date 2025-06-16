# Exquisite Checks Project

## Description

Exquisite Checks is a web-based platform offering learning materials, assessments for various programming languages, and a fun number guessing game. It also includes basic informational pages like About and Contact.

## Features

- **Learning Hub:** Access learning resources for different programming languages.
  - Python
  - Java
  - JavaScript
  - C/C++
  - C#
  - PHP
  - TypeScript
  - SQL
- **Assessment Center:** Test your knowledge with quizzes for each programming language.
- **Fun Zone:** A simple "Guess the Number" game.
- **User Authentication:** Includes a Login/Signup page.
- **Informational Pages:** About the project and Contact details.

## Project Structure

The project consists primarily of HTML, CSS, and some JavaScript files.

- **HTML Files (`.html`):** Define the structure and content of the web pages.
  - `start.html`: The initial landing page for the website.
  - `home.html`: The main homepage, providing navigation to different sections.
  - `loginpage.html`: Handles user login and signup.
  - `learning.html`: Central page for accessing learning materials.
  - `ass.html`: Central page for accessing assessments.
  - `[1-9]L.html`: Individual learning pages for specific languages (e.g., `1L.html` for Python learning).
  - `[1-9]q.html`: Individual quiz/assessment pages for specific languages (e.g., `1q.html` for Python quiz).
  - `fungame.html`: Contains the "Guess the Number" game.
  - `health.html`: A page intended for health-related content.
  - `about.html`: Provides information about the project.
  - `contact.html`: Displays contact information.
- **CSS Files (`.css`):** Style the visual presentation of the web pages.
  - `rogue.css`: The main stylesheet used across most pages.
  - `loginpage.css`: Specific styles for the login/signup page.
- **Image Files (`.jpeg`):** Used for icons, backgrounds, and other visual elements.
- **JavaScript (embedded and `.js`):**
  - `loginpage.js` (expected): Likely handles the logic for the login/signup forms.
  - Embedded script in `fungame.html`: Manages the game logic.

## Getting Started

To run this project:

1.  Clone or download the repository/files to your local machine.
2.  Open the `start.html` file in a web browser.
    - Alternatively, you can start by opening `home.html`.

## Pages Overview

- **`start.html`**: Initial entry point. Links to Home and About.
- **`home.html`**: Main dashboard. Links to Learning, Assessment, and Fun Game sections.
- **`learning.html`**: Lists available programming languages for learning. Each language links to its specific `[number]L.html` page.
- **`ass.html`**: Lists available programming language assessments. Each language links to its specific `[number]q.html` page.
- **`[number]L.html` files**: Content pages for learning a specific programming language.
- **`[number]q.html` files**: Quiz pages for a specific programming language.
- **`fungame.html`**: An interactive number guessing game.
- **`loginpage.html`**: Provides forms for user login and registration.
- **`about.html`**: Contains information about the "Exquisite Checks" project.
- **`contact.html`**: Shows contact details for the project creators.
- **`health.html`**: A page for health-related information.

## Technologies Used

- HTML5
- CSS3
- JavaScript (for interactive elements like the game and login form)

---

This README provides a basic overview. You can expand it with more details about specific features, setup instructions if any external dependencies are added, or contribution guidelines if applicable.

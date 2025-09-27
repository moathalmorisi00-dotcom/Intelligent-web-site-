# Intelligent-web-site-
A web site has four educational courses



---

📄 README: Intelligent Courses – Complete Web Design Project

Project Title: Intelligent – Arabic-Language Educational Courses Website  
Author: Moath Al Morisi  
Target Audience: Arabic-speaking learners interested in foundational IT courses  
Language Direction: Arabic (Right-to-Left layout)  
Technologies Used: HTML5, CSS3, JavaScript, jQuery, Service Workers, PWA manifest

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📝 Project Purpose and Objectives:

The “Intelligent” web project is a **static front-end educational website** developed as a student course project with the goal of providing **introductory learning content** for key topics in information technology. It is built with accessibility, simplicity, and a clean user experience in mind — particularly for **Arabic-speaking users**.

This project simulates the structure of an e-learning platform, containing content pages for different IT disciplines like:
- Cyber Security
- Databases
- Networking
- Ethical Hacking

It demonstrates key web design and development concepts including:
- Responsive layout design
- Multi-page site architecture
- RTL (Right-To-Left) content flow for Arabic
- PWA (Progressive Web App) fundamentals for offline access
- Use of jQuery for dynamic page interactions

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🌐 Site Architecture and Content Overview:

The website consists of a **homepage** and four dedicated **course pages**. Each page is static HTML and is styled consistently using a central stylesheet. Here's a breakdown:

1. `index.html` (Homepage):
   - Main landing page introducing the “Intelligent” platform
   - Contains a responsive navigation bar with scroll links
   - Includes four major sections:
     • Hero section with branding and welcome text  
     • Courses overview section with buttons linking to each course  
     • Advantages section listing reasons to choose this platform  
     • Contact section with basic communication details
   - A login button is included (as a prototype only — not functional)

2. `Cyber_Security_Fundamental.html`:
   - Page dedicated to cyber security basics
   - Outlines the definition, importance, threats, and protections in digital security
   - Tailored for beginners looking to understand online safety

3. `data_base.html`:
   - Introduces relational and non-relational databases
   - Covers use cases of database systems and their role in modern applications

4. `Ethical_haching.html`:
   - Explains ethical hacking and its difference from malicious hacking
   - Covers penetration testing and white-hat hacker responsibilities

5. `Networks.html`:
   - Discusses basic concepts of computer networking
   - Includes information about types of networks, topologies, and communication models

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🎨 Styling and Design:

- `css/style.css`:  
  The website uses a custom stylesheet to apply consistent branding across all pages.
  - Utilizes Google Fonts (Cairo) for modern Arabic typography
  - Designed with media queries for responsiveness across devices
  - Colors, buttons, layouts, and spacing are managed for clarity and readability

- RTL Layout:
  - All content is presented in Arabic using a Right-To-Left layout direction
  - Ensures natural reading flow for Arabic-speaking users

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🔌 Interactivity and PWA Features:

- jQuery:
  - Included via a local copy in the `Jquiry/` folder
  - Powers interactivity such as mobile menu toggling and showing/hiding login modal

- Service Worker (`sw.js`) and Manifest (`manifest.json`):
  - These files make the project PWA-capable
  - The service worker allows limited offline caching of site assets
  - The manifest enables the site to be installed on devices as a web app

Note: To fully utilize PWA capabilities, the site must be served from a secure origin (https or localhost).

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📁 File/Folder Structure Overview:

├── index.html ├── Cyber_Security_Fundamental.html ├── data_base.html ├── Ethical_haching.html ├── Networks.html ├── css/ │   └── style.css ├── images/ │   └── [site images: logos, banners, etc.] ├── Jquiry/ │   └── jquery-3.7.1.min.js ├── manifest.json ├── sw.js

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
▶️ How to View or Run the Website:

**Option 1: View in Browser (Basic Use)**
1. Download and extract the ZIP file
2. Open `index.html` in any modern web browser
3. Use navigation to browse through the pages

**Option 2: Enable PWA Functionality (Recommended)**
To test the offline capabilities:
1. Run a local server using a tool like `npx serve` or Live Server extension in VS Code
2. Open `http://localhost:5000` or similar
3. Allow installation prompt if shown
4. Test offline access by disconnecting and navigating to previously visited pages

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
⚠️ Requirements & Notes:

- A modern browser (Google Chrome preferred for PWA features)
- Internet access to load Google Fonts (Cairo)
- Local server setup if you want to test full PWA support
- No database or backend is connected — this is a **front-end only** project

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📬 Attribution & Notes:

This project was developed by **Moath Al Morisi** as a **course project** to demonstrate the ability to build a structured, educational, Arabic-language website using core front-end technologies.

While static in nature, the website architecture demonstrates:
- Clean and professional layout
- Multi-page navigation
- Accessible content design
- Integration of modern web capabilities (PWA)

It can serve as a foundation for future dynamic development (e.g., adding a real login system, back-end database support, or interactive course enrollment features).

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📌 Future Improvements (Suggested Enhancements):

- Add user authentication and registration
- Implement real course content with video or quizzes
- Connect to a back-end to manage courses and user data
- Translate site into English for multilingual support
- Add animations and accessibility improvements

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


---

Let me know when you'd like me to save this as a downloadable file, or if you'd like the same text formatted as a PDF or Word doc instead.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
▶️ How to View or Run the Website:

**Option 1: View in Browser (Basic Use)**
1. Download and extract the ZIP file
2. Open `index.html` in any modern web browser
3. Use navigation to browse through the pages

**Option 2: Enable PWA Functionality (Recommended)**
To test the offline capabilities:
1. Run a local server using a tool like `npx serve` or Live Server extension in VS Code
2. Open `http://localhost:5000` or similar
3. Allow installation prompt if shown
4. Test offline access by disconnecting and navigating to previously visited pages

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
⚠️ Requirements & Notes:

- A modern browser (Google Chrome preferred for PWA features)
- Internet access to load Google Fonts (Cairo)
- Local server setup if you want to test full PWA support
- No database or backend is connected — this is a **front-end only** project

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📬 Attribution & Notes:

This project was developed by **Moath Al Morisi** as a **course project** to demonstrate the ability to build a structured, educational, Arabic-language website using core front-end technologies.

While static in nature, the website architecture demonstrates:
- Clean and professional layout
- Multi-page navigation
- Accessible content design
- Integration of modern web capabilities (PWA)

It can serve as a foundation for future dynamic development (e.g., adding a real login system, back-end database support, or interactive course enrollment features).

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📌 Future Improvements (Suggested Enhancements):

- Add user authentication and registration
- Implement real course content with video or quizzes
- Connect to a back-end to manage courses and user data
- Translate site into English for multilingual support
- Add animations and accessibility improvements

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

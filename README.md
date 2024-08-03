# PRODIGY_TrackCode_01
This is a website landing page created for my internship @prodigy internship
Prodigy Internship Landing Page
Welcome to the Prodigy Internship landing page project! This repository contains the code for a landing page for a furniture and design company, designed as part of an internship project. The website is built using HTML, CSS, and JavaScript, and features a responsive design with a dynamic navigation bar.

Project Overview
This landing page is designed to showcase the company's services, portfolio, and provide an engaging user experience. The key components include:

Hero Section: An eye-catching introduction with a call-to-action button.
About Us: Information about the company and its mission.
Services: Overview of services offered.
Portfolio: A gallery of featured projects.
Testimonials: Customer feedback and reviews.
Contact Us: Contact form and company information.
Footer: Additional links and copyright information.
Features
Responsive Design: The layout adjusts for different screen sizes.
Dynamic Navigation Bar: Uses JavaScript to enhance user experience.
Interactive Elements: Hover effects, smooth scrolling, and more.
Getting Started
To view or edit the landing page locally, follow these steps:

Clone the Repository

bash
Copy code
git clone https://github.com/ochanyacodes/prodigy-internship-landing-page.git
Navigate to the Project Directory

bash
Copy code
cd prodigy-internship-landing-page
Open the index.html File

You can open the index.html file in your web browser to view the landing page. You can also use a local development server for a better experience (e.g., Live Server extension in VS Code).

Project Structure
index.html: The main HTML file for the landing page.
styles.css: The CSS file containing the styles for the website.
script.js: The JavaScript file for the dynamic navigation bar.
images/: Directory containing images used on the website.
JavaScript for Navbar
The navigation bar's functionality is handled by script.js. The JavaScript file includes:

Toggle Menu: Functionality to show and hide the mobile navigation menu.
Smooth Scrolling: JavaScript code to enable smooth scrolling to sections.
Example Code (script.js):

javascript
Copy code
// Toggle mobile menu
const menuButton = document.querySelector('.menu-button');
const navMenu = document.querySelector('nav ul');

menuButton.addEventListener('click', () => {
    navMenu.classList.toggle('active');
});
Dependencies
This project does not require any external dependencies or libraries. It uses vanilla HTML, CSS, and JavaScript.

Customization
Feel free to modify the styles, content, and functionality according to your needs. You can adjust the colors, fonts, and layout in styles.css, and enhance or change the behavior of the navigation bar in script.js.

Contributing
If you have any suggestions or improvements, please feel free to contribute! You can open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Contact
For any questions or feedback, you can reach out to me via email.
(amanyipepe@gmail.com)


#  Priyanka Patil Portfolio
A modern and responsive personal portfolio website built using **HTML, CSS, and JavaScript**.
This project showcases my skills, projects, certifications, and contact details in a clean and professional design.

##  Features
*  Responsive Design (Mobile Friendly)
*  Modern UI with Glassmorphism Effects
*  Smooth Navigation Menu (Toggle for mobile)
*  Projects Showcase Section
*  Certifications Section
*  Contact Information Footer

##  Technologies Used
* HTML5
* CSS3
* JavaScript
* Boxicons (for icons)

##  Functionality
###  Mobile Menu Toggle

The navigation menu is interactive and works on smaller screens using JavaScript:

```javascript
const menu = document.querySelector("#menu");
const nav = document.querySelector(".links");

menu.onclick = () => {
    menu.classList.toggle("bx-x");
    nav.classList.toggle("active");
};
```

✔ Toggles menu icon animation
✔ Shows/hides navigation links on mobile

##  Project Structure
portfolio/
│
├── index.html
├── style.css
├── script.js
├── images/
│   └── My photo.jpeg

##  Sections Included
* Home
* About
* Skills
* Projects
* Certifications
* Contact / Footer

##  Future Improvements
* Add project live demo links
* Add animations (scroll effects)
* Improve accessibility
* Add dark/light mode toggle

##  Contact
*  Pune, India
*  [patilpriyanka0857@gmail.com](mailto:patilpriyanka0857@gmail.com)
*  +91 9623080757

##  Acknowledgements
* Boxicons for icons
* Inspiration from modern developer portfolios

##  Note
This portfolio is created as part of my learning journey and will be continuously improved.
*Thank you for visiting my portfolio!*

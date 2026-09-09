Creative Portfolio Website

Overview
This project is a four-page personal portfolio website created for an aspiring Software Engineer. It showcases my background, technical skills, projects, and provides a contact form for potential clients or employers.

The website was developed using HTML5 and CSS3, with a focus on semantic structure, accessibility, responsive design, and professional presentation.

Issues Found
The starter code contained several HTML and CSS errors and missing requirements. Major issues included:

Generic <div> elements instead of semantic HTML5 elements.
Missing navigation across the pages.
Missing descriptive alt text for images.
Missing skills/data table on the About page.
Missing third project.
Incomplete contact form labels and controls.
Incorrect email input type.
Missing HTML5 form validation.
Missing navigation, table, and form styling.
Poor colour contrast and alignment.
Limited CSS selectors and missing interactive states.
Missing responsive design.
Fixes Implemented
The HTML was reorganised using semantic elements including <header>, <nav>, <main>, <section>, <article>, and <footer>. A consistent navigation menu was added across all four pages.

Images were provided with descriptive alternative text. A structured skills table was added to the About page, and a third project was added to the Projects page.

The contact form was completed with labelled controls, text, email and telephone inputs, a project-type dropdown, radio buttons, a textarea, and HTML5 validation attributes.

The CSS was reorganised and expanded to include responsive layouts, Flexbox/Grid, navigation, table and form styling, improved typography, colour contrast, spacing, hover states, and keyboard focus states.

HTML Structure and Semantics
Each page follows a consistent structure:

Header → Navigation → Main Content → Footer

Semantic sections and articles are used to organise related content and improve document structure, accessibility, and maintainability.

CSS Styling Approach

The stylesheet uses element, class, ID, descendant, attribute, and pseudo-class selectors. Flexbox and CSS Grid are used for layout. The CSS box model is demonstrated through margins, padding, borders, and sizing. Media queries provide responsive layouts for smaller screens.

Accessibility Improvements

Accessibility improvements include:

Descriptive image alt text.
Labels associated with form controls.
Semantic HTML5 elements.
Keyboard-visible focus states.
Improved colour contrast.
Descriptive page titles and metadata.
Responsive layouts.
Accessible navigation with the current page identified using aria-current.

How to View

Clone the repository or download the project.
Open the portfolio-website folder.
Open index.html in a web browser.
Use the navigation menu to access the About, Projects, and Contact pages.
No server or additional software is required.

Screenshots

Screenshots demonstrating the completed website are available in the screenshots/ folder, including:

Homepage  - portfolio-website/screenshots/screenshot1.png

About page and styled skills table - portfolio-website/screenshots/screenshot2.png

Projects page - portfolio-website/screenshots/screenshot3.png

Contact page and HTML form - portfolio-website/screenshots/screenshot4.png

Navigation hover state - portfolio-website/screenshots/NavigationHover.png

Form before improvements - portfolio-website/screenshots/BeforeForm.png

Form after improvements - portfolio-website/screenshots/AfterForm.png

The before/after screenshots demonstrate the improvements made to the contact form.

Skills table - portfolio-website/screenshots/SkillsTable.png

Reflection
The main challenge was identifying the errors and missing requirements in the starter code while ensuring that the final website remained accessible, responsive, and consistent. I approached the debugging process systematically by reviewing each page against the project requirements, testing the HTML structure and form controls, and refining the CSS as issues were identified.

This project strengthened my understanding of semantic HTML, CSS layouts, responsive design, form accessibility, and the importance of testing and validating code before submission.
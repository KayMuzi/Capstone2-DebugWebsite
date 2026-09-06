# Creative Portfolio Website

## Overview

This project is a four-page personal portfolio website created for an aspiring software engineer. The website showcases my background, technical skills, projects and provides a contact form for potential clients or employers to get in touch.

The website was developed using **HTML5 and CSS3 only**, with a focus on semantic structure, accessibility, responsive design and professional presentation.

## Issues Found

The starter code contained several HTML and CSS errors and missing features. Major issues included:

* Generic `<div>` elements were used instead of semantic HTML elements.
* Navigation was missing from all pages.
* Images did not have descriptive `alt` text.
* The About page was missing a data table.
* The Projects page was missing a third project.
* The contact form had missing labels and insufficient input types.
* Form validation was missing.
* The email field used the incorrect input type.
* CSS navigation and table styling were missing.
* The original design had colour contrast and alignment issues.
* The CSS had limited selector types and no interactive pseudo-classes.
* Responsive styling was missing.

## Fixes Implemented

The HTML was reorganised using semantic elements including `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` and `<footer>`. A consistent four-link navigation menu was added to all four pages.

Five images were included with descriptive alternative text. A structured skills table was added to the About page, and a third project was added to the Projects page.

The contact form was redesigned with labels, text and email fields, a project-type dropdown, radio buttons and a textarea. HTML5 validation attributes were added to improve data collection and accessibility.

The CSS was reorganised and expanded with responsive layouts, navigation styling, table styling, form styling, hover and focus states, improved colours, typography and spacing.

## HTML Structure

Each page follows a consistent semantic structure:

**Header → Navigation → Main Content → Footer**

Sections and articles are used to organise related content without unnecessary `<div>` elements.

## CSS Approach

The stylesheet uses element, class, ID, descendant, attribute and pseudo-class selectors. Flexbox and Grid are used for layout, while margins, padding and borders provide consistent spacing and visual hierarchy. Hover and focus effects improve interactivity and accessibility.

## Accessibility

Accessibility improvements include:

* Descriptive image `alt` text.
* Labels associated with all form controls.
* Semantic HTML elements.
* Keyboard-visible focus states.
* Accessible colour contrast.
* Descriptive page titles.
* Responsive layouts for different screen sizes.
* Accessible navigation with the current page identified.

## How to View

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Use the navigation menu to visit the About, Projects and Contact pages.

No server or additional software is required.

## Screenshots

Screenshots demonstrating the completed website are stored in the `screenshots/` folder.

They include:

* Homepage
* About page
* Projects page
* Contact page
* Completed contact form
* Styled skills table
* Navigation and hover state

## Reflection

The main challenge was identifying which parts of the starter code were incomplete and replacing the generic structure with meaningful semantic HTML. I was also contemplating what the actual outcome is supposed to be.  I also had to improve accessibility while keeping the design simple. I solved these issues by working through the requirements systematically, testing each page and organising the CSS into clear sections. The project helped me better understand semantic HTML, responsive CSS, form accessibility and the importance of testing before submission.


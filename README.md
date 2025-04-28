# Frontend Mentor - Four Card Feature Section Solution

This is my solution to the [Four Card Feature Section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### The Challenge

The challenge was to build a responsive feature section with four cards, matching the provided designs for mobile (375px), tablet, and desktop (1440px) layouts. The component includes a header, four cards with icons, titles, and descriptions, styled to closely resemble the design files. The page should be accessible, use semantic HTML, and adapt to different screen sizes using modern layout techniques like CSS Grid and Flexbox.

### Screenshot

![Four Card Feature Section Screenshot](./design/desktop-preview.jpg)

### Links

- **Live Site URL**: [Add your live site URL here, e.g., https://yourusername.github.io/four-card-feature-section]
- **Solution URL**: [Add your GitHub repo URL here, e.g., https://github.com/yourusername/four-card-feature-section]

## My Process

### Built With

- Semantic HTML5 markup (e.g., `<header>`, `<section>`, `<article>`, `<footer>`)
- CSS custom properties (for colors and spacing)
- CSS Grid for the card layout
- Flexbox for card content and centering
- Media queries for responsive design
- Google Fonts: Poppins (weights 200, 400, 600)

### What I Learned

This project helped me enhance several key skills:

- **Responsive Design with CSS Grid**: I used CSS Grid to create a complex 2x3 layout for desktop, adjusting to a 2-column grid for tablet and a single-column stack for mobile. For example:
  ```css
  .cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, auto);
    gap: 32px;
  }
  ```
- **Typography Precision**: I implemented precise typography styles using the Poppins font with specific weights, sizes, and line heights as per the style guide (e.g., 36px for the header, 20px for card titles).
- **Accessibility**: I ensured the component was accessible by using semantic HTML, providing alt text for icons, and maintaining sufficient color contrast (e.g., `#4D4F62` on `#FFFFFF` for text).
- **Spacing Consistency**: I followed the design’s spacing system (e.g., 32px for card padding, 24px for gaps on smaller screens) to achieve a pixel-perfect layout.

### Useful Resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - A valuable reference for CSS Grid and semantic HTML.
- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helped me understand CSS Grid for responsive layouts.
- [Google Fonts](https://fonts.google.com/) - Used to import the Poppins font.
- [Frontend Mentor Style Guide](#) - Provided precise colors, typography, and spacing values.

## Author

- Name: [Your Name Here]
- Frontend Mentor: [@YourUsername](https://www.frontendmentor.io/profile/YourUsername)
- GitHub: [@YourUsername](https://github.com/YourUsername)
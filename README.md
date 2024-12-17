# Frontend Mentor - Bento Grid Solution

This is a solution to the **Bento Grid** challenge on [Frontend Mentor](https://www.frontendmentor.io). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
![Design preview for the Bento grid coding challenge](./preview.jpg)

## Table of Contents
- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

### The Challenge

Your users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- Experience a responsive grid layout where the two components in the left column on desktop move to the bottom on mobile

### Screenshot

Desktop:
[Screenshot-Desktop](https://github.com/user-attachments/assets/bc3f7772-da3a-4df0-974e-6669ea54d040)

Tablet:
[Screenshot-Tablet](https://github.com/user-attachments/assets/2ffc7575-f302-4fca-8ea2-59d782296ce7)

Phone:
[Screenshot-Mobile](https://github.com/user-attachments/assets/3e1ac316-db95-403a-8caf-c75820cccf47)

### Links

- Live Site URL: [bentogrids.netlify.app](https://bentogrids.netlify.app/)
- Solution URL: [GitHub Repository](https://github.com/AbdulShaikz/Bento-Grid-Main)

---

## My Process

### Built With

- Semantic HTML5 markup
- CSS Grid and Flexbox
- Mobile-first workflow
- [Netlify](https://www.netlify.com) - for live deployment

### What I Learned

Working on this project allowed me to improve my understanding of CSS Grid and responsive design. A key takeaway was efficiently repositioning grid elements based on screen sizes. Here's an example of CSS Grid placement:

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
}

@media (max-width: 768px) {
  .grid-container {
    grid-template-columns: 1fr;
  }
  .left-column {
    grid-row: 3;
  }
}
```

This snippet showcases how the left column moves to the bottom on smaller screens.

### Continued Development

Going forward, I want to:

- Enhance the interactivity using JavaScript for dynamic behavior
- Experiment with Tailwind CSS to simplify styling further
- Improve accessibility features using ARIA roles and proper semantic tags

### Useful Resources

- [CSS Grid Layout](https://css-tricks.com/snippets/css/complete-guide-grid/) - A complete guide to understanding CSS Grid.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - For detailed CSS documentation and examples.

---

## Author

- GitHub - [AbdulShaikz](https://github.com/AbdulShaikz)
- Live Site - [Bento Grid](https://bentogrids.netlify.app/)

---

## Acknowledgments

Special thanks to [Frontend Mentor](https://www.frontendmentor.io) for providing this challenge to practice and refine front-end development skills.

---

Enjoy building! 🚀

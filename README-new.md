# Frontend Mentor - Blog preview card solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- View the card with proper responsive design on mobile and desktop

### Screenshot

![Blog Preview Card Screenshot](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/yourusername/blog-preview-card)
- Live Site URL: [Live Demo](https://yourusername.github.io/blog-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox for layout
- CSS transitions and transforms for interactivity
- Mobile-first workflow
- Google Fonts (Figtree)

### What I learned

Through this project, I strengthened my understanding of CSS Flexbox for centering content and creating responsive layouts. I also learned how to create engaging hover effects using CSS transitions.

Here's a hover effect I'm particularly proud of:

```css
.main-container:hover {
  box-shadow: 8px 8px 0px 0px hsl(0, 0%, 7%);
  transform: translateY(-4px);
}
```

This creates a lifting effect where the card appears to float up when you hover over it, with a shadow appearing beneath it for depth.

I also implemented interactive states for the button and title:

```css
button:hover {
  background-color: hsl(0, 0%, 7%);
  color: hsl(47, 88%, 63%);
}

.writtings-container h1:hover {
  color: hsl(47, 88%, 63%);
}
```

### Continued development

In future projects, I want to focus on:

- Advanced CSS animations and keyframes
- Adding JavaScript for more interactive features
- Improving accessibility (ARIA labels, keyboard navigation)
- Learning CSS Grid for more complex layouts
- Working with CSS preprocessors like SASS

## Author

- Frontend Mentor - [@FrankAntwi](https://www.frontendmentor.io/profile/FrankAntwi)
- GitHub - [@FrankAntwi](https://github.com/FrankAntwi)

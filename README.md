# Frontend Mentor - Advice generator app solution

This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Generate a new piece of advice by clicking the dice icon

### Screenshot

![Desktop](./design/desktop-design.jpg)
![Mobile](./design/mobile-design.jpg)

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Github Repo](https://github.com/ejaay-dev/advice-generator)
- Live Site URL: [Site Demo](https://advice-generator-psi-red.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Remix](https://remix.run/) - React framework
- [Tailwind](https://tailwindcss.com/) - For styles

### What I learned

I learned how to create a radial gradient

```css
.gradient-shadow {
  transition: box-shadow 0.3s ease;
}

.gradient-shadow::before {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: 50%;
  background: radial-gradient(
    circle,
    hsla(150, 100%, 66%, 0.6) 30%,
    hsla(150, 100%, 66%, 0) 100%
  );
  z-index: -1;
  transition: background 0.3s ease;
}

.gradient-shadow:hover {
  box-shadow: 0 0 20px 10px hsla(150, 100%, 66%, 0.6); /* Neon-green glow */
}
```

## Author

- LinkedIn - [@errolignacio](https://www.linkedin.com/in/errolignacio)

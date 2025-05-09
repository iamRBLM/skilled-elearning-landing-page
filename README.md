# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop Preview](/images/desktop-preview.png)

![Tablet Preview](/images/tablet-preview.png)

![Mobile Preview](/images/mobile-preview.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS Variables
- CSS Grid
- CSS Flexbox

### What I learned

I learned to make the course cards responsive by using CSS Grid with the `grid-template-columns` property, using the `repeat()` and `minmax()` functions for flexible layout control.

```css
.courses .container.grid {
  grid-template-columns: repeat(auto-fit, minmax(352px, 1fr));
  gap: 32px;
}

.courses .courses-card {
  position: relative;
  width: 100%;
  height: 322px;
  padding: 64px 32px 40px;
  border-radius: 15px;
  box-shadow: 0 25px 50px rgba(6, 22, 141, 0.0442);
}
```

I also learned how to write clean HTML and CSS code, using CSS utilities classes and CSS Variables (custom properties), for different styles, such as:

- Background color and Text color.
- Font sizes and Text styles.
- CSS Grid and CSS Flexbox.
- Padding and Margin properties.

### Continued development

I will keep improving my HTML and CSS skills and learning new tricks and techniques.
I will be focusing specifically on mastering CSS Flexbox and Grid techniques and responsive web design.

## Author

- Frontend Mentor - [@rosenblumitamar](https://www.frontendmentor.io/profile/rosenblumitamar)
- Twitter - [@rosenblumitamar](https://x.com/ItamarRosenblum)

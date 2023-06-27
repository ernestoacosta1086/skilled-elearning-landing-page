# Skilled e-learning landing page solution

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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This repository contains a webpage with a simple and responsive design. The page is designed in a clean and structured manner, automatically adapting to different screen sizes and devices. This ensures that the content is displayed correctly and easily accessible on both desktop computers and mobile devices. The simplicity of the design allows for easy navigation and understanding of the content, providing a seamless user experience.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./preview.jpg)

### Links

- [GitHub repo](https://jocular-churros-08ff76.netlify.app)
- [Live Site URL](https://jocular-churros-08ff76.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<section class="section-hero1">
  <div>
    <h1>
      Maximize skill, <br />
      minimize budget
    </h1>
    <p>
      Our modern courses across a range of in-demand skills will give you the
      knowledge you need to live the life you want.
    </p>
    <button class="button-size">Get Started</button>
  </div>
  <div>
    <img src="./assets/image-hero-desktop.png" alt="Hero image" />
  </div>
</section>
```

```css
.section-cards {
  display: grid;
  grid-template: 1fr 1fr/1fr 1fr 1fr;
  column-gap: 2rem;
  row-gap: 4rem;
  margin: 4rem 0 8rem 0;
}
.card-div {
  border-radius: 0.6rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 2rem;
  border: none;
  color: var(--color-dark-blue);
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.09);
  background-color: white;
}
```

### Continued development

I would like to emphasize my interest in delving deeper into the concepts of CSS and responsive screens in future projects. I recognize the importance of mastering flexible and adaptable design techniques to ensure an optimal user experience across different devices and screen sizes. I am excited to learn how to use media queries, relative units of measurement, and other CSS tools to create designs that adjust and look great on all devices.

### Useful resources

- [mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS) - This documentation is too good and provides several examples to understand all the concepts in simple ways.
- [Udemy](https://www.udemy.com) - This is a very rich source of knowledge where good teachers provide the best courses.

## Author

- Website - [Ernesto Acosta](https://www.frontendmentor.io/profile/ernestoacosta1086)
- Frontend Mentor - [@ernestoacosta1086](https://www.frontendmentor.io/profile/ernestoacosta1086)
- Linkedin [Ernesto Acosta](https://www.linkedin.com/in/ernesto-a-labrada/)

## Acknowledgments

I highly recommend this Udemy course by Instructor Colt Steele, it is very well explained and covers most of the more complex concepts within CSS. Mainly the concepts of positioning with Flex, Grid and responsive layouts which I initially didn't understand very well until I reviewed the course. https://www.udemy.com/course/html-and-css-bootcamp/

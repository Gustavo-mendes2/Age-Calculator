# Frontend Mentor - Age calculator app solution

This is a solution to the [Age calculator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/age-calculator-app-dF9DFFpj-Q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

An age calculator that shows how many years, months and days the user lived.

### The challenge

Users should be able to:

- View an age in years, months, and days after submitting a valid date through the form
- Receive validation errors if:
  - Any field is empty when the form is submitted
  - The day number is not between 1-31
  - The month number is not between 1-12
  - The year is in the future
  - The date is invalid e.g. 31/04/1991 (there are 30 days in April)
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: See the age numbers animate to their final number when the form is submitted

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [GitHub pages](https://gustavo-mendes2.github.io/age-calculator/)

## My process

I started to build from the top to the bottom, i created all the HTML and after planning all the structure, i created the CSS classes and setted all properties for the elements after all stylization and making the page responsive, i did the javascript code where i picked all elements i would need to calculate the age and interact with in this process, then i created the calculate age function wich verify if some value in the input fields are valids, if they don't this function highlights the input fields and shows what'a wrong with the value but if the values are valid the animation of rendering the age start and stops when reach the age.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Javascript

### What I learned

In this project i learned especially how to work with dates and how the rule of signs works in math, in the code below we can se an example

```js
11 + (actualDate.getMonth() + 1 - birthMonth.value);
```

in this part i want to subtract a negative value from 11 but to do this i need to add the value to 11 because if a negative value inside the parenthesis is subtracted from another, based on the rule of signs the value will turn into a positive number then it will be added to 11.

### Continued development

In my future projects i will start using another aproaches to the responsive part of my project, the responsive part of this project actually works but i didn't planned how it would work and just ajusted until satisfy the conditions i needed to conclude the challenge.

## Author

- Frontend Mentor - [@Gustavo Mendes](https://www.frontendmentor.io/profile/Gustavo-mendes2)

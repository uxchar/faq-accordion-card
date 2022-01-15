# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked
- Bonus: Do not use JS for toggle states

### Screenshot

[![Screenshot-2022-01-15-at-14-36-56-Frontend-Mentor-FAQ-Accordion-Card.png](https://i.postimg.cc/fy1tvQWC/Screenshot-2022-01-15-at-14-36-56-Frontend-Mentor-FAQ-Accordion-Card.png)](https://postimg.cc/1Vc39TqV)

### Links

- Live Site URL: https://uxchar.github.io/faq-accordion-card/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
<input type="checkbox" id="faq-arrow-toggle-2" />
            <label class="arrow" for="faq-arrow-toggle-2">
              <img class="select-arrow" src="images/icon-arrow-down.svg" />
            </label>

            <p class="answer">
              No more than 2GB. All files in your account must fit your allotted
              storage space.
            </p>
```
```js
input[type="checkbox"]:checked ~ .answer {
  display: flex;
  text-align: left;
  font-size: 1rem;
  font-weight: 400;
  color: var(--clr-txt-very-dark-grayish-blue);
  margin: -10px auto 10px auto;
  max-height: auto;
  transition: 0.4s ease;
}
```



### Useful resources

- [CSS Tricks Checkbox Hack](https://css-tricks.com/the-checkbox-hack/) - This helped me with toggling the FAQ card with the use of JavaScript.
- [CSS Tricks Absolute Positioning](https://www.example.com) - This is an article that helped me better understanding absolute positioning for elements I needed outside of the main FAQ card div.



## Author

- Frontend Mentor - [@uxchar](https://www.frontendmentor.io/profile/uxchar)




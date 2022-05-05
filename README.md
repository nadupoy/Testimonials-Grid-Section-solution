# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](https://raw.githubusercontent.com/nadupoy/Testimonials-Grid-Section-solution/main/design/Mobile%20-%20375px.png)

![](https://raw.githubusercontent.com/nadupoy/Testimonials-Grid-Section-solution/main/design/Tablet%20-%20768px.png)

![](https://raw.githubusercontent.com/nadupoy/Testimonials-Grid-Section-solution/main/design/Laptop%20-1440px.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/testimonials-grid-section-solution-using-html-and-css-B1eyLLVb8c)
- Live Site URL: [Netlify](https://testimonials-grid-section-nadupoy.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- Visual Studio Code


### What I learned
How to arrange elements using CSS Grid:
```css
main {
        display: grid;
        row-gap: 20px;
        column-gap: 30px;
        justify-content: space-between;
    }
```

```css
#jonathan {
        background-color: hsl(217, 19%, 35%);
        grid-column-start: 3;
        grid-column-end: 4;
        grid-row-start: 1;
        grid-row-end: 2;
    }
```

Different ways of targeting HTML elements using CSS Selectors:
```html
<section id="jonathan">
                <header>
                    <img src="images/image-jonathan.jpg" alt="picture-of-jonathan">
                    <div>
                        <p class="name">Jonathan Walters</p>
                        <p class="status">Verified Graduate</p>
                    </div>
                </header>
                <article>
                    <p class="summary-testimonial">
                        The team was very supportive and kept me motivated.
                    </p>
                    <p class="testimonial">
                        "I started as a total newbie with virtually no coding skills. I now work as a mobile engineer for a big company. This was one of the best investments I've made in myself."
                    </p>
                </article>
            </section>
```
```css
#daniel .name, #jonathan .name, #patrick .name {
        color: hsl(0, 0%, 100%);
    }
    
#daniel .status, #jonathan .status, #patrick .status {
        color: hsla(0, 0%, 100%, 0.5);
    }

#daniel .summary-testimonial, #jonathan .summary-testimonial, #patrick .summary-testimonial {
        color: hsl(0, 0%, 100%);
    }

#daniel .summary-testimonial {
        width: 500px;
    }
```


### Continued development

I intend to gain a greater understanding of CSS Selectors so as to avoid the unneccessary use of HTML attributes to target elements for styling.



### Useful resources

- [W3 Schools](https://www.w3schools.com/) - This helped me understand CSS Grid and CSS Selectors.



## Author

- LinkedIn - [Grace Sampao](https://www.linkedin.com/in/grace-sampao-49a3129b/)
- Frontend Mentor - [@nadupoy](https://www.frontendmentor.io/profile/nadupoy)





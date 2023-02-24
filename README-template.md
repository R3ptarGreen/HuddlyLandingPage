# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Desktop](./images/Screenshot1-02-24%20at%2017-06-41%20Huddle%20landing%20page%20with%20single%20introductory%20section.png)
![Mobile](./images/Screenshot%202023-02-24%20at%2017-07-41%20Huddle%20landing%20page%20with%20single%20introductory%20section.png)

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This challenge allowed me to improve my design and make responsive designs more efficiently.

```css
@media  (max-width: 1050px){
    .container, .bg_desktop{
        width: 50rem;
        height: 30rem;
     }
     .ilust_img{
        width: 22em;
        margin-left: 0; 
    }

}
@media  (max-width: 800px){
    .container, .bg_desktop{
        width: 40rem;
        height: 30rem;
    }
    .logo_header{
        width: 8em;
    }
    .ilust_img{
        width: 18em;
        margin-top: 8rem;
        margin-left: 0; 
    }
    .info{
        padding-left: 1rem;
    }
    .info h1{
        width: 22rem;
        padding-top: 3rem;
        font-size: 2em;
        text-align: center;
    }
    .info p{
        text-align: center;
    }
    .button{
        width: 24rem;
    }

}
@media (max-width: 640px) {
    .bg_mobile{
        visibility: visible;
        position: absolute;
        width: 22rem;
        z-index: -1;
    }
    .bg_desktop{
        visibility: hidden;
    }    
    .container{
        margin: auto;
        margin-top: 4vh;
        width: 22rem;
        height: 50rem;
        border: 1px solid ;
        display: grid;
        grid-template-rows: 48% 40% 12%;
        grid-template-areas: "header"
                             "info"
                             "profile_link";
    }
    .header, .info, .profile_link{
        width: 22rem;
    }
    .logo_header{
        width: 8em;
    }
    .ilust_img{
        width: 20em;
        margin-top: 4rem;
        margin-left: 0; 
    }
    .info{
        padding: 1.5rem;
        padding-top: 0;
    }
    .info h1{
        padding-top: 1rem;
        font-size: 1.5em;
        text-align: center;
    }
    button{
        height: 2.5rem;
        width: 12rem;
    }
    .profile_link{
        padding: 0;
    }
    .profile_link{
        justify-content: center;
        align-items: center;
    }

}
```

### Continued development

I would like continued development with grid and flexbox display and make more quickly codes

### Useful resources

- [cdnj](https://cdnjs.com/libraries/font-awesome) - Great place to use the font awesome page [Font awesome](https://fontawesome.com/search)

## Author

- Frontend Mentor - [@R3ptarGreen](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

I'm studying by myself in FreeCodeCamp and I'm improving my skills with Frontend Mentor


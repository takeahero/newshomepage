# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)



### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![desktop version screenshot](https://github.com/cadeMeuCode/newshomepage/blob/main/screenshots/mySolution--desktop.png?raw=true "Desktop")  
![mobile version screenshot](https://github.com/cadeMeuCode/newshomepage/blob/main/screenshots/mySolution--mobile.png?raw=true "Mobile")  
![mobile menu screenshot](https://github.com/cadeMeuCode/newshomepage/blob/main/screenshots/mySolution__menu--mobile.png?raw=true "Mobile menu")  



### Links

- Repo URL: [GitHub Repository](https://github.com/cadeMeuCode/newshomepage)
- Live Site URL: [Deploy](https://newshomepage-7vgvjj267-cademeucode.vercel.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

This is my first time using grid. I'm learn how positioning the grid, with the `grid-template-areas`  

```
    main {
        display: grid;
        grid-template-areas: 
        "main"
        "new"
        "popular";
        grid-template-columns: 33.33% 33.33% 33.33%;
        grid-template-rows: 33.33% 33.33% 33.33%;
    }

    .section__main {
        grid-area: main;
        grid-row: 1/1;
        grid-column: 1/3;
        margin-right: 1rem;
    }

    .section__new {
        grid-area: new;
        grid-row: 1/2;
        grid-column: 3/4;
        margin: 0;
        margin-left: 1rem;
    }

    .section__popular {
        grid-area: popular;
        grid-row: 2/3;
        grid-column: 1/4;
    }

```

### Continued development

The next step is build the another pages.



# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

hi welcome everyone! this is my first challeng on the front end mentor website. i'm not actually sure about some flex properties such as justify-content, align-item, align-content. also i don't know a thing about media query, didn't learn it yet. forgive me if you saw so many unnecessery things inside of it >_<
  
### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

Web view:
![](./screenshot/result%20summary%20component%20solution.png)

Mobile view - Responsive:
![](./screenshot/result%20summary%20component%20solution%20-%20mobile.png)

### Links

- Solution URL: [https://github.com/syarief02/result-summary-component](https://github.com/syarief02/result-summary-component)
- Live Site URL: [https://syarief02.github.io/result-summary-component/](https://syarief02.github.io/result-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS built-in properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

- Semantic element and how to insert icon from external source
```html
          <div class=sumcon id="r1">
            <div class=item id="reaction"> <img src="./assets/images/icon-reaction.svg" alt=""> Reaction</div>
            <div class="summ"> <span>80</span> / 100</div>
          </div>
```

- how to use viewport height, flexbox, and center content
```CSS
body {
    font-size: 18px;
    min-height: 100vh;
    display: flex;
    place-items: center;
    margin: 0;
    background-color: rgb(253, 251, 248);
    align-content: center;
    justify-content: center;
    justify-items: center;
    align-items: center;
    flex-wrap: wrap;
    flex-direction: column;
}
```

- How to use external font
```CSS
@font-face {
    font-family: "Hanken Grotesk";
    src: url(assets/fonts/HankenGrotesk-VariableFont_wght.ttf);
}

main {
    font-family: 'Hanken Grotesk';
    font-weight: 1000;
    font-size: 18px;
}
```

- How to use Linear Gradient
```CSS
#sec1 {
    /* background-color: #312ceb; */

    background-image: linear-gradient(180deg, hsl(252, 100%, 67%), hsl(241, 81%, 54%));
    color: hsl(241, 100%, 89%);
    text-align: center;
    border-radius: 2em;
    transition: all 0.5s;
}
```

- learned how to use media query to adjust the width for mobile view
```CSS
@media only screen and (max-width: 800px) {

    div.mainsec {

        flex-direction: row;
        align-items: center;
        border-radius: 2em;
        box-sizing: border-box;
        box-shadow: 5px 15px 30px 12px #e8edfe;
        margin: 0;
        justify-self: center;
        align-content: center;
        flex-grow: 1;
        width: 100%;
        max-width: calc(737/510*375px);
    }
```

- learned opacity
```CSS
#r1 {
    background-color: hsla(0, 100%, 67%, 0.05);
}
```

- learned how to adjust position slightly using Transform: Translate properties
```CSS
img {
    transform: translateY(0.25em);
}
```

- I also learned about specificity in css element selector.

I learned a lot since this is my first project by doing the front end mentor challenges.

### Continued development

For now my focus is to continue learning more about the web development. there's so much more i've never heard about. some people suggested bootstrap while i was doing this challenge for mobile view.

### Useful resources

- [StackOverflow](https://stackoverflow.com/questions/52941346/css-height-calc100vh-vs-height-100vh) - This helped me fora lot of things such as understanding some properties i don't know about. because there's a lot of people with similar problem and people who solved the problem with example. I really liked this site and will use it going forward.

- [Udemy](https://www.udemy.com/course/the-web-developer-bootcamp/) - This is an amazing website which i can find courses to learn everything about tech. I'd recommend it to anyone still learning web development.


## Author

- Website - [Syarief Azman](https://github.com/syarief02)
- Frontend Mentor - [@syarief02](https://www.frontendmentor.io/profile/syarief02)
- Twitter - [@SyariefAzman](https://www.twitter.com/SyariefAzman)

## Acknowledgments

Colt Steele - I learned web development bootcamp from Udemy by Colt Steele. the course is complete with everything we needed to be a full stack web dev. I would really recommend it to anyone else.


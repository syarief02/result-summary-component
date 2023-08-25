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


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**

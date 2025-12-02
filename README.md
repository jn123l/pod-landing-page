# Frontend Mentor - Pod request access landing page solution

This is a solution to the [Pod request access landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pod-request-access-landing-page-eyTmdkLSG). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements
- Receive an error message when the form is submitted if:
  - The `Email address` field is empty should show "Oops! Please add your email"
  - The email is not formatted correctly should show "Oops! Please check your email"

### Screenshot

![](./project-result.png)

### Links

- Solution URL: [GitHub](https://github.com/jn123l/pod-landing-page/)
- Live Site URL: [Netlify](https://pod-landing-page.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Vanilla JS

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned how to organize my HTML properly and change the order of HTML elements depending on the screen size using Flexbox.
Also I learned how to apply different styles to form elements when the screen resizes. Furthermore I studied
how to check the validity of email inputs using a regular expression.

```js
function resizeWindow(){
    if(!isFormInputCorrect){
        if(window.innerWidth <= 767){
            form.style.border = "none"
            inputEmail.style.border = "0.125rem solid var(--red)"
        }
        else{
            form.style.border = "0.125rem solid var(--red)"
            inputEmail.style.border = "none"
        }
    }
}

window.onresize = resizeWindow
```

## Author

- Website - [Jan Lindner](https://jans-learning-journal.netlify.app/)
- Frontend Mentor - [@jn123l](https://www.frontendmentor.io/profile/jn123l)



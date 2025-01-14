# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![](/images/Screenshot/Galaxy%20S21-1736780184518.jpeg) ![](/images/Screenshot/Galaxy%20S21-1736780218527.jpeg)
![](/images/Screenshot/iPad-1736780190247.jpeg) ![](/images/Screenshot/iPad-1736780225215.jpeg)
![](/images/Screenshot/Nest%20Hub%20Max-1736780354081.jpeg) ![](/images/Screenshot/Nest%20Hub%20Max-1736780364127.jpeg)


### Links

- Solution URL: [Add solution URL here](https://github.com/h3cat3/article-preview-component)
- Live Site URL: [Add live site URL here](https://h3cat3.github.io/article-preview-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Accesibility
- Java Script

### What I learned

Use this section to recap my CSS and HTML and wrote my first Java Script Code.

```js
function openSocialMedia() {
            document.getElementById("myModal").style.display = "flex";
        }

        function closeSocialMedia() {
            document.getElementById("myModal").style.display = "none";
        }

        window.onclick = function(event) { 
            var modal = document.getElementById("myModal"); 
            if (event.target == modal) { 
                modal.style.display = "none"; 
            }
        }
```

### Continued development

I strugle to make the the project react the way I want for big scins, and definitly need to understand better how to use dysplay property.
For sure I have more to learn about JS.

## Author

- Frontend Mentor - [@h3cat3](https://www.frontendmentor.io/profile/h3cat3)


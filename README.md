# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![image](https://user-images.githubusercontent.com/98894266/214221314-4b9a9eb1-b7cf-4b8b-b94e-7d6af884f755.png)
This is what I made.

![image](https://user-images.githubusercontent.com/98894266/214221493-c01ec22d-e9fe-45f3-b461-4e8bb487509f.png)
this is what it was propose as a challenge.
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I start puting the divs in html with class containers and , then I add objects inside the divs, like: texts and images. Then with css I git the divs height and widht and a background color.
```html
<div class="container">
    <img src="images/image-qr-code.png" alt="Qr" class="qr">
    <div class="text">
      <h3 class="title">Improve your front-end skills by building projects</h3>
      <p class="para">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
```
```css
.container{
    width: 18.66rem;
    height: 470px;
    
    margin: 50px auto ;
    background-color: hsl(0, 0%, 100%);
    border-radius: 1em;
    border-style: none;
}
.text{
    width: 230px;
    height: auto;
    margin-top: 5px;
    margin-left: auto;
    margin-right: auto;
}
```


### Built with

- Semantic HTML5 markup
- CSS custom properties
- [Font Style](https://fonts.google.com/specimen/Outfit?preview.text=Improve%20your%20front-end%20skills%20by%20building%20projects%20Scan%20the%20QR%20code%20to%20visit%20Frontend%20Mentor%20and%20take%20your%20coding%20skills%20to%20the%20next%20level&preview.text_type=custom/) 

### What I learned

I learn how to posicionate objets on the screend and how important are the divs to manage and controle objects inside them.


## Author

- Website - [Curriculm vitae](https://jocular-begonia-42093d.netlify.app)
- LinkedIn - [Carlos Alberto Salcedo Rodríguez](https://www.linkedin.com/in/carlos-alberto-salcedo-rodríguez-54837a239/)

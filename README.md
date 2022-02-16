# My first HTML/CSS project : Frontend Mentor's QR code page

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
 Contrary to what I expected, I learned really a lot from doing this challenge. So if you are an absolute beginner like me, I encourage you to give it a try.
## Table of contents

- [Overview](#overview)
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

### What I learned (I'll specify later in the code section) :

- How to link HTML to CSS.
- CSS box model.
- Types of position : static, absolute, relative and fixed.
- One way to center a div.
- How to import : images, colors and font families.
- How to use : classes and IDs.
- How to use chrome to preview a page.
- How to round image courners (HTML).



### Links

- [Solution URL](https://www.frontendmentor.io/solutions/qr-code-page-with-htmlcss-sY8B78cwC) You can find the code in this github repository.
- [Live Site URL](https://qrpage.vercel.app/)

## My process

### Built with

- HTML5.
- CSS.
- Visual studio code.



### Code process :

I knew how to use VS code, Github and a little bit of HMTL ; So I head to learn CSS. 
#### First, **connecting things together** in HTML :

```html
<!-- Inside the head element -->
<!-- Linking the CSS sheet -->
<link rel="stylesheet" href="style.css">

<!-- Importing the image -->
<link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
```


#### Grouping elements in divisions and marking some elements with classes and ids to be able to modify them in CSS stylesheet :

```html
<div class ="Card">
 <div id = "img">
  <img src="images/image-qr-code.png" alt="QR code" width="200" height="200" style ="border-radius: 10px;">
 </div>
 <div class="Card_description">
   <p id="line1">Improve your front-end skills by building projects</p>

   <p id="line2">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
```

#### Importing font family and styling the texts (for example line1 here) :

```html
<!-- Importing the fonts for later -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
  
```
Remember that to reference, we use a dot for classes and a hashtag for id.

```css
@font-face {
    font-family: 'Outfit', sans-serif;
    src: url(https://fonts.google.com/specimen/Outfit);}

#line1 {
    color: hsl(218, 44%, 22%);
    font-size: 17px;
    font-family: 'Outfit';
    font-weight: 700;
    background-color: white;
    padding: 5px;
    text-align: center;}

```





### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

- Twitter - [Anas Rouam](https://twitter.com/rouam_anas)


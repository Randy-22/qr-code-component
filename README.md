# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

This project is a static web page that features a centered card-style component containing a QR code image, a heading, and a short description. The goal is to mimic a modern UI card design commonly seen in web applications and landing pages.

The design is fully responsive and optimized for both mobile and desktop screen sizes. It uses semantic HTML elements and CSS properties such as Flexbox, custom fonts, border-radius, and padding to achieve a visually appealing layout.

### Screenshot

![Mobile Design](/QR-code/designs/mobile%20design.png)
![Desktop Design](/QR-code/designs/desktop%20design.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

This project utilizes modern HTML and CSS3 to build a simple and responsive QR code component. All styling is done using **internal CSS**, with no external stylesheet included.

The HTML structure consists of two main `div` elements: `big-container` and `small-container`. The `big-container` employs `display: flex` to center the small-container both vertically and horizontally within the viewport.

The `small-container` is styled **with a width of 300px for desktop** screens and **250px for mobile**. A responsive breakpoint is set at `375px` to adjust the layout for smaller devices.

This approach ensures a clean, centered layout that adapts well to both mobile and desktop environments using basic, yet modern, layout techniques.

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Flexbox
- Google Fonts
- VS Code (or any text editor)

### What I learned

The first lesson I learned from this project is that Flexbox makes it very easy to center HTML elements both vertically and horizontally. This greatly simplifies layout design compared to older methods like using margins or positioning.

Secondly, I learned that setting `padding: 0;` and `margin: 0;` helps remove inconsistent spacing across different browsers. This allows me to apply padding and margin intentionally, based on the specific needs of my layout.

Lastly, setting `box-sizing: border-box;` makes layout design more intuitive and easier to manage, especially when building responsive user interfaces. It ensures that padding and borders are included within the total width and height of elements, making layout calculations more straightforward.

To see how you can add code snippets, see below:

```css
* {
    margin: 0;
    padding:0;
    box-sizing: border-box;
  }
```

### Continued development

Although this is a simple static project, there are several areas I plan to explore further to enhance my understanding and improve the design:

- Refactor the CSS by moving styles to an external stylesheet for better organization and maintainability.

- Improve responsiveness by adding media queries to adjust the layout more dynamically across various screen sizes.

- Add subtle animations or transitions, such as hover effects on the card, to enhance user experience and interactivity.

- Rebuild the component using CSS Grid as a way to compare layout techniques and deepen my layout skills.

- In the future, I’d also like to recreate this component using a utility-first CSS framework like Tailwind CSS or Bootstrap

### Useful resources

- [CSS flex-box Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This site provides user friendly and a simple way to really grasp the concept of CSS flex box.

## Author

- Website - [Randy Sekyere](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

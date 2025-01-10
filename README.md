# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![qr code fm](https://github.com/user-attachments/assets/8bed5e7a-686c-49a1-80e1-45105fe7d2be)

### Links

- Solution URL: [github](https://github.com/januarmaksum/qr-code-component/)
- Live Site URL: [qr-code-component-fm.vercel.app](https://qr-code-component-fm.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

While working on this project, I learned how to effectively use semantic HTML5 elements and CSS custom properties to create a responsive and visually appealing card component. Here are some key takeaways:

1. **Semantic HTML5 Markup**: Using semantic elements like `<article>`, `<h1>`, and `<p>` helps improve the readability and accessibility of the code.

```html
<article class="card">
  <h1 class="card__title">
    Improve your front-end skills by building projects
  </h1>
  <p class="card__description">
    Scan the QR code to visit Frontend Mentor and 
    take your coding skills to the next level
  </p>
</article>
```

2. **CSS Custom Properties**: Leveraging CSS variables for consistent styling and easy maintenance.
```css
:root {
  --card-bg-color: #fff;
  --card-border-radius: 10px;
  --card-box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.card {
  background-color: var(--card-bg-color);
  border-radius: var(--card-border-radius);
  box-shadow: var(--card-box-shadow);
}
```

### Continued development

Based on this project, I want to continue focusing on the following areas in future projects:

1. **Advanced CSS Techniques**: I aim to deepen my understanding of CSS Flexbox to create more complex and responsive layouts.
2. **Responsive Design**: Further refining my skills in creating designs that work well on a variety of devices and screen sizes.

These areas will help me build more robust and user-friendly web applications.

### Useful resources

- [HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp) - This helped me understand the importance of using semantic elements to improve the structure and accessibility of my web pages. I really liked this pattern and will use it going forward.
- [BEM — is a methodology that helps you to create reusable components](https://getbem.com/naming/) - This is an amazing article which helped me finally understand the BEM methodology. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Januar Maksum](https://januarmaksum.vercel.app/)
- Frontend Mentor - [@januarmaksum](https://www.frontendmentor.io/profile/januarmaksum/)
- Linkedin - [@januarmaksum](https://www.linkedin.com/in/januarmaksum/)

## Acknowledgments

I would like to give credit to Frontend Mentor for providing an excellent platform for learning front-end development through real-world projects. Their challenges have been instrumental in improving my coding skills and understanding of best practices.

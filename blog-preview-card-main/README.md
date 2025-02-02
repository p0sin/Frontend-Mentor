# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Solution](https://github.com/p0sin/Frontend-Mentor/tree/main/blog-preview-card-main)
- Live Site URL: [Site URL](https://p0sin.github.io/Frontend-Mentor/blog-preview-card-main/index.html)

## My process

1. **Outline and Structure**  
   I started by sketching the layout and identifying the main sections (header, content, footer, etc.). This helped me establish a clear blueprint before coding.

2. **Top-to-Bottom Implementation**  
   I built each element starting from the top (header area) down to the bottom (footer or final sections). This step-by-step approach ensured that each part of the layout was correctly positioned and styled.

3. **Responsive Focus**  
   At every stage, I tested and adjusted for various screen sizes. I applied responsive classes (like `md:`) to ensure each element adapted seamlessly to different viewport widths.

4. **Incremental Style Application**  
   As I progressed, I added Tailwind CSS utility classes to control spacing, typography, and colors. Applying these styles incrementally made it easier to maintain a responsive design and prevent layout issues.

5. **Refinement and Final Checks**  
   Finally, I reviewed the entire page design, checking it on multiple devices or using dev tools. Minor tweaks were made to ensure everything remained consistent and responsive.

By working methodically from top to bottom and focusing on responsiveness at each step, I was able to develop a coherent and mobile-friendly interface.

### Built with

- Semantic HTML5 markup
- Tailwind

### What I learned

- **Leveraging utility-first classes for quick layouts**  
  Tailwind made it easy to create the layout with its pre-defined classes for grid, flex, spacing, and sizing. For instance, using `grid h-screen justify-center content-center` helped me center the content without writing additional custom CSS.

- **Scalability and maintainability**  
  Although it may seem like a lot of classes in the HTML, it greatly reduces the need to switch to a separate CSS file. This streamlines my workflow and prevents style duplication.

- **Responsive design with prefix**  
  I learned how to use prefixes like `md:` to adjust the design for different screen sizes. This makes the site responsive without writing manual media queries.

- **Customizing styles with arbitrary values**  
  Using classes such as `rounded-[10px]`, `shadow-[8px_8px_#000]`, and `bg-[#F4D04E]` allowed me to achieve a very specific design without configuring everything in Tailwind’s config file.

- **Managing typography and colors**  
  Through utilities like `font-extrabold`, `text-sm`, and `text-[#6B6B6B]`, I gained a better understanding of how Tailwind provides granular control over typography and colors.

Overall, Tailwind proved to be a versatile tool for both prototyping and fine-tuning styles, offering a more streamlined workflow and an easier-to-maintain codebase.

### Useful resources

- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Tailwind Docs](https://tailwindcss.com/docs/installation/play-cdn)

## Author

- p0sin

## Acknowledgments

I would like to extend my gratitude to the [Frontend Mentor](https://www.frontendmentor.io/) community for providing this challenge and offering valuable insights. Their platform and resources guided me through best practices for responsive design, HTML, and CSS. I also want to thank my peers and mentors who reviewed my code, shared feedback, and helped me refine my approach throughout the project.

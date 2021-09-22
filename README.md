# 01 HTML, CSS, and Git: Code Refactor (Mark Drummond)

## My Task

I started with a working HTML&CSS web app that isn't great for **web accessibility**, which is important for differently-abled people as well as search engines and other machine readers. My task was to refactor the existing code to meet accessibility standards defined in these **acceptance criteria**:

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## My Work

I refactored the code to replace div tags with semantic tags main, header, article, section, figure, aside, and footer. I added the "alt" attribute to the images to describe the images. I added ARIA attributes to describe non-text elements such as the div that has its background picture defined in the CSS file and the heart emoji in the footer.

I uploaded the complete web app to GitHub and made it accessible via GitHub Pages.

## Mock-Up

The following image shows the web application's appearance and functionality. The finished web app looks exactly the same to the eye as the original but is more accessible to differently-abled people and machine readers.

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./assets/images/01-html-css-git-homework-demo.png)


---
© 2021 Mark Drummond. All Rights Reserved.
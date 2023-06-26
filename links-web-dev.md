# CSS
## html, body {} /* full page size */
https://www.freecodecamp.org/news/html-page-width-height/ :

For years, the answer was the following:
```css
html {
    height: 100%;
}
body {
    min-height: 100%;
}
```
This allows the HTML element to reference the parent viewport and have a height value equal to 100% of the viewport value.

With the HTML element receiving a height value, the min-height value assigned to the body element gives it an initial height that matches the HTML element.

This also allows the body to to grow taller if the content outgrows the visible page.

The only drawback is the HTML element does not grow beyond the height of the visible viewport. However, allowing the body element to outgrow the HTML element has been considered acceptable.

Today, use viewport height on body only (URL from above):
```css
body { min-height: 100vh; }
```

# Node.js
## npm / nvm
https://bobbyhadz.com/

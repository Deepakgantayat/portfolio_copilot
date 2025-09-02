# Fonts Used in the Personal Portfolio Project

This project utilizes various fonts to enhance the visual appeal and readability of the website. Below are the details of the fonts used:

## Google Fonts

1. **Roboto**
   - A modern, sans-serif typeface that is clean and highly legible.
   - Link: [Roboto on Google Fonts](https://fonts.google.com/specimen/Roboto)

2. **Open Sans**
   - A humanist sans-serif typeface designed for legibility across print, web, and mobile interfaces.
   - Link: [Open Sans on Google Fonts](https://fonts.google.com/specimen/Open+Sans)

## Custom Fonts

- If any custom fonts are added to the project, they will be placed in this directory. Ensure to include the appropriate `@font-face` declarations in the CSS file to use them.

## Usage

To use the fonts in your project, include the following in your HTML file within the `<head>` section:

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
```

In your CSS, you can apply the fonts as follows:

```css
body {
    font-family: 'Roboto', sans-serif;
}

h1, h2, h3, h4, h5, h6 {
    font-family: 'Open Sans', sans-serif;
}
```

Make sure to adjust the font weights and styles as needed for different elements throughout your portfolio.
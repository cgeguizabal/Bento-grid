# Bento Grid Layout - Frontend Mentor Challenge

This project is a responsive grid-based layout inspired by the **Frontend Mentor Bento Grid** challenge. It demonstrates the use of CSS Grid, custom fonts, modern CSS features, and responsive design principles.

---
# Preview
https://testimonials-cssgrid.netlify.app/
---
## Features

- **Responsive Grid Layout:** Uses CSS Grid with `auto-fit` and `minmax()` to create a flexible, dense grid.
- **Custom Fonts:** Implements `@font-face` with variable fonts and fallbacks for the `DMSans` font family.
- **Modern CSS Variables:** Utilizes CSS custom properties (`--light-purple`, `--purple`, etc.) for easy theming.
- **Consistent Box Model:** Uses universal selector `*` styles for `margin`, `padding`, and `box-sizing`.
- **Shadows and Rounded Corners:** Classes `.shadow` and `.borderR` add depth and rounded corners for UI elements.
- **Accessibility:** Semantic HTML with headings, images with alt attributes.
- **Image Optimization:** Uses WebP images with appropriate alt texts for illustration purposes.

---


---

## Usage

1. Clone the repository or download the files.
2. Make sure your web server serves the `/assets/fonts` and `/assets/img` folders correctly.
3. Open `index.html` in your browser to view the layout.
4. Resize the browser window to see responsive behavior.

---

## CSS Highlights
### Font Faces
```css
@font-face {
  font-family: DMSans;
  src: url("/assets/fonts/DMSans-VariableFont_opsz,wght.woff2") format("woff2-variations"),
       url("/assets/fonts/DMSans-Regular.woff2") format("woff2"),
       url("/assets/fonts/DMSans-Regular.ttf") format("truetype"),
       url("/assets/fonts/DMSans-Medium.woff2") format("woff2"),
       url("/assets/fonts/DMSans-Medium.ttf") format("truetype");
  font-style: normal;
  font-weight: 100 500;
  font-optical-sizing: auto;
}



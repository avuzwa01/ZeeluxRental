# ZeeluxRentals - Part 3 Submission

## Project Overview
This is a responsive dress rental website built for Part 3 of the assignment. It includes external CSS styling, responsive design breakpoints, and functional contact and enquiry forms using Formspree.

## Changelog
- **Part 1 Feedback Implementation:** Removed all inline `style` attributes (e.g., `style="color: goldenrod;"`) from all HTML files and replaced them with an external CSS file (`style.css`).
- **HTML Validation:** Fixed broken HTML tags, including unclosed `<div>` elements and improper `<ul>` nesting in `about-us.html`. Removed duplicate `</section>` tags in `services.html`.
- **Base Styling:** Added a CSS reset (`* { margin: 0; padding: 0; box-sizing: border-box; }`) and set a consistent font family and color scheme.
- **Layout Structure:** Implemented CSS Grid and Flexbox for the navigation, service cards, and "Who we are" sections to create a clean desktop layout.
- **Visual Styles:** Added hover and focus pseudo-classes to navigation links, buttons, and form inputs. Added box-shadows to sections for depth.
- **Responsive Design:** Added media queries for `max-width: 768px` (Tablet) and `max-width: 480px` (Mobile). The layout switches from multi-column to single-column, and navigation stacks vertically on mobile.
- **Responsive Images:** Applied `max-width: 100%; height: auto;` to all images.
- **Part 3 Forms:** Integrated Formspree to handle form submissions. The `contact.html` form sends a general email, and the `enquiries.html` form processes specific dress rental enquiries with date and size validation.

## Testing and Screenshots
*(Add your screenshots to a folder called `screenshots` in your repository and link them here)*

### Desktop View
![Desktop View](./screenshots/desktop.png)

### Tablet View
![Tablet View](./screenshots/tablet.png)

### Mobile View
![Mobile View](./screenshots/mobile.png)

## References
- MDN Web Docs. (2026). *CSS: Cascading Style Sheets*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS
- W3Schools. (2026). *CSS Responsive Web Design*. Available at: https://www.w3schools.com/css/css_rwd_intro.asp
- Formspree. (2026). *Formspree Documentation*. Available at: https://help.formspree.io/

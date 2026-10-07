# Atelier — Art Gallery Website

**Topic:** Art Gallery Website  
**Group members:** Zhanserik Zharylgassyn and Erkebulan Korganbek  
**Published website:** https://znsrk.github.io/atelier-art-gallery/  
**Repository:** https://github.com/znsrk/atelier-art-gallery

Atelier is a simple, responsive art gallery made for a web development midterm. A cream, terracotta, and olive palette gives the website a gallery-like atmosphere. The six SVG artworks are original illustrations made for this project; all artist personas and exhibitions are fictional.

## Pages and features

- Home: introduction, featured artworks, and an exhibition preview.
- Gallery: six artworks arranged with CSS Grid.
- Artists: three fictional profiles with links to their artwork.
- Exhibitions: a virtual exhibition preview and an accessible table.
- About: project description and group member names.
- Contact: labeled fields, a dropdown, and native required/email validation.
- Form confirmation: a separate page explaining that the form is a demo.
- Shared semantic header, main, footer, and visible navigation on every page.
- Bootstrap responsive columns, containers, spacing, buttons, and alignment utilities.
- CSS variables, Flexbox, Grid, relative/absolute positioning, hover/focus styles, and alternating items with `:nth-child()`.
- Tablet and mobile breakpoints, a keyboard skip link, image descriptions, and lazy loading below the fold.

## Technologies

HTML5, CSS3, SVG images, and **Bootstrap 5.3.8 CSS only**. Google Fonts provides DM Sans and Playfair Display, with Arial/Georgia fallbacks. There is no JavaScript, framework, package installation, or build step.

Bootstrap CSS is included locally in `vendor/bootstrap.min.css`. Its MIT license is in `vendor/bootstrap-LICENSE.txt`. Source: https://getbootstrap.com/docs/5.3/getting-started/download/

## Run and edit

Open `index.html` in a browser. All pages use relative links, so they also work on GitHub Pages. Google Fonts needs an internet connection; the site falls back to system fonts offline.

- Edit text directly in the `.html` files.
- Edit the shared design in `css/style.css`.
- Edit artwork shapes in `images/*.svg`.
- Navigation and footer markup is repeated intentionally to keep the project beginner friendly; update all pages when changing it.

The contact form is a demonstration, with no backend or delivery service. The browser validates the fields before opening `thank-you.html`. Inputs intentionally omit `name` attributes so sample values are not put in the URL or sent to the host. No message is delivered or stored. Footer social links lead to the platform homepages, not gallery accounts.

## Individual contribution plan

The following is a **suggested division for group review and defence preparation**, not a claim of completed work by either member. Replace it with the actual contributions before submitting.

| Member | Suggested responsibility |
| --- | --- |
| Zhanserik Zharylgassyn | Review Home, Gallery, and About; explain the shared navigation, CSS Grid, artwork assets, and GitHub Pages setup. |
| Erkebulan Korganbek | Review Artists, Exhibitions, and Contact; explain Bootstrap columns, the exhibition table, HTML form validation, and responsive breakpoints. |

Both members should understand the complete website and practise editing headings, colors, spacing, and responsive layouts.

## GitHub Pages

The website is published from the `main` branch, `/ (root)` folder. Commit and push changes to update the live site.

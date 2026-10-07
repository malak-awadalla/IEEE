# IEEE Members Website

A static website made with HTML, CSS, and SVG graphics. No JavaScript, dependencies, or build step.

## Folder contents

- `index.html`: page structure, accessible text, MEMBERS letters, and signup link.
- `assets/css/styles.css`: colors, layouts, button styling, animations, and responsive rules.
- `assets/graphics/`: vector headings and decorative artwork from your supplied PDF.

## Preview

Extract the ZIP and double-click `index.html` to open the website in your browser.

## Editing

- Change the signup destination in the `.button` link in `index.html`.
- Change colors in the `:root` block in `assets/css/styles.css`.
- The `LAPTOP` section controls the desktop composition.
- The final `PDF TYPOGRAPHY AND PHONE DESIGN` section controls the PDF phone layout and heading artwork. These phone rules override the earlier phone defaults.
- `pop-in`, `bob`, and `float` control the animations. Reduced-motion preferences are respected.
- PP NeueBit headings are SVG artwork, not an installed webfont. To change heading wording, replace the matching graphic and update its screen-reader text in `index.html`.

## Vercel

Upload or push the folder contents to your existing project. Use the Other framework preset, no build command, and the project root as the output directory. Keep the assets folder alongside index.html.

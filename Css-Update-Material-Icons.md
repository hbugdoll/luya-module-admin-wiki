Follow the steps below to update the Material Icons font:

1. Download the latest .ttf version through the Google font api:  
Open https://fonts.googleapis.com/icon?family=Material+Icons and copy the link to the woff2 file (`@font-face` -> `src`).
2. Check if the CSS code changed: [Google Material Docs](https://google.github.io/material-design-icons/#setup-method-2-self-hosting).  
File: `src/resources/scss/fonts/_material-icons.scss`
3. Generate .eot, .woff and .ttf from the .woff2 file: https://transfonter.org/
4. Replace the font files under `src/resources/fonts/material-icons/`
5. Test the new Icons (you can use an HTML Block with `<span class="material-icons">name_of_new_icon</span>` and "Render HTML" `true` in Block Config)
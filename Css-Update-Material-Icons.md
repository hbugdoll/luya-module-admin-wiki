Follow the steps below to update the Material Icons font:

1. Download the latest .ttf version from the [Material Icons Github Repo](https://github.com/google/material-design-icons/blob/master/font/MaterialIcons-Regular.ttf).
2. Check if the CSS code changed: [Google Material Docs](https://google.github.io/material-design-icons/#setup-method-2-self-hosting).  
File: `src/resources/scss/fonts/_material-icons.scss`
3. Generate .eot, .woff and .woff2 from the .ttf file: https://transfonter.org/
4. Replace the font files under `src/resources/fonts/material-icons/`
5. Test the new Icons (you can use an HTML Block with <span class="material-icons">3d_rotation</span> and "Render HTML" true in config)
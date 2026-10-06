# Ernest Amiel C. Serrano - Portfolio

Static site, no build step. Open `index.html` in a browser or upload the whole folder to any static host.

```
index.html      page markup and content
css/styles.css  all styling (colors are variables at the top of :root)
js/main.js      mobile menu toggle
images/         optional: put local copies of images here
```

Images (logo, profile photo, resume photo) and the resume PDF currently load from the Duda CDN.
To host them yourself, download them into `images/` and update the `src`/`href` paths in `index.html`.
Project tiles are placeholders: replace each `<div class="shot">` with an `<img>` of the site screenshot.

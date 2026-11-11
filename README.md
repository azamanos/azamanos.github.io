# azamanos.github.io

Personal homepage of Andreas Zamanos, served by GitHub Pages at https://azamanos.github.io.

It is a single static page with no build step: everything is in `index.html`.

## Editing

- **Add a publication:** in `index.html`, copy one `<li class="a-item">` block inside the Publications list and change the year, title, authors, venue and links.
- **Add software or a dataset:** same, inside the "Software & datasets" list.
- **Change the photo:** the portrait is loaded from the Archimedes site. To host your own copy, save it as `assets/photo.jpg` and set the image `src` in `index.html` to `assets/photo.jpg`. If the image cannot load, the initials "AZ" show instead.
- **Change links or bio:** edit the sidebar (`<aside class="a-side">`) and the About section.
- **Colours and fonts:** the tokens at the top of the second `<style>` block (`.tA{ --bg … }`), with the dark theme values right below.

## Deploying

Push to the default branch. GitHub Pages publishes the repository root. The empty `.nojekyll` file tells Pages to serve the files as they are.

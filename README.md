# Myeongsoo Song — Personal Website

A minimal, responsive personal website ready to be hosted with GitHub Pages.

## Preview locally

Open `index.html` in a web browser. No build step or dependencies are required.

## Add a profile photo

1. Create an `assets` directory.
2. Save the photo as `assets/profile.jpg`.
3. In `index.html`, replace the contents of `.profile-photo` with:

```html
<img src="assets/profile.jpg" alt="Myeongsoo Song" />
```

## Add LinkedIn

Add the following link inside `.contact-list` in `index.html`:

```html
<a href="YOUR_LINKEDIN_URL" target="_blank" rel="noreferrer">LinkedIn</a>
```

## Publish with GitHub Pages

1. Create a public repository named `myeongsoo-song.github.io`.
2. Push the files in this directory to the repository's `main` branch.
3. In the repository settings, open **Pages** and select **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.

The site will be available at `https://myeongsoo-song.github.io/`.

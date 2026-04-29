# Gahee Kim — Foster + Partners Portfolio Site

Static one-page portfolio website for GitHub Pages.

## How to use

1. Create a GitHub repository, e.g. `gahee-portfolio`.
2. Upload `index.html` and `styles.css` to the repository root.
3. Go to **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch: `main` / root.
6. Your website will be available at:
   `https://YOUR_USERNAME.github.io/gahee-portfolio/`

## Codex prompt

Create a minimal Foster + Partners-inspired one-page portfolio site using the existing `index.html` and `styles.css`. Replace placeholders with project images, keep typography minimal, preserve large whitespace, and do not add visual effects unless they improve clarity.

## Image replacement

Replace placeholder blocks in `index.html` with real images:

```html
<img src="images/project-name.jpg" alt="Project description">
```

Then add this CSS if needed:

```css
.project-image img,
.hero-image img,
.feature-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

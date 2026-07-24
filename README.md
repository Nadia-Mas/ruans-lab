# Ruan's Lab — GitHub Pages starter

A responsive, one-page research lab website built with plain HTML, CSS, and JavaScript. No build step or framework is required.

## Sections

- Home
- Team
- Publications
- Open Positions
- Gallery
- Contact

The fixed navigation uses anchor links and smooth scrolling to move visitors to the corresponding section.

## Preview locally

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a repository named `YOUR-USERNAME.github.io` for a root website, or use any repository name for a project website.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save. GitHub will provide the public URL.

## Customize first

Search the project for these placeholders:

- `YOUR_EMAIL@utsa.edu`
- Example team members
- Example publications
- `href="#"` placeholder links
- Gallery placeholder blocks

Replace the placeholder initials in the Team section with real photos. One simple pattern is:

```html
<div class="person-photo">
  <img src="assets/images/person-name.jpg" alt="Person Name">
</div>
```

Then add this CSS:

```css
.person-photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

## Logos and institutional identity

The included DNA mark and text-only UTSA lockup are original placeholders, not official institutional marks. Replace them with approved Ruan's Lab and UTSA logo assets and follow UTSA brand standards before public launch.

Suggested files:

- `assets/images/ruan-lab-logo.svg`
- `assets/images/utsa-logo.svg`

Use official, authorized files rather than recreating the UTSA logo.

## Design notes

The project uses an original dark-navy, orange, teal, and cream visual system inspired by modern research-group websites. It includes:

- Sticky navigation
- Active-section highlighting
- Responsive mobile menu
- Smooth anchor scrolling
- Scroll-reveal animation
- Reduced-motion accessibility support
- Keyboard skip link
- Responsive team, publication, position, and gallery layouts

## License

Add the license your lab prefers before making the repository public. MIT is a common option for website source code, but confirm with the lab and university first.

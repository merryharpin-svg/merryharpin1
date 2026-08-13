# Merry Harpin — Artist Website

A clean, elegant single-page website built just for you.

**Colors used:** Black, White, Pale Blue

---

## How to open & edit the site

1. Download the entire `merryharpin-site` folder.
2. Open `index.html` in any browser to see the site.
3. To edit text or colors:
   - Open `index.html` or `styles.css` in any text editor (VS Code, Notepad, TextEdit, etc.)
   - Make your changes and save.
   - Refresh the browser.

### Easy things you can change

**In `styles.css` (at the top):**
```css
--black: #0a0a0a;
--white: #f7f7f7;
--pale-blue: #a8c5d4;
```
Change these values and the whole site updates.

**In `index.html`:**
- Edit the About text
- Change titles of artworks
- Update contact info if needed

### Adding your own artwork

1. Create a folder called `images` next to `index.html`.
2. Put your photos/drawings inside it.
3. In `index.html`, find the portfolio items and replace the placeholder like this:

```html
<article class="portfolio-item">
  <img src="images/my-drawing.jpg" alt="Description of the piece">
  <div class="portfolio-info">
    <h3>Title of the Piece</h3>
    <p>Graphite · 2025</p>
  </div>
</article>
```

---

## How to put it online (free)

### Option 1 — Netlify (easiest)
1. Go to [netlify.com](https://www.netlify.com) and sign up (free).
2. Drag and drop the whole `merryharpin-site` folder onto the Netlify dashboard.
3. Your site will be live in seconds with a free netlify.app address.
4. Later you can connect your real domain (merryharpin.com).

### Option 2 — GitHub Pages
1. Create a free GitHub account.
2. Create a new repository and upload the files.
3. Turn on GitHub Pages in the settings.

### Connecting your domain (merryharpin.com)
Once the site is live on Netlify or GitHub Pages, you can point your domain to it in the hosting settings (or in your domain registrar). Netlify has a simple guide for this.

---

## Need changes later?
Just open the files and edit them. You own 100% of the code.

Enjoy your new site!

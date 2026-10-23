# Gallus Lab

An interactive field notebook about the chicken (*Gallus gallus domesticus*), made for an organism research project.

**Pages**

- **Anatomy:** egg, embryo, chick and adult, outside and inside, plus a hen vs. rooster comparison
- **Field Guide:** 13 breeds as hens and roosters, plus feather types and patterns
- **Timeline:** from the first shelled egg to today, plus a chicken's 24-hour day
- **Intelligence:** a quiz written from a chicken's point of view
- **Relationships:** how chickens connect to the environment and to people

The whole site is a single `index.html` file. It has no build step and no dependencies. Fonts load from Google Fonts.

## Publish with GitHub Pages

1. Create a new public repository on GitHub, for example `gallus-lab`.
2. Upload `index.html`, `.nojekyll` and this `README.md` to the root of the repository.
   - On GitHub's website, use **Add file → Upload files**.
   - `.nojekyll` is a hidden file. If your computer hides it, you can skip it; the site works without it.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute or two the site is live at `https://<your-username>.github.io/gallus-lab/`.

Each page has its own link, for example `.../gallus-lab/#anatomy` or `.../gallus-lab/#breeds`.

## Preview on your computer

Double-click `index.html` to open it in your browser.

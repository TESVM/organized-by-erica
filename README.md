# The Erica Edit Website

Static marketing site built for GitHub Pages.

## Files

- `index.html`: homepage structure and copy
- `styles.css`: site styling, layout, responsive behavior, and animations
- `script.js`: mobile navigation, section reveal animation, and footer year
- `assets/organized-space-*.svg`: replaceable image placeholders

## What To Replace

1. Business name
   Update `The Erica Edit` in `index.html` if the brand changes later.
2. Contact details
   Replace email, phone, social handles, and service area details in `index.html` as needed.
3. Images
   Replace the SVG files in `assets/` or update the `src` values in `index.html` with real photos.
4. Form handling
   Connect the contact form to Formspree, Netlify Forms, Basin, or another form service.
5. Metadata
   Update the `<title>`, meta description, and any local business keywords if needed.

## Suggested Future Pages

- `about.html`
- `services.html`
- `gallery.html`
- `testimonials.html`
- `contact.html`

## GitHub Pages Deployment

1. Create a new GitHub repository.
2. Push these files to the repository root.
3. In GitHub, open `Settings > Pages`.
4. Set the source to `Deploy from a branch`.
5. Choose the `main` branch and `/root`.
6. Save. GitHub Pages will publish the site.

## Local Preview

Run either of these from this folder:

```bash
python3 -m http.server 8000
```

or

```bash
npx serve .
```

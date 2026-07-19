# Deshmed Healthcare Static Website

Static multi-page website for Deshmed Healthcare, built with plain HTML, CSS, and JavaScript so it can be hosted on Netlify's free static hosting.

## Pages

- `index.html`
- `products.html`
- `about.html`
- `quality.html`
- `contact.html`
- `privacy-policy.html`
- `thank-you.html`

## Netlify Deployment

1. Upload this folder to Netlify or connect it to a Git repository.
2. No build command is required.
3. Publish directory: `.`
4. The contact form uses Netlify Forms with the form name `wholesale-enquiry`.
5. In Netlify, open Site configuration > Forms > Form notifications and add `alcrestahealthcare@gmail.com` as the email recipient.

## Local Preview

```bash
python -m http.server 4173
```

Then open `http://127.0.0.1:4173`.

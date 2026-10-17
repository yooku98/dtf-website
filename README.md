# DTF Yooku

Landing page for DTF Yooku — direct-to-film (DTF) printing, custom T-shirts and transfers in Ghana.

**Live demo:** https://yooku98.github.io/dtf-website/

## What's on the page

- What we do, services, and why-choose-us sections
- How to order / how it works
- Sample work gallery and customer testimonials
- Contact section; orders go through WhatsApp (`wa.me` links with a pre-filled message)

## Stack

HTML + CSS (`index.html`, `style.css`) with a small inline script for the WhatsApp order link. No build step.

## Structure

```
index.html   Page markup
style.css    Styles
images/      Sample print photos
```

## Run locally

```bash
python3 -m http.server 8000
```

## Deployment

Served by GitHub Pages from the root of `main`.

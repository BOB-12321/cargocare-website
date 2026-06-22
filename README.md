# Cargocare Website

Custom static website for [cargocare.ie](https://cargocare.ie) — freight forwarding between the UK and Ireland.

## Stack

Plain HTML, CSS, JavaScript. No frameworks, no build step.

## Development

```bash
# Serve locally
python3 -m http.server 3015

# Or with live reload
npx live-server .
```

## Deploy

Static files — push to any hosting (Cloudflare Pages, GitHub Pages, Netlify, S3, etc).

## Structure

```
├── index.html     # Homepage
├── logo.png       # Company logo
├── services/      # Service sub-pages (coming)
├── company/       # Company pages (coming)
└── contact/       # Contact page (coming)
```

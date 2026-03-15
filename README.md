# Wagner IT-Solutions — Website

Statische Website für [Wagner IT-Solutions](https://wagner-its.at), deployed über Cloudflare Pages.

## Deployment

### Cloudflare Pages Setup
1. Repository mit GitHub verbinden
2. **Build command:** _(leer lassen)_
3. **Build output directory:** `/`
4. **Root directory:** `/`

Keine Build-Tools nötig — rein statisches HTML, CSS & JS.

## Struktur

```
├── index.html        # Komplette Website (Single-File)
├── logo-dark.png     # Logo für dunklen Hintergrund
├── logo-light.png    # Logo für hellen Hintergrund
├── _headers          # Cloudflare Pages Security & Cache Headers
├── _redirects        # Cloudflare Pages Routing
├── .gitignore
└── README.md
```

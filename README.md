# Modern GB Corporate Site

Static GitHub Pages site for `moderngb.net`, the corporate and
application-development home for the Modern GB ecosystem.

## Purpose

- Present Modern GB as the development identity for philately, postal workflow,
  and counter-side software.
- Link the ecosystem domains:
  - `moderngb.com`
  - `stampdecoder.app`
  - `c2t.dev`
  - `kiosk.c2t.dev`
- Provide a future home for shared integration work such as Royal Mail tracking,
  parcel sizing, carrier data, policy pages, and app support routes.

## GitHub Pages

This site is ready to serve from GitHub Pages using the repository root.

The `CNAME` file sets the custom domain to:

```text
moderngb.net
```

Once the repository is pushed to GitHub and Pages is enabled, update DNS with
the records GitHub provides for the custom domain.

## Local Preview

Open `index.html` directly in a browser, or serve the directory locally:

```bash
python3 -m http.server 8080
```

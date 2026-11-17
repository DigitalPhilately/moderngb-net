# Modern GB Corporate Site

Static GitHub Pages site for `moderngb.net`, the company site for Modern GB.

## Purpose

- Present Modern GB as the company behind its collector apps and reference sites.
- Link the collector-facing domains:
  - `moderngb.com`
  - `stampdecoder.app`
  - `barcodedstamps.com`
  - `firstdaycover.co.uk`
- Keep to the collector side only. Test tools and work outside stamp collecting
  are not listed here.

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

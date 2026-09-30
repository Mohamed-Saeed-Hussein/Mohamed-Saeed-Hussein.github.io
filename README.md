# Portfolio Entry Point

**A stable GitHub Pages address for Mohamed Saeed's portfolio.**

[Open the portfolio](https://dr-nullptr.vercel.app/) · [GitHub profile](https://github.com/Mohamed-Saeed-Hussein)

---

## What this repository does

This repository hosts a small redirect page at:

**https://mohamed-saeed-hussein.github.io/**

The current destination is **https://dr-nullptr.vercel.app/**. The full portfolio application is maintained separately.

## How the redirect works

[index.html](index.html) contains:

- a JavaScript `location.replace` redirect;
- a meta refresh as a fallback;
- a visible link for manual navigation;
- a canonical URL pointing to the portfolio.

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Opening [localhost:8000](http://localhost:8000) should redirect to the portfolio.

## Updating the destination

Keep the JavaScript destination, meta refresh, canonical URL, and visible link in sync when changing the portfolio address. The page has no build step or package dependencies.

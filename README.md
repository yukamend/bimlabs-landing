# bimlabs.xyz

Landing page for Bim Labs: a directory of the tools on `*.bimlabs.xyz` plus selected work.

Plain static HTML/CSS — no build step.

```
index.html     page content (tools + work cards)
styles.css     styles
images/        site screenshots (800×500 JPEG)
favicon.svg
vercel.json    Vercel config (static, clean URLs)
```

## Local preview

```bash
npx serve .
```

## Deploy

Vercel → Add New Project → import this GitHub repo → Framework preset "Other", no build command, output directory `.`. Then add `bimlabs.xyz` under Project → Settings → Domains.

## Adding a tool

Copy a `<a class="card">` block in the Tools section of `index.html`, drop an 800×500 screenshot in `images/`, and bump the count in the section heading.

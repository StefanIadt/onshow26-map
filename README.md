# On Show 26 — Wayfinding map (proof of concept)

**Live (GitHub Pages):** [https://stefaniadt.github.io/onshow26-map/](https://stefaniadt.github.io/onshow26-map/)

**Repository:** [github.com/StefanIadt/onshow26-map](https://github.com/StefanIadt/onshow26-map)

Static site: `index.html` plus `fonts/` and `assets/`. You can also deploy to [Vercel](https://vercel.com/) for a different hostname or a custom domain.

## Run locally

Open `index.html` in a browser, or from this directory:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to Vercel (recommended)

1. Push this repo to GitHub (or GitLab / Bitbucket).
2. In Vercel: **Add New Project** → import the repo. Framework preset: **Other**; root directory: leave default (repo root contains `index.html`).
3. Deploy. You get a URL like `https://<project-name>.vercel.app`.

### Customise the free hostname

In Vercel: **Project → Settings → Domains**. The default `*.vercel.app` name comes from the **project name** (**Settings → General → Project Name**). Changing the project name changes the default subdomain (when not conflicting).

### Use your own domain later

Add the domain under **Domains** and set the DNS records Vercel shows (often a `CNAME` to `cname.vercel-dns.com`). Many registrars charge roughly the cost of the domain only; Vercel does not charge extra for custom domains on the hobby tier.

## Original design handoff

The upstream spec and notes live in `../handoff/README.md` (sibling folder under `onshow26`).

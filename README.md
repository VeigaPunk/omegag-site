# omegag-site

Static marketing site for **omegaG** (formerly DS4CC), mirrored for GitHub Pages under the VeigaPunk user account.

Source of truth: [`vgpnk-holdings-llc/omegaG`](https://github.com/vgpnk-holdings-llc/omegaG) → `website/`.

## Live

- **Intended Pages URL:** https://veigapunk.github.io/omegag-site/
- **Rolling zip:** https://github.com/vgpnk-holdings-llc/omegaG/releases/tag/website-static
- **Canonical product repo:** https://github.com/vgpnk-holdings-llc/omegaG

## Enable Pages (once)

Repo **Settings → Pages → Build and deployment**:

1. Source: **GitHub Actions** (workflow in `.github/workflows/`), **or**
2. Source: **Deploy from a branch** → `main` / `/` (root)

Until that is set, `*.github.io` returns 404 even when `main` is current.

## Local

```bash
python3 -m http.server 8080 --bind 127.0.0.1
# open http://127.0.0.1:8080/
```

## Sync from product tree

```bash
# from a checkout of vgpnk-holdings-llc/omegaG
cp website/index.html website/style.css website/main.js /path/to/omegag-site/
rm -rf /path/to/omegag-site/assets && cp -a website/assets /path/to/omegag-site/assets
```

# SciTex website

Single-page static marketing site for SciTex (Cin7 Core ERP implementation, QuickBooks Online integration, and inventory and traceability consulting), based in Riverview, New Brunswick.

- `index.html` is fully self-contained: inline CSS, no JavaScript, no external dependencies, no tracking.
- Deploys via **GitHub Pages**: push these files to the repository root (or `/docs`) and enable Pages under *Settings → Pages*, choosing the branch/folder.
- The `CNAME` file sets the custom domain to `scitex.ltd`. At the DNS provider, point the apex `A` records to GitHub Pages (185.199.108.153, .109.153, .110.153, .111.153) and/or add a `www` CNAME to `<username>.github.io`, then enable *Enforce HTTPS* in Pages settings.
- Contact address `omar@scitex.ltd` is a placeholder mailto link.

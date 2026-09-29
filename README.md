# RoriSummit website

Static website prepared for GitHub Pages. Upload these files to the root of a GitHub repository, then enable Pages from the `main` branch at `/ (root)`.

Custom domain: `rorisummit.it.com` (also present in `CNAME`). Configure the domain in Settings → Pages before changing DNS. For a domain managed as an apex zone, add the current GitHub Pages A records to the domain's DNS. Remove the old hosting A and verification records only after the GitHub Pages configuration is ready. Wait for HTTPS to become available, enable **Enforce HTTPS**, and verify the homepage, portfolio and dental dashboard at the custom domain.

The enquiry form opens a mail draft in the visitor's email application; it does not submit to a server. The dental dashboard is an illustrative concept and loads Three.js from a public CDN, with a local 2D fallback.

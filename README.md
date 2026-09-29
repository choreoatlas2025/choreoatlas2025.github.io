# ChoreoAtlas resource landing

A temporary, factual landing page for the organization site. It links only to public resources that were checked as reachable on 2026-09-29. The page deliberately omits the old website's unverified commercial claims, pricing, testimonials, and nonfunctional contact form.

The page has a `noindex` meta tag while it is used as a staging URL. Remove that tag when the intended canonical domain is connected and the content is approved for indexing. Do not add a root-level `robots.txt` disallow rule: it would also affect the existing `/docs/` project site on the same GitHub Pages host.

To connect `choreoatlas.com`, set it as this repository's GitHub Pages custom domain, replace the registrar parking A records with the current [GitHub Pages apex records](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site), and set `www` to the organization's GitHub Pages host. Verify the domain in organization settings and enforce HTTPS after the certificate is issued. DNS changes require access to the domain's Spaceship account.

# piccola-accademia-static

Static, Markdown-first reconstruction of the public PIKIMONI marketing site for GitHub Pages.

## Scope

Included public pages: home, about, administrators, authors, honor wall placeholder, pricing, login and registration links. The authenticated learning application is intentionally not copied.

The copy was transcribed from publicly visible pages on pikimoni.ru on 2026-09-28. Review text, prices, links, privacy/legal content, and image rights before publishing.

## Run locally

```bash
bundle install
bundle exec jekyll serve --livereload
```

Open `http://127.0.0.1:4000`.

## Publish on GitHub Pages

1. Create a GitHub repository named `piccola-accademia-static`.
2. Push this directory to the `main` branch.
3. In **Settings > Pages**, choose **GitHub Actions** as source.
4. The included workflow builds and deploys the Jekyll site.

## Custom domain

After validating the GitHub Pages preview, configure the custom domain in repository Pages settings and update DNS. Add a `CNAME` file only when ready to switch production traffic.

## Images

The text crawler exposed image placeholders but not reliable original asset URLs. Add owned/authorized assets under `assets/images/` and reference them from Markdown or layouts. Do not commit private application content, credentials, subscriber data, or copyrighted course materials without authorization.

# piccola-accademia-static

Static, Markdown-first reconstruction of the public PIKIMONI marketing site for GitHub Pages.

## Scope

Included public pages: home, about, administrators, authors, the student-work gallery, pricing, and login and registration information. The authenticated learning application is intentionally not copied.

The public marketing copy and assets were refreshed from pikimoni.ru on 2026-09-29. Review text, prices, links, privacy/legal content, and image rights before publishing.

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

The public homepage and team images are in `assets/images/home/` and `assets/images/authors/`; the 17 public student-work gallery images are in `assets/images/doska/`. Confirm that you have permission to republish each image. Do not commit private application content, credentials, subscriber data, or copyrighted course materials.

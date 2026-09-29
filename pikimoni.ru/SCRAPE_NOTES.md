# Scrape notes

Source pages consulted:

- https://pikimoni.ru/
- https://pikimoni.ru/about
- http://pikimoni.ru/about_admin
- http://pikimoni.ru/about_avtori
- http://pikimoni.ru/doska
- http://pikimoni.ru/price
- https://pikimoni.ru/vhod

This is a maintainable reconstruction, not a byte-for-byte mirror. Public text was normalized into Markdown and the visual style was recreated with custom CSS. The live site was inspected again on 2026-09-29 because the expected `legacy/pikimoni.ru` source directory was not present in the workspace.

The migration restores the homepage's platform explanation, getting-started steps, video links and six testimonials; the mission statement; expanded team biographies; teacher, parent and school registration information; and all 16 program-level price rows. The Wall of Fame's 17 public gallery images and the public homepage/team images were downloaded into `assets/images/` so the static site does not depend on Tilda's image host.

Dynamic authentication, payments, application logic and protected course content were not copied. Verify image republication rights and re-check pricing and registration instructions before deployment.

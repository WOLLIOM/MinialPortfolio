RADOYA / SIMON MAXAM — BASIC SEO FILES

Files:
- robots.txt: tells crawlers they may crawl the public site and points to the sitemap.
- sitemap.xml: currently lists the homepage only because the supplied website is a single-page site.
- seo-meta-snippet.html: metadata to add inside the <head> of index.html.

IMPORTANT:
Replace every occurrence of https://YOUR-DOMAIN with the exact public website origin, for example:
https://simonmaxam.pages.dev

Only use that example if it is the actual deployed URL. If you use a custom domain, use the custom domain consistently instead.

Upload robots.txt and sitemap.xml to the ROOT of the deployed site, alongside index.html. Add the contents of seo-meta-snippet.html inside index.html's <head>, and do not add a second canonical tag if one is added later.

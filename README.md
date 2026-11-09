# Mobile Typing Tutor

Static site. No build step. Every page is self-contained (CSS and JS are inside the page), so no extra files are needed to run it.

## Deploy
Upload all files (not the src folder is optional) to GitHub with index.html at the top, and connect the repo to Cloudflare Pages (build command empty, output directory /).

## Add a new page
Copy a similar page, rename it and change title, description and content. Link it from articles.html. Add it to sitemap.xml once you have a domain. Never rename or delete live pages. 404.html is shown for missing pages.

## Files
- src/: original CSS and JS source files (for developers)
- Mobile-Typing-Tutor-Offline.html, Urdu-Typing-Tutor-Offline.html: downloadable offline files
- sw.js: offline cache

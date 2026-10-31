# Cllr Rupinder Singh — GitHub Pages website

A static, mobile-first website using only HTML, CSS and plain JavaScript. No npm or build step is required.

## Publish on GitHub Pages
1. Unzip this package.
2. Upload the **contents** of the `rupinder-singh-website` folder to the root of your GitHub repository. `index.html` must be at the repository root.
3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**. Select your publishing branch (normally `main`) and `/ (root)`.
4. Wait for GitHub Pages to publish the site.

## Before public launch
- Open `js/content.js` and replace `[PLACEHOLDER]` with a verified residents-helped figure, or change the label.
- Replace `REPLACE_ME` in `contact.html` and `news.html` with your Formspree form ID, or remove the forms until configured.
- Review `privacy.html` after choosing the actual form/newsletter providers.
- Add your approved photographs to the image folders and list gallery images in `js/content.js`.
- Review all campaign/news copy and dates before publishing.

## Adding photos
Recommended paths:
- `images/hero/` — wide homepage images
- `images/about/` — profile/community images
- `images/gallery/` — gallery images
- `images/campaigns/` — campaign images
- `images/press/` — approved high-resolution press headshots

Then add gallery entries in `js/content.js`, for example:
```js
{src:"images/gallery/street-surgery.jpg", caption:"Street surgery on Binley Road", category:"community"}
```

## Custom domain
If you later point a custom domain at GitHub Pages, configure it in **Settings → Pages → Custom domain**. GitHub may create a `CNAME` file automatically. If you manage it manually, the `CNAME` file should contain only the domain name, e.g. `www.example.co.uk`.

## Structure
All pages use relative links, so the site works from a GitHub Pages project repository as well as a custom domain.

## Important
The included privacy page is a launch-ready framework, not legal advice. Update it to accurately describe the services and data processing you actually use.

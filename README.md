# Cllr Rupinder Singh — website

A static, photograph-led website for GitHub Pages. Open index.html through a local web server; no build or package installation is needed.

## Editing
- Page copy: the individual HTML files.
- News summaries, campaigns, photographs and contact information: js/content.js.
- Shared navigation, gallery and email draft behaviour: js/main.js.
- Layout: css/style.css, css/pages.css and css/redesign.css (loaded in that order).
- Real photographs: images/hero, images/about, images/campaigns and images/press.

## Contact and updates
The contact form opens a prefilled email draft for the visitor to review and send. It does not submit to a server. Phone and email links are available independently. Newsletter enquiries use email; social updates link to Facebook. No mailing list provider is configured, and no sign-up is submitted automatically.

News entries are general summaries retained from the existing site, not independently verified dated news reports. Add actual articles and publication dates when available. Confirm roles, contact details and surgery arrangements as they change.

## GitHub Pages
Publish from the main branch, repository root. All local links use relative paths, including assets, so the site works under the repository subdirectory. Previous versions remain in Git history.

## Checks
JavaScript syntax, local page/image targets, keyboard navigation, portrait gallery filtering and lightbox behaviour were checked during the rebuild.

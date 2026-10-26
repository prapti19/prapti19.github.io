# Prapti Trivedi — personal website

A lightweight, responsive portfolio for https://prapti19.github.io/, with a
cream background, burgundy accents, experience-led content, and selected papers.
Plain HTML, CSS, and a small optional JavaScript enhancement. No installation,
framework, tracking scripts, external fonts, or build step required.

## Preview

Open `index.html` directly in a browser. All styles, assets, navigation, links,
and CV download work without a development server. JavaScript only updates the
footer year and highlights the visible section in the navigation.

## Publish to GitHub Pages

1. Create the public repository `prapti19/prapti19.github.io`, or use it if it
   already exists. Do not overwrite an existing website without reviewing it.
2. Put the contents of this folder at the repository root on branch `main`.
3. In the repository, open **Settings → Pages**, choose **Deploy from a branch**,
   select `main` and `/ (root)`, then save. GitHub's built-in Pages workflow
   handles publication; no custom workflow is required.
4. GitHub will show the deployment URL under Settings → Pages after publishing.
   The intended address is **https://prapti19.github.io/**.

If uploading using the GitHub web interface, extract the ZIP first and upload
the site files rather than the ZIP or its enclosing folder.

Official setup guide:
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Edit

- `index.html`: biography, experience, publications, education, and contact.
- `styles.css`: colors, typography, spacing, and responsive layouts.
- `assets/Prapti_Trivedi_Resume.pdf`: replace to update the linked CV.
- `assets/prapti-trivedi.jpg`: the beach portrait supplied in this conversation.
  The source photo is unchanged; CSS frames the portrait for the page.

Experience and education are based on the final resume supplied in this task.
Publication titles and complete author lists were checked against arXiv and
Springer. The self-rationalization paper is labeled as a 2024 preprint instead
of asserting a current review status. Google Scholar is linked directly; it
rate-limited automated access during preparation.

The visual direction takes inspiration from Alisa Liu's readable academic
homepage, https://alisawuffles.github.io/, with original layout and copy.

## Verification

Rendered and inspected in the macOS WebKit engine at 1440px, 768px, 390px,
and 320px viewport widths. Checks passed for image loading, section navigation,
JavaScript syntax, and absence of horizontal overflow. Local links and assets,
structured profile JSON, sitemap XML, and text color contrast
were also checked. Chrome could not launch in the restricted environment;
WebKit supplied the browser previews. This repository uses the built-in
branch-based GitHub Pages deployment from `main`.

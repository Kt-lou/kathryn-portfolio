# Kathryn Lewek — GitHub Pages Portfolio

This portfolio is intentionally built as a **single-file website** so it is easy to understand, edit, and publish while you are learning Git, HTML, CSS, JavaScript, and GitHub Pages.

## Files

- `index.html` — the entire live website (HTML + CSS + JavaScript)
- `assets/documents/` — place your résumé and sanitized writing samples here
- `assets/images/` — optional future project images

## Before publishing

Open `index.html` and search for these placeholders:

- `YOUR-LINKEDIN`
- `YOUR-GITHUB-USERNAME`
- `YOUR_EMAIL@example.com`

Replace them with your real links/email.

Add your résumé PDF here and name it exactly:

`assets/documents/Kathryn_Lewek_Resume.pdf`

## Important professional-writing note

The site includes a case-study summary of your technical proposal, but it does **not** include the original PDF. Create a deliberately sanitized public version before adding a downloadable work sample. Remove or generalize customer-specific, proprietary, security-sensitive, location-specific, and operational details before publication.

## Publish on GitHub Pages

1. Create a new GitHub repository, for example: `portfolio`
2. Upload `index.html`, `README.md`, and the `assets` folder.
3. Commit everything to the `main` branch.
4. In the repository, open **Settings**.
5. Click **Pages**.
6. Under **Build and deployment** choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
7. Click **Save**.
8. GitHub will provide your public URL after deployment.

Typical URL:

`https://YOUR-GITHUB-USERNAME.github.io/portfolio/`

## How to edit the site

Because everything is in one file:

- Search for the visible wording you want to change.
- The `<style>` section near the top controls colors, spacing, cards, layout, and mobile behavior.
- The HTML inside `<body>` controls the actual content.
- The small `<script>` near the bottom controls the mobile menu, copyright year, and scroll-reveal effect.

## Suggested next steps

1. Add your real LinkedIn, GitHub, and email.
2. Add your résumé PDF.
3. Publish the site.
4. Finish a sanitized technical-proposal PDF.
5. Build the Requirements Analysis demonstration.
6. Add an API documentation project.
7. Add a docs-as-code project.

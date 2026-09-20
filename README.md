# Slab Worth legal website

This is a complete static website for Slab Worth. It includes the Terms of Use, Privacy Policy, and Apple-required Support page. Upload the six files in this folder to the root of a GitHub repository and enable GitHub Pages; no build command, API key, JavaScript, or paid hosting is required.

## Upload to GitHub Pages

1. Create a public GitHub repository, such as `slab-worth-legal`.
2. Choose **Add file → Upload files** and drag the contents of this folder into the upload area: `index.html`, `privacy.html`, `support.html`, `styles.css`, `README.md`, and `OWNER-CHECKLIST.md`.
3. Commit to `main`.
4. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save.
5. Open the HTTPS address GitHub shows under Pages. The pages are `index.html` (Terms), `privacy.html` (Privacy), and `support.html` (Support).

GitHub project sites normally use `https://YOUR-USERNAME.github.io/REPOSITORY/`. Copy the exact address GitHub provides into App Store Connect. Apple’s Support URL must point to the live `support.html` page, which identifies the developer, shows `haydenfuhrer2@gmail.com`, and provides a direct email action.

## What is included

The Terms describe the confirmed 30 free scans and one-time, non-consumable lifetime Pro unlock. The Privacy Policy describes the app code reviewed for this package: local and iCloud collection storage, optional Sign in with Apple, StoreKit, CardSight AI image identification, card catalog and price providers, artwork services, eBay links, notifications, widgets, support email, retention, deletion, rights requests, and the GitHub Pages host. The Support page covers purchases, scanning, exports, iCloud, technical issues, and privacy requests.

The site uses relative links, has responsive, keyboard-focus, reduced-motion, and print styles, and contains no external fonts, analytics scripts, advertising scripts, forms, cookies, or browser-storage code. GitHub Pages still logs visitor IP addresses for security; the Privacy Policy links to GitHub’s disclosure.

## Before App Store submission

Read `OWNER-CHECKLIST.md`. The public documents are complete prose based on the audited code and published provider terms, but Apple approval and legal compliance also require the app’s behavior to match them. In particular, add an explicit in-app consent step before sending images to CardSight AI, and implement the account/sign-in deletion and token-revocation flow if Sign in with Apple is presented as account creation. Verify provider contracts, App Store privacy labels, age handling, and the legal requirements in the markets where the app will be offered.

This package does not change or redeploy a GitHub repository. If the repository already contains these pages, upload the files and review the resulting diff before committing.

## Local preview

Unzip the download and open `index.html` in a browser. Keep all six files together. The same files work at a GitHub project URL or a custom domain.

# Slab Worth website — GitHub Pages setup

A complete static website. No installation, build command, API key, or paid hosting service is needed for this package. GitHub Pages can serve these files directly.

## Preview it

Unzip the download and double-click `index.html`. Keep `privacy.html`, `support.html`, and `styles.css` beside it. The pages also work without JavaScript.

## Put it on GitHub Pages

1. Sign in to GitHub and create a **new public repository**, for example `slab-worth-legal`. Initialize it with a README so it has a `main` branch. Public repositories support GitHub Pages on GitHub Free. Avoid using an existing app source-code repository unless you intend to publish from it.
2. In the repository, select **Add file → Upload files**.
3. Open the unzipped folder and drag its **contents** into GitHub: `index.html`, `privacy.html`, `support.html`, `styles.css`, `README.md`, and `OWNER-CHECKLIST.md`. Upload the files, not the ZIP and not an extra enclosing folder. Commit the upload to `main`.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select **main** and **/ (root)**, then **Save**.
5. Wait for GitHub's deployment to finish. The **Pages** settings screen will provide the real website address. Open **Visit site**. If it does not appear immediately, check the repository's **Actions** tab for the deployment status.

These steps follow [GitHub's publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site). See also [GitHub's file-upload instructions](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository).

## Your page addresses

For a repository named `slab-worth-legal`, the usual address is:

```text
https://YOUR-GITHUB-USERNAME.github.io/slab-worth-legal/
```

- **Terms of Use:** that website address, or the same address followed by `index.html`.
- **Privacy Policy:** that website address followed by `privacy.html`.
- **App Support:** that website address followed by `support.html`.

Use the exact address GitHub shows you. The example above is not an already deployed website. Custom domains and account-level Pages sites can use different addresses.

## Set the App Store Connect Support URL

After publishing, open your live `support.html` page and copy its full HTTPS address into the **Support URL** field for your app version in App Store Connect. For the example repository above, the format is:

```text
https://YOUR-GITHUB-USERNAME.github.io/slab-worth-legal/support.html
```

Replace the username and repository with your actual values, or copy the deployed address directly from your browser. Use this webpage address in the Support URL field; its email button lets visitors contact you.

The Support page identifies Hayden Fuhrer, displays `haydenfuhrer2@gmail.com`, and includes help for purchases, scans, collections, and technical problems. Confirm that this mailbox is monitored. Apple requires the support website to lead to actual contact information; additional contact details may be required by local law. [Apple's Support URL documentation](https://developer.apple.com/help/app-store-connect/reference/app-information/platform-version-information/).

If you already uploaded the previous package, upload this package's files to the same location and replace the earlier versions. This version updates Pro to a **one-time, non-consumable lifetime unlock** across `index.html`, `support.html`, and the purchase-related privacy wording in `privacy.html`. No change to your existing GitHub Pages settings is needed when the repository and publishing folder stay the same.

If you have made additional edits in the live repository, merge this update into those files instead of overwriting them. The included legal pages still carry the existing review status and incomplete privacy fields. This download has not itself changed or redeployed your GitHub repository.

Verify the deployed Terms describe one payment, no expiry from elapsed time or use, and restoration of the same unlock. Check Support as well. Match the wording to the app's actual non-consumable product and paywall; changing these files does not change the app's purchase configuration.

## Complete the legal drafts before using them in your app

The site deliberately preserves the review status of the documents supplied for this build. The Privacy Policy has highlighted fields that require facts about the app. It is **not a completed privacy notice** and should not yet be used as the app's published policy in App Store Connect. See `OWNER-CHECKLIST.md`.

The Terms are in `index.html`; the privacy draft is in `privacy.html`. Each section uses ordinary HTML paragraphs beneath an `<h2>` heading. You can edit a file on GitHub with its pencil button, then commit the change. GitHub Pages will redeploy it.

After completing factual verification and legal review:

- Replace every incomplete disclosure and highlight with the final wording.
- Set truthful effective/updated dates in the page header and any relevant body text.
- Remove the draft notice and draft badge, and update the page's description.
- The legal draft pages currently contain `<meta name="robots" content="noindex, follow">`. You may remove it if you want search indexing. This tag does **not** make a published site private or prevent access.
- Check Terms, Privacy, Support, email links, section links, and the narrow-screen layout on the deployed site before adding URLs to the app or App Store Connect.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Terms of Use and the website's opening page |
| `privacy.html` | Privacy Policy draft |
| `support.html` | Support contact and help for common issues |
| `styles.css` | Shared desktop, mobile, and print styles |
| `README.md` | These setup instructions |
| `OWNER-CHECKLIST.md` | Remaining publication work |

All website links are relative, so the same package works at a GitHub project address or a custom domain. There are no external fonts, analytics scripts, forms, cookies, or browser-storage code in this package. GitHub Pages logs and stores visitor IP addresses for security, as explained in [GitHub's Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection). The privacy draft includes this website-specific disclosure. All uploaded files in a public repository will be publicly readable.

## Checks performed

The HTML structure, all local file references and section links, section counts, and repository-relative navigation were checked. Mobile, reduced-motion, keyboard-focus, and print styles are included. The in-app browser blocked opening the local file, so visual browser testing was not completed. Use the local preview steps above and check the deployed pages on your phone before launch.

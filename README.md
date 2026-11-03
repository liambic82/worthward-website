# Worthward website

Static introduction, support contact and privacy policy for Plowden Digital. Prepared September 19, 2026. This package is separate from the Android repository. It does not alter the app or backend.

## Preview

Open `index.html` in a browser. Both pages also work from a subdirectory on GitHub Pages. No installation, API keys, dependencies or build step is required.

Local checks passed for page structure, asset references and internal links/anchors. Automated browser rendering could not run because the browser runtime download timed out. Before publishing, preview both pages on desktop and at a narrow phone-sized window, including enlarged text.

## Publish with GitHub Desktop

1. In GitHub Desktop, create a new repository named `worthward-website`. Choose a local folder separate from `shift-pay-calculator`.
2. Copy this package's contents into that repository so that `index.html`, `privacy.html`, `styles.css` and the `assets` folder are at its root. Do not put the ZIP itself in the repository.
3. Commit with summary `Add Worthward support website and privacy policy`.
4. Choose **Publish repository**, make this website repository public, and publish. It contains only public website files. No need to make the Android repository public.
5. On GitHub, open the website repository's **Settings → Pages**. Select **Deploy from a branch**, choose the repository's main branch, choose **/(root)**, and Save.
6. Wait for GitHub Pages to display the published site link. Open that exact URL, then use the site's Privacy link. Check both in a signed-out/private browser window.
7. Use the full public `privacy.html` URL in Play Console. The app still needs a privacy link or policy text added in a later source overlay. Send the actual Pages URL back so the link can be wired accurately.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Publication and maintenance notes

- The home page links to the public Google Play listing for `com.mplowden.worthward`. The November 3, 2026 refresh explains verified core features, the optional one-time Pro purchase, and a clearly labeled illustrative gross-pay calculation.
- The policy includes the owner-approved limit of 12 months after resolution for ordinary support emails. Apply a regular mailbox cleanup process and handle privacy requests through the public support address.
- Hosted AI is unavailable as checked September 19, 2026. Update the policy before enabling it.
- Cloud log retention is based on the supplied 30/400-day configuration; unacknowledged purchase messages have seven-day retention. Purchase revocation hashes have no automatic expiry in the reviewed server code.
- The owner has not separately answered whether independently configured database backups, manual exports or other processing exist. If any do exist beyond the reviewed setup, add their handling before publishing. This site makes no blanket promise that no additional copies exist.
- The privacy policy is based on the supplied app/server source, the provided cloud settings and official SDK documentation. It is not a certification that Google Play has accepted the declarations. Data safety, audience and country selections remain separate Play Console tasks.
- The logo reuses paths from the app's `ic_worthward_foreground.xml`, adapted into SVG. The site has no scripts, forms, external fonts, analytics or tracking cookies. GitHub's hosting logs are disclosed.
- Do not upload private source archives, audit drafts, credentials or customer records to this website repository.


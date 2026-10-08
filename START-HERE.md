# MARK STREBEN — FINAL MASTER WEBSITE

This is the complete static website. **Keep every file and folder together.** Do not upload only `index.html`.

## A. Put it on GitHub (no coding)
1. Download `MARK-STREBEN-FINAL-GITHUB-VERCEL.zip` and double-click to unzip it.
2. Sign in at https://github.com and select **New repository**.
3. Name it `mark-streben-private-edition`, select **Private** if you wish, then create it.
4. Choose **uploading an existing file** (or **Add file → Upload files**).
5. Open the unzipped `MARK-STREBEN-FINAL-GITHUB-VERCEL` folder, select **all files and folders inside it**, and drag them onto GitHub's upload page. Make sure `index.html`, `vercel.json`, `assets`, `art`, and `qr-codes` are at the repository root.
6. Click **Commit changes**. If the GitHub browser upload does not accept folders, use GitHub Desktop to publish the unzipped folder instead: https://desktop.github.com/ .

## B. Connect GitHub to your EXISTING Vercel website
**Important: use the existing project, not a new project.** The QR codes already point to `https://mark-streben-private-edition-vercel.vercel.app`.
1. Go to https://vercel.com/dashboard and open the project serving that address.
2. Go to **Settings → Git** and connect the GitHub repository (if the project has no repository yet). Depending on your existing connection, you may need to disconnect the old repo first or import the repository and move the domain to the new project. Do not delete the existing site until the replacement is verified.
3. In **Settings → Build and Deployment**, choose **Framework Preset: Other**; root directory `./`; no build command; no output directory override.
4. Deploy from the `main` branch. Check **Deployments** for the new successful production deployment.
5. Test the homepage, `/collection`, `/language`, `/in-context`, `/patronage`, `/atomic-archive`, and scan at least two QR codes with a phone.

## C. Updates later
Edit or replace files in the same GitHub repository, commit changes, and Vercel will automatically deploy them.

## Publishing checks
- 17 entries include contextual installation imagery, not necessarily 17 separate authenticated artworks.
- Confirm catalogue names, sizes, dates, image rights, and the enquiry address.
- The patronage page does **not** claim HSBC or any named bank/fund invested. Add such claims only with documentation and permission.
- QR codes are permanently tied to the current Vercel domain. If you change the domain, regenerate the QR PNG files before printing.

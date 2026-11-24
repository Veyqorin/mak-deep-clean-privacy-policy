# Mak Deep Clean — Privacy Policy Website

This folder contains the standalone, responsive Privacy Policy website for **Mak Deep Clean** (`com.mak.deepclean`), ready to be hosted on **GitHub Pages** without any build step, backend server, or external JavaScript frameworks.

## Files
- `index.html` — Complete standalone HTML page with embedded CSS and lightweight JavaScript (dark navy/blue theme, light/dark toggle, sticky desktop TOC, collapsible mobile jump menu, and all 15 legal sections).
- `README.md` — Deployment and pre-publishing instructions.

## Before Publishing (Required)
Open `index.html` and replace the clearly marked placeholders in **Section 15 (Contact Information)**:
1. `[INSERT DEVELOPER OR PUBLISHER NAME]` — Your name or publisher name as shown on Google Play.
2. `[INSERT SUPPORT / PRIVACY EMAIL ADDRESS]` — A monitored email address for privacy inquiries (required by Google Play).
3. `[INSERT POSTAL ADDRESS OR REMOVE LINE]` — Optional; include if required by your jurisdiction, or remove that bullet item.
4. Remove the yellow `"Action Required Before Publishing"` notice wording once your contact details are filled in.

## How to Deploy on GitHub Pages

### Option A — Dedicated Public Repository (Recommended for Clean URL)
1. Create a new **public** repository on GitHub (for example, `mak-deep-clean-privacy`).
2. Upload `index.html` from this `privacy-website` folder to the root of that repository (on the `main` branch).
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
6. Wait 1–2 minutes for GitHub Pages to publish. Your URL will be:
   `https://<your-github-username>.github.io/mak-deep-clean-privacy/`

### Option B — Publish from an Existing Repository (`/docs` folder)
1. Copy `index.html` into a `/docs` folder in your repository and push to `main`.
2. In GitHub, open **Settings → Pages**.
3. Select **Deploy from a branch**, branch **`main`**, folder **`/docs`**, and click **Save**.

## Using the URL in Google Play Console & AdMob
- **Google Play Console → App content → Privacy policy:** Paste your live `https://...` GitHub Pages URL.
- **Google AdMob Console → Privacy & messaging:** Configure and publish your European regulations (GDPR) / US state regulations consent messages and link the same Privacy Policy URL.

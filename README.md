# Epic Dev Website

Live site: **https://devepictech-oss.github.io/epicdev/**

Root URL `https://devepictech-oss.github.io/` redirects to the site above.

## Fix 404

If the site shows **404**, enable GitHub Pages:

1. Open [repo Settings → Pages](https://github.com/devepictech-oss/epicdev/settings/pages)
2. Under **Build and deployment**, set **Source** to **GitHub Actions**
3. Go to [Actions](https://github.com/devepictech-oss/epicdev/actions) → **Deploy website from docs** → **Run workflow**

Wait 1–2 minutes, then open https://devepictech-oss.github.io/epicdev/

## AdMob app-ads.txt

AdMob needs the file at the **domain root**:

`https://devepictech-oss.github.io/app-ads.txt`

That file is published from the [`devepictech-oss.github.io`](https://github.com/devepictech-oss/devepictech-oss.github.io) repo, not from this project path.

A copy also exists at:

`https://devepictech-oss.github.io/epicdev/app-ads.txt`

## Deploy

Site files live in `/docs`. Pushing to `main` runs the GitHub Actions workflow and redeploys the site.

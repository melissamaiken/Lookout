# Lookout

Find nonprofits in Denver and Boulder that need your time, money, goods or skills.

This is a static site: one `index.html` file, no build step. GitHub Pages serves it as is.

## Publish with GitHub Pages

1. Create a repository (for example `lookout`) and upload `index.html` and this `README.md` to it.
2. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and click **Save**.
3. After a minute or two the site is live at `https://<your-username>.github.io/lookout/`.

To update the site, replace `index.html` in the repository. Pages republishes it automatically.

## What's in the page

- Organization and opportunity data lives near the top of the script in `index.html` (`ORGS`, `ROWS`, `ORG_INFO`, `RATINGS`, `DONATE`).
- "Your list" and "I did this" are saved in each visitor's own browser (localStorage). Nothing is sent to a server yet.
- Suggestions show a thank-you but aren't delivered yet. They need a form service (for example Formspree) wired in.

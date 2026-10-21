# Otonagi website

The Otonagi website: home, Privacy Policy, Terms of Use and Support. Plain HTML and CSS, no build step, no trackers.

## Before publishing

Search the files for `[` and replace every placeholder (they are highlighted yellow on the pages):

- `[SUPPORT EMAIL]`: the address users write to (in privacy, terms, support)
- `[LEGAL NAME]`: your name or company name
- `[COUNTRY]`: where you or your company are based (also sets the law in the terms)
- `[DATE OF PUBLISHING]`: in privacy and terms
- EU trader details: optional block, commented out at the bottom of `support.html`

Then remove the `todo` class from the filled-in spots (or leave it and delete the `.todo` rule in `style.css`).

## Publish on GitHub Pages

The site lives in the **otonagi** repository on the **mcederdev** account and is served at https://mcederdev.github.io/otonagi/.

1. Open the repository on GitHub and choose Add file › Upload files. Drag in `index.html`, `privacy.html`, `terms.html`, `support.html`, `style.css`, `favicon.svg` and the whole `images` folder (it keeps its name). Commit.
2. Settings › Pages should be "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Changes go live after about a minute.

All links in the pages are relative, so they work under the `/otonagi/` subpath. GitHub Pages serves `privacy.html` at `/otonagi/privacy` too.

## Links for App Store Connect

- Privacy Policy URL: https://mcederdev.github.io/otonagi/privacy
- Support URL: https://mcederdev.github.io/otonagi/support
- Marketing URL (optional): https://mcederdev.github.io/otonagi/
- Terms of Use (EULA): https://mcederdev.github.io/otonagi/terms. Also add this link to the app description, as Apple asks for subscription apps.

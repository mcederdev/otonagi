# Otonagi website

The Otonagi website: home, Privacy Policy, Terms of Use and Support. Plain HTML and CSS, no build step, no trackers.

## Details on the pages

- Support email: mcederdev@gmail.com. Maker: Magnus Cederberg, Sweden (the terms follow Swedish law).
- EU trader: Magnus chose "not a trader" (hobby), so no address or phone is shown.

## Publish on GitHub Pages

The site lives in the **otonagi** repository on the **mcederdev** account and is served at https://mcederdev.github.io/otonagi/.

1. Commit changes to `main` (Claude pushes updates directly; uploading through Add file › Upload files also works).
2. Settings › Pages should be "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Changes go live after about a minute.

When you change `style.css`, raise the number in `style.css?v=6` in all four HTML files (to `v=7` and so on) and upload them too, so browsers fetch the new stylesheet instead of a cached one.

All links in the pages are relative, so they work under the `/otonagi/` subpath. GitHub Pages serves `privacy.html` at `/otonagi/privacy` too.

## Links for App Store Connect

- Privacy Policy URL: https://mcederdev.github.io/otonagi/privacy
- Support URL: https://mcederdev.github.io/otonagi/support
- Marketing URL (optional): https://mcederdev.github.io/otonagi/
- Terms of Use (EULA): https://mcederdev.github.io/otonagi/terms. Also add this link to the app description, as Apple asks for subscription apps.

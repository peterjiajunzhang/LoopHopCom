# Loop Hop website

A static website with no build step or dependencies.

To preview locally, run this command in the website folder:

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173/` in a browser.

The public site deploys from this repository's `main` branch to https://loop-hop-com.vercel.app/.

The homepage links to the [App Store](https://apps.apple.com/app/id6815862724) and [Google Play](https://play.google.com/store/apps/details?id=com.loop.loophop). Android is labelled “Coming soon” while the public Play listing is unavailable. Once the production listing is publicly downloadable, change that label to “Get it on” and update its accessibility label; the destination URL stays the same. Production access approval alone does not establish a public Android release.

`app-ads.txt` is available at the deployment root (`/app-ads.txt`). Support is available from the Contact page, where the address appears as an email link label rather than printed page text.

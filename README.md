# CrossLangWord — marketing page

The public marketing page for
[CrossLangWord](https://github.com/NextGenPowerToys/crosslangword), and the
**Marketing URL** on the App Store and Google Play listings.

**Live page: https://nextgenpowertoys.github.io/crosslangword-marketing/**

Use that Pages URL, not this repository URL.

## Editing

`index.html` is the whole page, `style.css` the whole stylesheet, `img/` the
screenshots. Pushing to `main` republishes within a minute or so.

Screenshots are regenerated in the app repo
(`./tool/capture_screenshots.sh`) and copied here downscaled to ~520px wide
JPEGs. They are of the real app on real simulators — never mockups, and the
page says so.

## app-ads.txt does not live here

AdMob only reads `app-ads.txt` from the **root** of the developer domain, so a
project Pages site cannot host it. It belongs in the org-root repository
`NextGenPowerToys/nextgenpowertoys.github.io`, which serves it at
<https://nextgenpowertoys.github.io/app-ads.txt> — already in place, with
publisher id `pub-1407171162367131`.

## Claims on this page that have to stay true

* "Coming to the App Store" — replace with a real store link once the app is
  live, and not before. Never link to a store page that does not exist.
* Fifteen topics, four sizes, 220 puzzles, four shipping languages.
* No tracking, no advertising identifier, non-personalised ads, one-off
  purchase to remove ads. These mirror the
  [privacy policy](https://nextgenpowertoys.github.io/grosslangword-privacy/)
  and both must be updated together if the app changes.

# Wild Boar Studios — website

Static marketing + support + privacy site for Wild Boar Studios LLC, hosted on
Cloudflare Pages. Custom domain: **wildboarstudios.io**, attached directly to
the Pages project (DNS cut over 2026-10-15; previously GitHub Pages, which is
why this repo was named `wildboar-studio.github.io` before it was renamed).

## Structure
```
/                     Studio homepage (apps showcase)
/support/             Support page (Apple support URL for all apps)
/privacy/             The Wind Runner privacy policy
/selah/privacy/       Selah: Bible Memory privacy policy
/foody/privacy/       Foody privacy policy (draft, pre-release)
/flipfall/privacy/    Flip Fall privacy policy (draft, pre-release)
/yapit/privacy/       YapIt privacy policy (draft, pre-release)
/classtrack/privacy/  ClassTrack privacy policy (draft, pre-release)
/app-ads.txt          AdMob authorized-sellers (pub-1221342134311644)
/assets/              styles.css, logos, favicons, OG image
```

## Brand
Palette: forest green `#0F3D30`, rust `#B0561F`, cream `#F2EEE0`, ink `#1E1E1E`.
Primary logo `assets/logo-primary.png` (no "LLC"); legal variant `assets/logo-legal.png`.

## App Store links
The homepage app cards use `data-appstore="..."` placeholders on the "App Store →"
links. Replace the `href="#"` with the real App Store URL for The Wind Runner and
Selah once confirmed.

## Deploy
Commit to `main`; Cloudflare Pages publishes automatically (connected via the
Cloudflare GitHub integration, no build command — this is a static site).

# buildinelsalvador.com — your website package

Last updated June 2026.

## What's here
This folder is your whole website. `index.html` is the home page, with `membership.html`, `stories.html`, `about.html`, and `privacy.html` alongside it. Your photos and logo live under `assets/images/`, and all of your colors and fonts live in one file, `assets/css/tokens.css`.

This build is **English only** for now. Spanish can be added later as a `/es/` mirror of every page.

## Preview it locally
Just open `index.html` in your browser. All links and images use relative paths, so it works straight from the folder. (For a server-style preview you can also run `python3 -m http.server` inside this folder and visit `http://localhost:8000`.)

## Replace the photos
Drop your originals into `_source/photos-original/` (any format). The web-ready versions go under `assets/images/` in the right subfolder:

| Where it appears | Goes to | Recommended size |
|---|---|---|
| Hero photo strips | `assets/images/hero/` | min 1100px wide |
| Section photos | `assets/images/gallery/` | min 1200px wide |
| Logo | `assets/images/logos/` | vector (SVG) if possible |
| Testimonial cards | `assets/images/testimonials/` | min 800px wide |

Save them as `.webp` for speed (the same name as the file you're replacing).

## Change your colors or fonts
Everything is in `assets/css/tokens.css`. Editing that one file re-skins the whole site.

## The newsletter signup
The "Subscribe" forms point to your Substack at https://buildinelsalvador.substack.com/. Replace that URL in the page if your newsletter moves.

## Things to wire up before launch
- "Apply to join" and "Get in touch" buttons are placeholders. Point them at your real application form and contact email.
- The contact email used in the footer and privacy policy is `hello@buildinelsalvador.com` / `admin@buildinelsalvador.com`. Update if needed.
- Replace the low-res logo and partner placeholder content with final assets.

## Request a change
Message everybodyknowsyou.com with what you'd like changed, and we'll handle it.

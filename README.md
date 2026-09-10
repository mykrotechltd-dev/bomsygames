# Bomsy Games

Multi-page website for **Bomsy Games**, a Nigerian sports and educational platform and umbrella brand for a growing family of invented games, including **Bomsy Wall Tennis**, **Bomsy Mat Game** (BWTmatGame), and the upcoming **Bomsy Target Bowling**.

## Pages

- `index.html` — Home: hero (video background), Our Games overview, About, Why Bomsy, Gallery, News, Leadership, Partners, Newsletter, Footer.
- `wall-tennis.html` — Bomsy Wall Tennis: rules, origin story, tournaments, gallery, press.
- `mat-game.html` — Bomsy Mat Game: rules/zones, why it exists, gallery.
- `target-bowling.html` — Bomsy Target Bowling: "coming soon" page (no assets exist for this game yet).
- `styles.css` — shared styles across all pages. Edit once, applies everywhere.

No build step — open any page directly in a browser, or deploy the folder as-is (e.g. GitHub Pages).

## Assets

```
assets/
  bomsy-logo.jpeg            nav logo (general Bomsy Games mark)
  bomsy-logo-social.jpg      favicon / social share preview
  founder.jpg                Pastor Boma Willie-Pepple (Leadership)
  coaching-session.jpg       (legacy, still referenced nowhere as of this update — safe to remove later)
  target-board.jpg, session-setup.jpg, bomsy-report-issue-001.jpg
  wall-tennis/                logo, action shots, tournament/trophy photos, school outreach
  mat-game/                   coaching photos, tile close-up, gameplay, tournament podium, product shot
  videos/home-hero.mp4        homepage hero background video
```

Raw, unedited originals (WhatsApp exports, the source PDF, zip archives) live in `_raw/`, which is **git-ignored** — it stays on this machine for reference but never gets pushed. If you drop new photos/videos into this folder in the future, tell Claude and it will sort, rename, and wire them in the same way, then move the originals into `_raw/`.

## Assumptions made this update (please review)

- **"Who We Are" copy**: your draft cut off at "Founded on the belief that games can transform lives, Bomsy Games co…" — I completed it as: *"...continues to invent new ways to play — blending physical activity with simple, accessible tools so every game we build can reach more schools, more communities, and more players, wherever they are."* You mentioned wanting to fine-tune the digital-game angle yourself — this sentence is a placeholder for that, not final copy.
- **EEXSPORT**: appears repeatedly alongside Bomsy branding (co-branded banners, matching shirts) in the new photos, so it's listed as a text-only partner name on the Home page. Its logo image was *not* used, since that wasn't confirmed.
- **WIPO recognition**: "Bomsy Wall Tennis made the top 20 finalists out of 180 entries from 43 countries" is pulled from a screenshot you shared of a WIPO World IP Day social post — stated as fact since it's your own material, but not independently verified.
- **Bomsy Water Tennis**: mentioned only in your hero-video brief, with no photos or a dedicated page — it gets a one-line "also in development" mention on the Home page's Our Games section instead of its own page.
- Several near-duplicate WhatsApp photos were deduplicated (identical byte-for-byte copies were dropped; only visually distinct shots were kept).
- The largest photos were resized/compressed for faster page loads; originals are preserved in `_raw/`.

## Still open

- Bomsy Target Bowling has no photos, logo, or rules yet — page is a "coming soon" placeholder.
- Contact email and phone number in the footer are still bracketed placeholders.
- Newsletter form has no backend wired up.
- Six additional raw video clips (in `_raw/`) weren't reviewed/placed — say the word if you want a video gallery built from them.

## Content sources

- The Bomsy Wall Tennis Report (Issue #001, April 2025) and a Vision/Mission graphic you shared.
- [Vanguard News, "Bomsy Wall Tennis Births In Port Harcourt" (Sept 28, 2024)](https://www.vanguardngr.com/2024/09/bomsy-wall-tennis-births-in-port-harcourt/).
- Your "Bomsy Games — Website Structure & Content Framework" write-up (this update).

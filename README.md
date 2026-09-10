# Bomsy Games

Multi-page website for **Bomsy Games**, a Nigerian sports and educational platform and umbrella brand for a growing family of invented games: **Bomsy Wall Tennis**, **Bomsy Mat Game** (BWTmatGame), and **Bomsy Target Bowling**.

## Pages

- `index.html` — Home: hero (video background), Our Games overview, About, Why Bomsy, Gallery, News, Leadership, Partners, Newsletter, Footer.
- `wall-tennis.html` — Bomsy Wall Tennis: rules, origin story, tournaments, gallery, press & IP recognition (with video).
- `mat-game.html` — Bomsy Mat Game: rules/zones, "Learn to Play" explainer videos, gallery (incl. two short gameplay clips).
- `target-bowling.html` — Bomsy Target Bowling: how it's played, board photo, two demo videos.
- `styles.css` — shared styles across all pages. Edit once, applies everywhere.

No build step — open any page directly in a browser, or deploy the folder as-is (e.g. GitHub Pages).

## Assets

```
assets/
  bomsy-logo.jpeg              nav logo (general Bomsy Games mark)
  bomsy-logo-social.jpg        favicon / social share preview
  founder.jpg                  Pastor Boma Willie-Pepple (Leadership)
  bomsy-report-issue-001.jpg   report cover (News section)
  coaching-session.jpg, target-board.jpg, session-setup.jpg   legacy, unreferenced — safe to remove later
  wall-tennis/                 logo, action shots, tournament/trophy photos, school outreach, WIPO screenshot
    videos/ip-nomination.mp4   IP nomination video (Press section)
  mat-game/                    coaching photos, tile close-up, gameplay, tournament podium, product shot
    videos/explain.mp4         "Mat Game, Explained" — rules & expectations
    videos/overview.mp4        "The Full Bomsy Mat Game Experience"
    videos/clip-1.mp4, clip-2.mp4   short gameplay clips (Gallery)
  target-bowling/               practice-ball.jpg, board-setup.jpg
    videos/demo-1.mp4, demo-2.mp4   first-look demo clips
  videos/home-hero.mp4          homepage hero background video
```

All videos were compressed with ffmpeg (H.264, CRF 27–31) before upload — most shrank 40–75%; sizes now range from ~1–13MB rather than the original 5–30MB.

Raw, unedited originals (WhatsApp exports, the source PDF, zip archives, uncompressed videos) live in `_raw/`, which is **git-ignored** — it stays on this machine for reference but never gets pushed. Drop new photos/videos into this folder in the future and tell Claude — it'll sort, rename, compress, and wire them in the same way, then archive the originals.

## Assumptions made this update (please review)

- **"Who We Are" copy**: your draft cut off at "Founded on the belief that games can transform lives, Bomsy Games co…" — completed as a placeholder pending your own fine-tuning of the digital-game angle.
- **EEXSPORT**: listed as a text-only partner name (their logo wasn't confirmed for use).
- **WIPO / Intellectual Property recognition**: "Bomsy Wall Tennis made the top 20 finalists out of 180 entries from 43 countries" comes from your own WIPO World IP Day screenshot — stated as fact since it's your material, not independently verified. Labeled "Intellectual Property" per your latest note.
- **Bomsy Water Tennis**: still no photos or page — one-line "also in development" mention only.
- **Bomsy Target Bowling copy**: written from what the two photos and two videos show (a ball rolled across a flat board of numbered holes) — no official rules text was provided, so keep this description high-level and correct me if the mechanics are different.
- Near-duplicate WhatsApp photos were deduplicated (identical byte-for-byte copies dropped).

## Still open

- Contact email and phone number in the footer are still bracketed placeholders.
- Newsletter form has no backend wired up.
- One raw video (`_raw/WhatsApp Video 2026-09-10 at 00.11.35.mp4`) is still unidentified/unplaced — say what it is if you want it used.

## Content sources

- The Bomsy Wall Tennis Report (Issue #001, April 2025) and a Vision/Mission graphic you shared.
- [Vanguard News, "Bomsy Wall Tennis Births In Port Harcourt" (Sept 28, 2024)](https://www.vanguardngr.com/2024/09/bomsy-wall-tennis-births-in-port-harcourt/).
- Your "Bomsy Games — Website Structure & Content Framework" write-up.
- Your WIPO World IP Day screenshot and IP nomination video.
- Your BWTmat Game explain/overview videos, and target bowling photos/videos.

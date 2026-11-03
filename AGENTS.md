# Agent guidance for the Legends Classic site

These instructions apply throughout this repository, including automated pull-request reviews.

This is the public project landing page, separate from the builder, engine fix and launcher. Read `README.md`. `index.html` contains the page, styles and behavior; `img/` contains its images and `CNAME` names the site. GitHub Pages publishes the root of `main`; there is no build step or committed CI workflow.

Keep release, companion-version, roadmap and testing claims aligned with the corresponding code repositories and their release evidence. Use the `<!-- release round: update -->` markers when refreshing the page and inspect the rest of the page for repeated claims. Keep planned work distinct from shipped features, and same-PC/LAN checks distinct from internet or relayed co-op. Do not turn a networking goal into a tested guarantee.

Follow the image policy in `README.md`: existing gallery captures are identified as a player's own Legends Classic build. Only such captures are permitted; keep their captions and responsive image references accurate. No official logos, box/key art, cutscene stills, music, extracted game assets, decoded data, game-download links, secrets or personal paths/IPs/emails. Do not copy the private notes archive into the site. Keep the unofficial, non-commercial disclaimer and original page-code license.

Keep the page self-contained: no external scripts or fonts and no invented package/build toolchain. Preserve accessible headings, alt text, keyboard use and responsive layout; respect reduced-motion preferences if adding animation. Check changed links, anchors, image paths, release text and narrow-screen layout. State if visual/browser validation was unavailable; do not claim a deployment or live-site check from a local text review.

Review final diffs for incorrect claims, privacy/content leaks, broken navigation and accessibility regressions; give concrete file/line findings with triggers and consequences. Keep edits scoped and preserve unrelated work. Changes to `main` deploy the site: a review or draft does not authorize committing, pushing, merging, deploying or announcements.

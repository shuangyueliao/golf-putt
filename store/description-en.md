# Golf Putt — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Sink all 9 holes in as few strokes as possible. Drag back and release to
putt — only slow putts drop in. Mind sand, water, slopes and walls across
9 handcrafted mini golf holes.

(179 characters — within the 200 limit)

## Details

- Genre: Sports / Mini Golf / Casual / Puzzle-Physics
- Controls: Drag back from the ball and release (mouse / touch).
  Keyboard: ←/→ aim, hold Space to charge, release to putt.
- Features: 9 handcrafted holes (par 2-4, total par 29), sand that kills
  momentum, water with +1 penalty and replay from the previous spot, slope
  zones with constant pull, wall bounces that keep 85% energy, lip-out cup
  physics (fast balls skip over), full scorecard with vs-par scoring
  (Eagle / Birdie / Par / Bogey), best-round saving, mute button.
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5, zero
  external assets, works offline once loaded. No frameworks, no tracking.

## Tags
golf, mini-golf, putting, sports, casual, physics, arcade, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to fit, portrait-friendly, touch + mouse + keyboard)
- [x] No external links inside gameplay, no analytics
- [ ] Cover 16:9 and screenshots (export from live page)

## GameDistribution submission checklist
- [x] index.html only, self-contained (GD SDK loads only on gamedistribution/gd.games domains)
- [x] No external requests besides the guarded SDK loader
- [x] Works in iframe, mobile-friendly viewport, touch controls

## itch.io
- Upload zip (rename to golf-putt.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480x720, kind: html
- Pricing: $0 (donations optional)

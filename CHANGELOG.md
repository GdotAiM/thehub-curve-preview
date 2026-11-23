# Changelog

All notable changes to this project are documented in this file.

## 2.0.0 — 23/11/2026

Cinematic, scroll-driven v2 of the TheHub@TheCurve landing page, hosted as a public GitHub Pages preview.

- Replaced the earlier lounge hero with a full-screen, scrubbed and pinned 3D controller story driven by Three.js r170 and GSAP 3.13 with ScrollTrigger.
- The controller is built from procedural geometry (no third-party 3D models): exploded parts assemble, RGB edge and buttons light up, then a PRESS START climax.
- After the story, the controller docks and reacts to each page section (stations, booking, games, league, loyalty, trade-in, parties).
- Adaptive quality: pixel ratio is capped, rendering pauses when the tab is hidden, and if frame rate drops the pixel ratio is reduced and bloom can turn off.
- Added `prefers-reduced-motion` and no-JavaScript fallbacks, plus a mobile navigation menu.
- Share preview image (`og-image.jpg`) is included; Open Graph and Twitter image tags now use absolute GitHub Pages URLs, and `og:url` is set.
- Repository documentation, MIT licence, third-party notices, compressed screenshots, scroll recordings, and short looping hero-assembly previews added.

## 1.0.0

Original single-page website prototype:

- Station cards, booking-request flow, filterable sample games, and placeholder sections for leagues, loyalty, trade-ins, parties, and visit/contact information.
- A simpler Three.js lounge hero loaded from a CDN.
- No backend; booking requests were designed to be followed up by the shop rather than confirmed in the page.

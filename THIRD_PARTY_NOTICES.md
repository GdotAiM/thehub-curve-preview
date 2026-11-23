# Third-party notices

This project’s own source (see `index.html` and the documentation in this repository) is released under the MIT Licence in [LICENSE](LICENSE). The business name, branding, and content are not covered by that licence — see the licence section of the [README](README.md).

The page loads the libraries and fonts below from public CDNs at runtime. They are **not** vendored in this repository. Licence texts were read from the official sources named here on 23/11/2026. This file is a factual summary, not legal advice.

The 3D game controller is built in code from Three.js primitives (procedural geometry). There are no third-party 3D model, texture, or asset licences.

## Three.js r170 (including examples add-ons)

- **Used for:** WebGL scene, procedural controller, environment lighting, and post-processing bloom.
- **Loaded from:** `https://cdn.jsdelivr.net/npm/three@0.170.0/`
- **Modules referenced:** `three.module.min.js`, plus `examples/jsm` add-ons `RoundedBoxGeometry`, `RoomEnvironment`, `EffectComposer`, `RenderPass`, `UnrealBloomPass`, and `OutputPass`.
- **Licence:** MIT Licence.
- **Copyright:** Copyright © 2010-2024 three.js authors.
- **Source verified:** [LICENSE at the r170 tag](https://github.com/mrdoob/three.js/blob/r170/LICENSE) on github.com/mrdoob/three.js. The examples/jsm add-ons live in the same repository and are covered by that MIT licence.
- **Notice:** The MIT copyright and permission notice must be included in all copies or substantial portions of the Software. The full text is in the source linked above.

## GSAP 3.13 and ScrollTrigger

- **Used for:** Scroll-scrubbed timeline that drives the controller story, and section-triggered reactions. ScrollTrigger is registered as a GSAP plugin.
- **Loaded from:** `https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/gsap.min.js` and `https://cdn.jsdelivr.net/npm/gsap@3.13.0/dist/ScrollTrigger.min.js`
- **Licence:** Standard “No Charge” GSAP License, granted by Webflow. This is **not** an MIT or OSI open-source licence.
- **Source verified:** [Standard License](https://gsap.com/community/standard-license/) on gsap.com (also linked as https://gsap.com/standard-license). The page states an effective date of 30 April 2025 and a last-modified date of 30 May 2025. The same wording was used for this summary.
- **Grant (summary of the published text):** a non-exclusive, worldwide licence to use, reproduce, display, and implement GSAP Products solely for Permitted Uses — implementing or using them on any website, web application, or digital interface, including commercial projects, at no charge.
- **Main restriction (summary of the published text):** GSAP Products may not be used in tools that let users build visual animations without code in a way that encourages, induces, or materially assists a solution that competes with Webflow’s visual animation-building capabilities, without prior written consent. Reverse engineering to create such competitive products, and removing or altering proprietary notices or branding, are also prohibited.
- **Ownership:** intellectual property in GSAP Products remains with Webflow; the licence does not transfer ownership.
- **Amendments and terms:** the licence is incorporated into Webflow’s Terms of Service. Webflow may revise the licence by posting new terms; continued use of later GSAP releases constitutes acceptance. If you do not accept a revision you may not use versions released after its effective date, but may keep using earlier versions under the terms that applied to them (excluding later updates).
- This landing page is a website, which the published licence describes as a Permitted Use. The official FAQ on the same page states that commercial usage is covered under the standard licence.

## Barlow Condensed

- **Used for:** Display type (headings and brand lettering), loaded by CSS as `'Barlow Condensed'`.
- **Loaded from:** Google Fonts (`https://fonts.googleapis.com/css2?family=Barlow+Condensed:...`).
- **Licence:** SIL Open Font License, Version 1.1 (26 February 2007).
- **Copyright:** Copyright 2017 The Barlow Project Authors (https://github.com/jpt/barlow).
- **Source verified:** [ofl/barlowcondensed/OFL.txt](https://github.com/google/fonts/blob/main/ofl/barlowcondensed/OFL.txt) in the google/fonts repository.

## DM Sans

- **Used for:** Body type, loaded by CSS as `'DM Sans'`.
- **Loaded from:** Google Fonts (`https://fonts.googleapis.com/css2?family=DM+Sans:...`).
- **Licence:** SIL Open Font License, Version 1.1 (26 February 2007).
- **Copyright:** Copyright 2014 The DM Sans Project Authors (https://github.com/googlefonts/dm-fonts).
- **Source verified:** [ofl/dmsans/OFL.txt](https://github.com/google/fonts/blob/main/ofl/dmsans/OFL.txt) in the google/fonts repository, consistent with the [DM Fonts project README](https://github.com/googlefonts/dm-fonts/blob/main/README.md).

Under the SIL Open Font License 1.1, the fonts may be used, studied, modified, embedded, and redistributed, including alongside software, provided the fonts are not sold by themselves and the other OFL conditions are met. The fonts are not bundled in this repository; they are requested from the Google Fonts CDN when the page is viewed.

## CDN

jsDelivr and Google Fonts are used only as delivery networks for the works listed above. They are not additional licensed components of this repository.

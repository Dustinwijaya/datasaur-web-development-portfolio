# Validation — 31 October 2026

## Published site

- Tested in Chromium-based Microsoft Edge at 320, 375, 390, 414, 479, 767, 768, 991, 1024, 1280, 1920 and 2560 px.
- No horizontal document overflow or internal comparison-table overflow at any tested width.
- All three comparison columns and 22 check/cross icons remain inside the viewport. No feature labels overflow their cells.
- Desktop columns remain 480/592/592 px at 1920, 480/272/272 px at 1280, and 480/224/224 px at 1024.
- All 24 logo images load. Decorative repeats are hidden from assistive technology; the original four brands retain text alternatives.
- A complete animation cycle was observed: motion travels left to right, repeats and presents all four brands.
- Autoplay was rechecked after removing all playback controls. The published logo strip moved right immediately after load without clicking. No Pause/Play elements remain.
- Automatic motion stays off when reduced motion is requested.
- No page JavaScript errors were observed during these checks.

## Portable files

- HTML/CSS, local artwork and fonts are included.
- The layout matches published section and comparison geometry at 1920, 1280, 1024 and 375 px, within one pixel.
- The portable page makes no external asset requests. Logo motion uses CSS keyframes; the published site uses native Webflow Interactions.
- Full-page previews were refreshed from the published page at 1920, 1280, 1024 and 375 px.

## Intentional differences and limits

The continuous logo strip without visible controls and the mobile comparison layout are deliberate refinements requested during review. The mobile table dimensions differ from the supplied static reference. Removing the playback controls restores the logo section to its reference heights: 278 px at 1920/1280 and 180 px at 1024/375. Desktop table dimensions and original content are retained.

Earlier checks covered the supplied copy, icon values, image/font loading, native product disclosures, footer and video links. This revision adds focused responsive and motion checks, followed by an autoplay-only verification at 1920, 1280, 1024 and 375 px; it does not represent a new independent pixel-diff certification.

The sandbox endpoint is accessible, but its Designer canvas was not verified in an anonymous automated session. Physical-device Safari, Firefox and a complete screen-reader audit remain untested. WebKit automation was unavailable in this environment. The free-plan Webflow badge remains visible.

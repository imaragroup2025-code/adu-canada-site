# ADU Canada — Vercel Static Deploy (Text-Only Conversion)

This repository is a cleaned static deploy of an existing SPA build.
Goal: keep images and layout; remove Atlanta/GA/county references and rebrand to ADU Canada.

## Included
- /index.html (SPA shell)
- /assets/css/index.css
- /assets/js/index.js (patched text strings)
- /assets/js/runtime-extra.js (only if needed; safe to delete if unused)
- /assets/analytics/plausible.js (configured for aducanada.com)
- /assets/images/adu/ (place your image files here if you want local hosting)

## Notes
- The JS bundle referenced Atlanta + GA + county dropdown values. Those strings were replaced with Toronto/ON and GTA municipalities.
- If anything looks off, revert the GA->ON global replacement and switch to only ", GA" -> ", ON".

## Deploy
Import repo into Vercel → Framework: Other → Build: none → Output: .

# ADU Canada — Static SPA (Vercel) v5

## What changed
- Homepage hero copy updated to the Rational/Proven/Certain narrative
- CTAs updated: Start Your Build / Get Your Price
- Models renamed: Reform One / Reform Duo / Reform Series
- "Why REFORM?" updated to "Why This Works" with rational proof points (scope + estimating)
- Email set to sales@aducanada.com
- Prices increased +30% (USD)

## Images / Gallery troubleshooting
This build loads images from `/images/<filename>` (repo root folder).

If your Gallery does not reflect image updates:
1) Verify the image exists at: https://YOUR-DEPLOYMENT/images/hero-adu.png (and others).
   - If 404: your `/images` folder is not at repo root.
2) If the URL loads but shows the OLD image:
   - Hard refresh (Ctrl+F5) or try Incognito (browser cache)
   - Vercel/CDN may cache same-filename images; easiest fix is to rename the image file
     and update the string in `assets/js/index.js`.

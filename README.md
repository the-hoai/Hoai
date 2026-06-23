# HOAi Master Command Center - v10.3-qc-hardened

QC-hardened production build.

## Verified runtime table
| Length | Comfortable | Sweet | Max |
|---|---|---|---|
| 8s |30-38|34-36|40+|
| 10s |40-48|44-46|50+|
| 12s |48-58|52-56|60+|
| 15s |58-67|62-66|70+|
| 20s |78-92|82-88|95+|
| 30s |120-140|125-135|145+|

15 sec is default and highest-performing. Generator output verified in-band 468/468 across all ideas x runtimes.

## QC fixes
Syllable over-max & under-min eliminated, clipboard fallback, accessibility (aria/keyboard/skip link/focus), defensive import, empty-state messaging, HTTPS-guarded service worker, manual-draft id fix.

## Deploy
Upload folder to HTTPS host (Netlify/Vercel/GitHub Pages/Cloudflare Pages). iPhone: Safari > Share > Add to Home Screen.

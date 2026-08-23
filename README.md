# TON YIN / WooHua Taiwan — Official Website

Production target: `https://woohuataiwan.com`

## Non-negotiable project requirements

- Use only brand, product, company and visual information supplied or explicitly confirmed by WooHua / TON YIN.
- Do not invent tea origins, elevations, tasting notes, awards, certifications, biographies, production methods or commercial claims.
- Brand front: **TON YIN™ / 堂印**. Company layer: **WooHua Co., Ltd.**
- Core brand language: **SOIL · CRAFT · TIME · MOUNTAIN**.
- Core craftsman story: 李宏堂, more than 30 years of tea-roasting experience, known in the trade as 「堂哥」.
- Primary premium audiences: Taiwan and the United States.
- No new recurring website subscription or hosting fee may be introduced without explicit approval.
- Existing `woohuataiwan.com` domain ownership and Google Workspace email must remain intact.
- DNS changes must never remove or overwrite existing Google Workspace mail records (MX/SPF/DKIM/DMARC or verification records) without explicit verification.
- Production site must use HTTPS.
- First release is a static informational brand website: no user accounts, payment handling, advertising trackers, analytics, third-party embeds or web contact forms.
- No passwords, API keys, DNS credentials, mail credentials or other secrets may be committed to this repository.

## Current source

The deployable static site is maintained in `/docs`.

Files named `index.html` and `styles.css` at the repository root are retained as
an early design snapshot and are not published by GitHub Pages. Make production
changes only in `/docs`.

## Release process

1. Build and review in the private source repository.
2. Verify copy and all supplied media against source materials.
3. Test desktop/mobile rendering, navigation, language switching and accessibility basics.
4. Create a temporary deployment/preview and validate HTTPS.
5. Back up and verify current DNS records before any production DNS change.
6. Connect `woohuataiwan.com` only after preview acceptance.
7. Re-test both website and `tonyin@woohuataiwan.com` mail flow after DNS propagation.

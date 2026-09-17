# ShieldCall AI — Landing Page

Marketing landing page for **ShieldCall AI**, the AI-powered call screener with Ghost Mode.

**Live site:** https://shieldcallai.mdaics.org/

## What is here

- `index.html` — the full landing page (hero with Ghost Mode phone mockup, feature cards, how-it-works, download section, footer)
- `styles.css` — all styling, dark navy + teal brand theme, mobile responsive
- `assets/qr-ios.png` / `assets/qr-android.png` — QR codes for the App Store and Google Play listings

## Store links and QR codes

The App Store / Google Play badges and both QR codes are currently **placeholders**. The QR codes encode placeholder URLs:

- iOS: `https://apps.apple.com/app/shieldcall-ai/id000000000`
- Android: `https://play.google.com/store/apps/details?id=ai.shieldcall.app`

When the real listings go live: replace the `href="#"` badge links in `index.html` and regenerate the two QR PNGs with the real store URLs, then redeploy.

## Deployment

- Static site hosted on Vercel (project `shieldcallai-landing`), auto-built from this repo's `main` branch.
- Custom domain `shieldcallai.mdaics.org` with a CNAME in IONOS pointing to `cname.vercel-dns.com`.

## Contact

contact@mdaics.org

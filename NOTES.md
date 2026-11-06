# ZaibaTech-Website notes

- Site: `index.html`, `privacy/`, `terms/`, `404.html`, shared `assets/site.css`, `assets/i18n.js`, `assets/logo.svg`, self-hosted fonts in `assets/fonts/`; `CNAME` = www.zaibatech.com. Host: GitHub Pages, repo mirahimi500-ai/ZaibaTech-Website (branch main).
- 2026-11-03: Hybrid tech design with light/dark toggle; brand "Zaiba Technologies"; drawn illustrations.
- 2026-11-03: Contact pop-up form via Web3Forms (key for support@zaibatech.com only). FormSubmit was unreachable. Email addresses removed from the page; only the "SiraatOne apps" contact card kept.
- 2026-11-03: Privacy Policy and Terms of Use (effective Nov 3, 2026); footer Privacy / Terms / App privacy policies (siraatone.com/privacy, kept as the single app-policy copy). Google Fonts removed; fonts self-hosted (Inter, Sora, JetBrains Mono - SIL OFL).
- 2026-11-03: Added 404 page, share image (assets/og-image.png 1200x630), favicon.ico, apple-touch-icon, logo-512.png, robots.txt, sitemap.xml, Organization/WebSite JSON-LD, skip-to-content link.
- 2026-11-03: 10 languages (en, ar, ur, id, tr, fa, ps, bn, fr, ms) via globe menu; RTL for ar/ur/fa/ps; UI strings in assets/i18n.js; legal translations in privacy/i18n/ and terms/i18n/ (English prevails). Form sends the visitor's site language. Translations by Claude - native-speaker review recommended.
- 2026-11-06: Added SiraatOne Azan for Windows (Microsoft Store) card + Windows in hero/services/form topics (10 languages); iOS card now full-width. Store link: https://apps.microsoft.com/detail/9PHZ87D2BW12 (verified: SiraatOne Azan).
- Tests: 0 page errors, no overflow 360-1280px in all 10 languages, text contrast >= 5.8:1 in both themes; real Web3Forms test delivered to support@zaibatech.com.
- To confirm: governing-law state in Terms (Pennsylvania). Policies not lawyer-reviewed.
- 2026-11-06: LIVE. GoDaddy DNS: 4x A @ 185.199.108-111.153, CNAME www -> mirahimi500-ai.github.io (MX/TXT untouched). GitHub Pages: main /(root), custom domain www.zaibatech.com, DNS check OK, http+https 200, Enforce HTTPS on.
- 2026-11-06: Live form test PASS (support@). GitHub verified domain PASS (keep TXT _github-pages-challenge-mirahimi500-ai). DMARC already present (GoDaddy default, p=quarantine) - do not add a second. DKIM/SPF/Zoho verification intact. Google Search Console (Domain property) verified; sitemap submitted (file 200 OK, Google fetch pending).
- 2026-11-06: privacy@zaibatech.com added to Privacy Policy sections 7 and 12 (all 10 languages); other pages stay email-free.
- Later (optional): native-speaker review (ps, fa, ur, bn); lawyer review of policies after PA LLC; refresh og-image to mention Windows.

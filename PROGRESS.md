# Progress

## 2026-09-25 — Initial site build

- Created a responsive, accessible static landing page.
- Used the approved KeepsiPuff wordmark, mascot, favicon, and brand palette.
- Added GitHub/Vercel-ready static source files.
- Created the public GitHub repository and connected it to the Vercel project.
- Deployed the production site and attached the custom domain in Vercel; DNS still requires a Porkbun update.
- Added the approved cover for *Unclenched & Offline*, a focused book-sales section, and direct Amazon purchase actions using ASIN `B0HKVKWVZ1`.
- Removed public `puffy/puffies` wording and aligned the page with the current generic `puff/puffs` direction.
- Refined the palette hierarchy so coral leads calls to action and product presentation while bright teal remains a supporting accent.
- Replaced Porkbun's conflicting apex ALIAS with Vercel's two required A records while preserving the existing mail, verification, wildcard, and `color` subdomain records.
- Verified through Vercel that `keepsipuff.com` is correctly configured and attached to the production project, issued the managed certificate, and confirmed an HTTPS `200` response from the live production site.
- Created and visually checked an isolated muted-coral preview. The book-section background, hero sunburst, and large decorative mark use the muted tone; purchase and navigation actions retain the brighter coral. Confirmed the production stylesheet was not changed.

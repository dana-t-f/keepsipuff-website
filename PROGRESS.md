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
- Corrected the initial preview interpretation after Dana clarified that the later approved coral and logo—not a new salmon background treatment—were the intended comparison. Restored the original color placement, set the coral token to `#E86E50`, added the approved `#E98E70` hover tone, and replaced the older bright logo asset with the verified muted-logo export.
- After side-by-side review, restored the bright coral and original logo treatment on the private preview. Added the user-confirmed `@keepsipuff` profile links for Instagram, TikTok, YouTube, and Pinterest and checked the resulting footer layout. The production site remains unchanged.
- Dana authorized the social footer for the published website and requested removal of her email address to avoid unsolicited website email. Removed the visible address and the About-section `mailto:` action; the About action now leads to the social profiles.
- Published the update to `keepsipuff.com` and verified HTTPS `200`, all four social destinations, the social-profile accessibility label, and the absence of Dana's email address, `mailto:` actions, and legacy `puffy/puffies` wording.

## 2026-09-25 — Signup, series name, Etsy placeholder, and legal line

- Added a dedicated free signup section linking through the stable owned URL `https://color.keepsipuff.com/`, which forwards to the existing Flodesk form.
- Replaced the public-facing `Puff Breaks` label with the approved series name `Meanwhile, Color This` and updated the section anchor accordingly.
- Added an intentionally non-clickable printable-pack space that says the Etsy download is coming soon, without implying that the not-yet-live listing is available for purchase.
- Added the footer disclosure: `KeepsiPuff is a brand and registered trade name of Symbol & Spark LLC.`
- Preserved the bright coral/logo direction, all four social links, the Amazon book purchase links, and the no-public-email rule.
- Verified the new sections, call-to-action, responsive mobile layout, social footer, and legal line in a private local browser preview.
- Published the update through the connected GitHub-to-Vercel production path and verified `https://keepsipuff.com` returns HTTPS `200` with every requested element and no public email, `mailto:`, or legacy public naming.
- Corrected the signup after Dana clarified that Flodesk delivers a free coloring sheet, not a Color Auditions page. Matched the live Flodesk disclosure and call-to-action, and replaced the color-swatch mockup with the approved `The Receipt Is Longer Than the Errand` coloring-sheet preview.
- Published the correction and verified the live page, preview image, exact offer language, and absence of the obsolete Color Auditions wording at `https://keepsipuff.com`.
- Added a cream secondary hero button, `Get a free coloring sheet`, linking to the on-page signup section while preserving the Amazon purchase and About paths.
- Completed the footer copyright line as `© 2026 Symbol & Spark LLC.` using the existing dynamic year.
- Published the hero/footer update through GitHub and Vercel, then verified the live button target, button styling, rendered 2026 copyright, and unchanged Etsy coming-soon state.

## 2026-09-26 — Unpublished privacy, performance, and sharing preview

- Added a local `privacy.html` candidate using the existing KeepsiPuff header, footer, type, colors, and layout system.
- Kept all email addresses off the site. Privacy access, correction, and deletion requests are directed to replies to a received KeepsiPuff email and promise a response within 30 days.
- Replaced footer social text with bundled Simple Icons in accessible 44-pixel round buttons; no third-party icon request is made by the page.
- Added light-only color-scheme declarations to prevent browser dark-mode recoloring.
- Optimized the logo, book cover, mascot, and free-sheet preview while retaining their filenames; the four files now total about 1.5 MB rather than about 6.7 MB.
- Added the 1200-by-630 social share image and Open Graph/Twitter metadata, a 180-by-180 iPhone home-screen icon, `robots.txt`, and `sitemap.xml`.
- Changed only the repeated free-sheet eyebrow from `Meanwhile, Color This` to `Free coloring sheet`; the public series section retains `Meanwhile, Color This`.
- Left `Coming soon on Etsy` unchanged because no live listing URL has been provided.
- No commit, push, or Vercel deployment was made. The candidate awaits desktop/mobile approval and confirmation that replies to the delivery email reach a monitored inbox.
- Removed both decorative teal squiggles from the private hero preview after they read as stray lines inside the transparent mascot's upper-left opening and lower-right coil. The mascot image itself was not damaged or redrawn.

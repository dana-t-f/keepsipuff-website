# Decisions

## 2026-09-25 — Initial launch surface

- The initial site is a single-page landing experience focused on the KeepsiPuff universe and Puff Breaks.
- Existing approved brand assets are used without recreating the logo or mascot.
- Contact uses the confirmed Symbol & Spark email; no unverified social or shop URLs were invented.
- `keepsipuff.com` is attached to the Vercel project. Its external DNS provider remains Porkbun, so DNS configuration is a separate required step.

## 2026-09-25 — Product and color direction

- Use coral as the primary conversion and product color. Keep bright teal for smaller accents so the page stays lively without changing the KeepsiPuff visual center.
- Public character language uses lowercase `puff/puffs`; `puffy/puffies` is removed from website copy and asset naming.
- *Unclenched & Offline* is the first featured product and links directly to its verified Amazon ASIN, `B0HKVKWVZ1`.

## 2026-09-25 — Custom-domain routing

- Keep Porkbun as the authoritative DNS provider and point only the root website record to Vercel.
- Use Vercel's recommended dual apex A records, `216.198.79.1` and `64.29.17.1`.
- Preserve all unrelated Porkbun DNS records, including Google/MailerLite email records, verification records, wildcard routing, ACME challenges, and the `color.keepsipuff.com` ALIAS.

## 2026-09-25 — Muted-coral comparison

- Keep the current production design live while Dana reviews a separate corrected preview.
- Preserve the original layout and color placement. Replace the older bright coral with the later approved muted coral `#E86E50`, use approved light coral `#E98E70` for hover states, and use the approved muted primary-logo export.
- Do not introduce a separate salmon background treatment.
- Do not promote the preview to production without Dana's explicit selection.

## 2026-09-25 — Contextual logo-color working direction

- Preserve the KeepsiPuff logo's exact construction; color treatment may vary only between documented approved exports rather than ad hoc recoloring.
- Use the brighter treatment as the current website/default-retail direction because it reads as more graphic, adult, and broadly appealing.
- The muted treatment may remain an optional social/editorial presentation, including an existing muted Instagram avatar, where the softer appearance suits the surface. This is a working usage distinction, not a new controlling brand-master approval.
- Keep both treatments recognizable through consistent logo geometry, teal/coral structure, cream context, and unchanged KeepsiPuff naming.

## 2026-09-25 — Public contact path

- Use the KeepsiPuff Instagram, TikTok, YouTube, and Pinterest profiles as the website's public follow/contact path.
- Do not publish Dana's email address or expose a `mailto:` action on the KeepsiPuff website.

## 2026-09-25 — Public series, signup, and future printable pack

- `Meanwhile, Color This` supersedes `Puff Breaks` as the public-facing series name on the website; `Puff Breaks` remains an internal working name only.
- Use the stable owned URL `https://color.keepsipuff.com/` for the free printable coloring-sheet signup so the website does not depend on a changeable Flodesk destination URL.
- Reserve a visible printable-pack section now, but keep it non-clickable and label it `Coming soon on Etsy` until the listing is confirmed live.
- Use the exact website footer line `KeepsiPuff is a brand and registered trade name of Symbol & Spark LLC.` The separate publisher/imprint wording remains book-specific.
- These decisions supersede the initial-launch references to public `Puff Breaks` wording and an email contact path.
- The website offer must describe the actual Flodesk free coloring sheet and may not call it a Color Auditions page. Use the approved `The Receipt Is Longer Than the Errand` sheet as its preview.
- Keep the Etsy printable-pack placeholder for now. Replace its coming-soon state with the verified listing link once live; if the listing will remain unavailable for an extended period, hide the section instead of leaving a stale promise.
- Give the free coloring sheet equal hero-button visibility beside the first-book purchase path, while retaining the About text link.

## 2026-09-26 — Privacy contact and review gate

- Do not add a Tally form or publish a contact email address. People who receive a KeepsiPuff email may reply to it to request access, correction, or deletion of their information.
- Verify the Flodesk delivery email's reply-to path reaches a monitored inbox before publishing the privacy policy. This operational check is required even though the receiving address will not appear on the website.
- Keep `Meanwhile, Color This` on the public series section and use `Free coloring sheet` for the adjacent signup eyebrow so the two sections do not repeat the same label.
- Keep the Etsy placeholder unchanged until a verified listing URL is available.
- Treat all September 26 website work as a local review candidate. Do not publish until Dana explicitly approves the desktop and phone previews.
- Remove both hero teal squiggles because their placement behind the transparent mascot reads as image artifacts in the upper-left opening and lower-right coil. Do not alter the mascot artwork to solve this display issue.

## 2026-09-26 — Publication approval

- Dana's explicit `lets publish` instruction supersedes the local-review hold after she reviewed the corrected desktop and phone preview.
- Publish the approved candidate through the existing GitHub `main` to Vercel production path without adding a Tally form or exposing an email address.
- Keep a real Flodesk reply-path test as visible operational follow-up work. Publication does not claim that a reply was sent or received during this run.

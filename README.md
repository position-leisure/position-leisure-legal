# position-leisure-legal

**This repository serves redirects only. It contains no legal text, by design.**

The canonical Privacy Policy and Terms of Service for **Position: Leisure** — an AI-powered job search and application tracking platform operated by **AlgoAxiom LLC** — are published and maintained at:

- **Privacy Policy** — <https://positionleisure.com/privacy>
- **Terms of Service** — <https://positionleisure.com/terms>

Those two URLs are the documents. Nothing in this repo is.

## What this repo is for

The canonical home migrated to `positionleisure.com` on 2026-05-03 (ADR-074, in the private project repo). This repository remains only as a GitHub Pages **redirect shim**, so that cached email links, old bookmarks, and any listing still carrying a `position-leisure.github.io` URL keep resolving to the live documents.

`privacy-policy.md` and `terms-of-service.md` contain nothing but Jekyll front matter with a `redirect_to:` directive. The April 2026 policy text that used to live here was **removed on 2026-09-10**: two publicly readable copies of an operative legal document can disagree, and the stale copy is the one that bookmarks and search engines keep finding.

## ⚠️ Updating — do NOT edit the documents here

**There is no document in this repo to update.** To change the Privacy Policy or Terms of Service, edit the canonical copies in the `position-leisure-web` application:

- `src/pages/PrivacyPolicy.tsx`
- `src/pages/TermsOfService.tsx`

Those are what `positionleisure.com/privacy` and `/terms` serve. **Any policy text added to this repo becomes a second, competing version by definition** — that is exactly the problem the 2026-09-10 reduction removed.

The only edits that belong here are to the redirect targets themselves, if a canonical URL ever changes. Keep the YAML front matter on both `.md` files: the `redirect_to:` line is the entire mechanism, and deleting it silently turns a redirect back into a published page.

## Where these redirect URLs are referenced

Legacy `position-leisure.github.io` links may still exist in:

- The Position: Leisure Chrome extension's Web Store listing
- Outbound email footers (SendGrid templates)

The application UI and the extension itself point directly at `positionleisure.com/privacy` and `/terms`. These redirects exist for whatever still does not.

## Contact

For questions about these documents or data handling:

**AlgoAxiom LLC**
Steven Cantwell
4601 E. Douglas Ave. STE 150
Wichita, KS 67218
<algoaxiom.steve@gmail.com>

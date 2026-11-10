# HelioFlux patient journey: Claude handoff

Prepared 10 November 2026. Work on `review/patient-journey-assets-2026-11-10` in `kellylucas314-cpu/helioflux-journey`.

## Scope and status
This is a review draft, not a published update. Main and GitHub Pages have not been changed. Base commit: `5df2c7ac758f457e5b5d35c67e5dd4234f4abd63`. Existing historical files remain intact. Read this handoff before the older February specs: those specs are historical, not current scientific authority.

## What changed
- Replaces hidden slides with a continuous seven-section editorial story and native anchor navigation, no JavaScript required.
- Matches the visual language of https://helioflux.co/science.html and https://helioflux.co/timeline.html: navy, off-white, teal, fine rules and restrained typography.
- Integrates six illustrations: Maya/clinician hero, Maya preparing questions, research questions conversation, conceptual cell, evidence review, and next-steps conversation.
- Includes web-ready versions of all 13 final illustrations in `assets/`, with transparency and original dimensions. Original PNG masters were delivered separately in the complete asset ZIP; the repo WebP derivatives use quality 92 compression. Do not treat them as original masters.
- Maya is fictional, brown-skinned and South Asian-inspired, with dark wavy hair. Her clinician is fair-skinned and blonde. Fine blue linework, mostly unfilled clothing, very light sage and natural skin/hair color. Use light backgrounds, contain framing, no cropping hands or faces.
- Other assets are available for future layout work, not all crammed into this page.

## Scientific boundaries
Preserve explicit separation between care today and investigational technology. A changing lesion warrants clinical assessment; biopsy may be needed. Do not imply that HelioFlux replaces or delays standard care. Do not restore the old 100× earlier claim, 10-million/10,000-cell detection figures, five-minute scan promise, human cancer validation, treatment claims, or guaranteed outcomes.

The 2020 cell/mouse paper and the 2025 healthy-adult brain-activity paper do not establish human cancer diagnostic performance. Confirm study interpretation and current company details with Nirosha before public use. Study site, first indication, protocol, enrollment and timing remain unconfirmed in this draft. Product names QSense/LuminAI and technical descriptors should be reconfirmed against the current source of truth.

All artwork is fictional/conceptual. It is not patient evidence, authenticated hardware, measured data or a depiction of an available clinical service. Keep conceptual-image captions.

## QA and next steps
Static checks are recorded in QA.md. Browser-rendered desktop/mobile screenshots, zoom, keyboard traversal, screen-reader behavior, full accessibility audits and live source-link availability remain untested. Prior local browser access was blocked; this is not a visual or WCAG certification.

1. Review this branch locally and compare it with the current science/timeline pages.
2. Test at 390px, 768px and 1440px, 200% zoom, keyboard only and reduced-motion setting. Check image transparency/edge washes on off-white, layout balance, long text and focus visibility.
3. Have Nirosha review all scientific claims and captions, and Kelly review character appearance/art direction.
4. Confirm contact email, source links, navigation URLs and product wording.
5. Only after explicit approval, merge/deploy. Do not publish, change Pages configuration or alter the archived roadmap as part of this handoff.

The roadmap repo was archived separately at Kelly's request; she wanted its public page left up. Leave it alone.

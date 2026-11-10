# QA: HelioFlux patient story

## Passed static checks
- PASS: balanced HTML tags
- PASS: unique IDs
- PASS: all internal links resolve
- PASS: all images local and present
- PASS: all images have alt and intrinsic dimensions
- PASS: one H1 and seven story sections
- PASS: all sections visible without JavaScript
- PASS: English language and responsive viewport
- PASS: skip link and focus indicator
- PASS: reduced motion supported
- PASS: fictional patient disclaimer retained
- PASS: clinical care safeguard retained
- PASS: human performance limitation retained
- PASS: evidence separation retained
- PASS: source links retained
- PASS: no hidden slide system or fixed overlays
- PASS: normal-text palette pairs >= 4.5:1
- PASS: large headline accent >= 3:1

## Calculated contrast ratios
- Body ink on paper: 14.15:1
- Muted notes on paper: 5.93:1
- Links on paper: 5.45:1
- Hero text on navy: 12.95:1
- Hero notes on navy: 9.99:1
- Hero eyebrow on navy: 7.89:1
- Primary CTA text on blue: 5.28:1
- Large accent headline on navy: 5.28:1

## Not run
Rendered desktop/mobile, browser zoom, keyboard focus order, screen-reader behavior, browser accessibility auditing, and live source-link availability checks of this draft were not run. The supported cloud browser rejected the local file URL because file: is not an allowed protocol. No route around that denial was attempted. Reference pages were visually inspected successfully. Static results do not constitute a full WCAG or visual pass.

## Scope
Only local files changed. No public publication, push, or deployment. Original clinical/scientific copy retained. The structure changed from hidden screens to a continuous story with native anchor navigation, requiring no JavaScript.

## Final illustration integration, 10 November 2026
Rechecked: six local image references, intrinsic dimensions, alt text, unique IDs, anchor targets, one H1, seven sections and absence of JavaScript. All passed. All 13 WebP derivatives retain alpha and original dimensions. No new rendered browser tests were run. Review-branch push does not deploy the draft.

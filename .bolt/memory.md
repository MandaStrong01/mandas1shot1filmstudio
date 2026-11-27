# Project memory

## Product intent & audience

- Film studio / production tool web app (single-page, no cover/hero section)
- Appears to be a "1-shot" film studio concept — users generate or prepare a film and get a "Your film is ready" result
- Audience: creators/producers wanting a premium, polished production interface

## Brand personality & voice

- Premium, professional, polished
- Dark-and-gold luxury aesthetic ("like it but smarter and more professional")
- Editorial/modern feel with refined details

## Visual design & UX direction

- **Theme:** dark background with gold accents throughout
- **Exception:** "7-day free trial" button uses green color (original styling), not gold
- **Corners:** soft rounded corners (6–10px) on all elements — buttons, cards, inputs, player, boxes
- **Buttons:** gold gradient fills with soft glow; gentle hover lift and glow intensification; pill-shaped subscribe button
- **Inputs:** softer dark background, subtle focus glow, clear placeholders
- **Shadows:** deep natural shadows on cards/panels instead of flat gold outlines
- **Typography:** uppercase section labels with wider letter-spacing; lighter heading weights; tighter line heights for editorial feel
- **Header bar:** clean login/subscribe row; pill-shaped subscribe button with gold gradient
- **Components present:** preview player, "film ready" gold announcement box, summary bar, progress bar (gradient fill, rounded edges, subtle track), timeline, project cards, 7-day free trial button (green)
- **Interactions:** smooth color transitions on hover for chips, buttons, links — page should feel "alive"
- **Cards/panels:** rounded corners with subtle panel background

## Decisions, constraints & rationale

- User liked existing dark-and-gold theme — keep it; refinement not redesign
- Sharp 3px corners were replaced with softer radii for a premium feel
- Flat gold outlines replaced with layered shadows for depth
- 7-day free trial button explicitly reverted to original green color per user request; rest of palette remains gold
- Build verified passing after styling changes

## Open questions & assumptions

- Exact feature set beyond "film ready" workflow is inferred from UI components
- No explicit brand guidelines or design tokens documented yet
- Responsive behavior and accessibility requirements not yet specified
- Green free-trial button may have specific shade/interaction details worth documenting if revisited
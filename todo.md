# AI Educational Website — Todo (v3: Visual Polish)

## v3 Plan — Visual Improvements

- [x] Add rounded corners to cards and buttons (hero card 16px, course/testi cards 12px, buttons 6px)
- [x] Add box shadows for depth (hover glow on course cards, ambient on testimonials, hero float)
- [x] Add gradient accent to hero headline "Already Here." (gold → light gold via background-clip: text)
- [x] Add subtle section background alternation (How It Works → #0E0E0E)
- [x] Improve button hover states (gold glow shadow on primary, semi-transparent fill on ghost)
- [x] Add gradient overlay on course card images (::after linear-gradient to top)
- [x] Enlarge and reposition testimonial quote mark (4rem, display:block, 0.7 opacity)
- [x] Fix remaining "Synapse" brand name in testimonial copy → "NorthStar"
- [x] Commit and push to GitHub

---

## Plan

- [x] Define design system (colors, typography, spacing tokens)
- [x] Create `index.html` as a single-file site (HTML + CSS + JS)
- [x] Build Nav — sticky, blurs/shrinks on scroll
- [x] Build Hero section — full-viewport, bold headline, two CTAs, placeholder image card
- [x] Build Stats bar — 3 key metrics (courses, learners, completion rate)
- [x] Build Featured Courses section — 3-column card grid with placeholder images and hover effects
- [x] Build How It Works section — 3 numbered steps
- [x] Build Testimonials section — 2×2 quote cards with avatar placeholders
- [x] Build CTA Banner — full-width accent color block
- [x] Build Footer — 4-column layout with link groups
- [x] Add scroll-based fade-in animation (IntersectionObserver)
- [x] Add responsive layout (stacks to single column on mobile)
- [x] Verify in browser — all sections render correctly
- [x] Verify mobile responsiveness
- [x] Verify scroll animations (nav shrink, section fade-in)
- [x] Address any user-requested revisions — none requested

---

## v2 Plan — NorthStar Rebrand

- [x] Copy `NorthStar.jpg` from Downloads into the project folder as `assets/logo.jpg`
- [x] Update color palette: replace mint green (`#6EE7B7`) with gold accent (`#C8A84B`) and darker gold hover (`#B8943A`)
- [x] Replace text logo "Synapse." in Nav with `<img>` of NorthStar logo (white-inverted via CSS filter)
- [x] Replace text logo "Synapse." in Footer with `<img>` of NorthStar logo
- [x] Update site `<title>` to "NorthStar — AI Education"
- [x] Update Hero brand label to "NorthStar AI Learning"
- [x] Update footer tagline to "Care, Comfort and Plan — AI education built around you."
- [x] Commit and push changes to GitHub

---

## Review

**v1 (Initial build):** Single-file AI educational website with 8 sections — Nav, Hero, Stats, Courses, How It Works, Testimonials, CTA Banner, Footer. Dark theme, mint accent (`#6EE7B7`), Inter typeface, IntersectionObserver animations, CSS Grid responsive layout. No frameworks.

**v2 (NorthStar rebrand):** Added `assets/logo.jpg`; applied CSS `filter: brightness(0) invert(1)` to render it white on the dark background. Replaced mint palette with NorthStar gold (`#C8A84B` / `#B8943A`). Updated page title, hero label, footer tagline, and copyright to NorthStar branding. All changes minimal — no structural rewrites. Pushed to https://github.com/tommyhtown/claude-code-demo.

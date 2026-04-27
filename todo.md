# AI Educational Website — Todo (v2: NorthStar Rebrand)

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

- [ ] Copy `NorthStar.jpg` from Downloads into the project folder as `assets/logo.jpg`
- [ ] Update color palette: replace mint green (`#6EE7B7`) with NorthStar navy (`#1B3A6B`) and gold accent (`#C8A84B`)
- [ ] Replace text logo "Synapse." in Nav with `<img>` of NorthStar logo
- [ ] Replace text logo "Synapse." in Footer with `<img>` of NorthStar logo
- [ ] Update site `<title>` to "NorthStar — AI Education"
- [ ] Update Hero brand label and headline to reflect NorthStar identity
- [ ] Update footer tagline to "Care, Comfort and Plan"
- [ ] Commit and push changes to GitHub

---

## Review

**What was built:** A single-file AI educational website (`index.html`) with no external dependencies beyond Google Fonts and picsum.photos placeholder images.

**Sections delivered:** Nav, Hero, Stats bar, Featured Courses (3-card grid), How It Works (3-step), Testimonials (2×2 grid), CTA Banner, Footer.

**Design approach:** Dark-mode first (`#0A0A0A` background), mint green accent (`#6EE7B7`), Inter typeface, hairline borders, generous whitespace — minimal agency aesthetic throughout.

**Interactions:** Sticky nav shrinks on scroll via a CSS class toggle; all sections fade in via IntersectionObserver. Both are lightweight, no-framework implementations.

**Responsiveness:** CSS Grid `auto-fit / minmax` handles all layout reflow. Tested breakpoint at 900px — all columns stack cleanly.

**Changes kept minimal:** No frameworks, no build step, no unnecessary abstractions. One file, open and run.

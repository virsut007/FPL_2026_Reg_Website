Freshers' Premier League 2026 — BITS Pilani
A single-page event landing site for the Freshers' Premier League (FPL) 2026, organized by the Sports Union Executive Committee at BITS Pilani, Pilani Campus.

FPL is the annual inter-wing sports tournament for first-year students at BITS Pilani. This page serves as the central hub for event information, sport-wise registration links, and organizer contact details.
Features

Animated dark-themed UI with gold accents matching a sports/premiere aesthetic
Event date and registration deadline tiles (with urgency highlighting)
Clickable registration links for all 9 sports (including Esports for the first time)
Contact section listing Sports Union organizers with phone numbers
Fully responsive, works on mobile and desktop
Pure HTML + CSS, no JavaScript or external dependencies beyond Google Fonts

Customization
All visual variables are defined as CSS custom properties at the top of the <style> block and can be easily changed:
Registration form links (Google Forms URLs) are embedded directly in each <a> tag and can be swapped out as needed.

Stack
LayerTechnologyMarkupHTML5StylingVanilla CSS3 (custom properties, grid, clip-path, keyframes)FontsGoogle Fonts CDN — Bebas Neue, Barlow Condensed, BarlowScriptingNoneDependenciesNone (zero npm, zero bundler)

Visual Effects
EffectImplementationBackground gridbody::before — repeating linear-gradient at 60px intervalsTop glowbody::after — radial-gradient ellipse, fixed positionLogo pulse@keyframes pulse-ring cycling box-shadow opacityStaggered entrance@keyframes fadeUp / fadeDown with incremental animation-delay per sectionGold text gradient-webkit-background-clip: text + linear-gradient on <h1>Chevron CTA.sport-link::after pseudo-element, revealed on :hover via opacity transitionYear badge skewclip-path: polygon(...) for parallelogram shape

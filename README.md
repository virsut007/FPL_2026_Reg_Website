Try it out over here : https://fpl2026.vercel.app/

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


Major Fixes and Improvements:
1)Fixed slow redirection to google forms
Problem:
Earlier after clicking on sport, it took a long time to get redirected to the registration google form.
fix:
Added dns prefetch and preconnect to google forms domain, so the browser establishes a connection in the background before the user clicks.
Forms also now open in a new tab instead of navigating away, which feels significantly faster.



Customization
All visual variables are defined as CSS custom properties at the top of the <style> block and can be easily changed:
Registration form links (Google Forms URLs) are embedded directly in each <a> tag and can be swapped out as needed.


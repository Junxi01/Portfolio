A1: Responsive Portfolio in HTML and CSS — Readme
=================================================

Name: Junxi Chen
Email: chen161402@gmail.com
Course / Section: ________

Estimated points completed (out of 10 +1 bonus): 10/10 (+1/1)

Files
-----
- index.html (root)
- about.html
- projects.html
- contact.html
- validations.html (how to capture validator screenshots)
- styles.css
- assets/images/* (placeholder images; replace as desired)
- assets/docs/* (design docs)
- validation/*.jpg (REPLACE placeholders with real validator screenshots)

Highlights / Embracing the spirit
----------------------------------
- HCI-driven front end: accessibility-first markup (skip link, clear focus rings, ARIA, reduced-motion support) and responsive CSS Grid/Flex tuned for readability.
- Real project integration: featured the SuperNova Figma prototype with a concise case-style summary and clear calls to action (Prototype / Design Doc).
- Clean, portable code: mobile-first, semantic HTML with a CSS-only nav; consistent design tokens and relative paths for reliable grading environments.

Checklist: Basic HTML content (pick at least 3)
-----------------------------------------------
- [x] Image(s) with descriptive alt text
- [x] Headings & paragraph text
- [x] Links to external pages (GitHub, LinkedIn)
- [x] Multiple pages with navigation
- [x] Semantic tags (<header>, <nav>, <main>, <footer>)
- [x] Custom icons (Material Icons)

Checklist: Basic CSS styling (pick at least 2)
----------------------------------------------
- [x] Spacing (padding/margins) for readability
- [x] Custom colors & link styles
- [x] Custom Google Font (Inter)
- [x] Responsive layout (Grid/Flex)
- [ ] (Optional) Bootstrap helpers — not used

Advanced feature(s) (at least 1)
--------------------------------
- [x] More complex layout (responsive Grid + sticky header + CSS-only mobile nav)
- [x] Accessible table with caption and scope attributes
- [x] Contact form with labeled fields and required attributes
- [ ] Embedded HTML5 media (add if desired)

Responsiveness
--------------
Tested using Chrome DevTools device emulation. Layout shifts from single-column to 2–3 column grids; navigation collapses into a hamburger menu under 720px.

Accessibility notes & ignored warnings
--------------------------------------
Ignored warnings rationale:
1) Mobile nav `aria-expanded` on the hamburger label — This portfolio uses a CSS-only navigation toggle (checkbox pattern) without JavaScript, so the `aria-expanded` attribute is not programmatically updated. Keyboard navigation, focus visibility, and a clear skip link are provided, and the menu links appear in source order. After manual testing, this warning is considered acceptable for the assignment scope.
2) Muted copy contrast (`.muted`) — Muted text is used only for secondary/assistive content and kept at a readable size. While contrast checkers may flag it borderline on some displays, manual testing shows sufficient legibility against the background. For the purposes of this assignment, the style is retained.

Time to complete
----------------
~ 3.5 hours

Resources consulted (URLs)
--------------------------
- https://developer.mozilla.org/en-US/docs/Learn/Accessibility
- https://www.w3.org/WAI/ARIA/apg/

People consulted (classmates, staff, etc.)
------------------------------------------
- None

AI assistance acknowledgement
-----------------------------
Portions of this portfolio’s boilerplate, copy editing, and project templating were assisted by ChatGPT. I reviewed, tested, and edited all code and text. All validation, accessibility decisions, and final submissions are my own.

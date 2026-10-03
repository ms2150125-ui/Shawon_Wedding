---
schema: clarification-answers/v1
status: submitted
generated_at: "2026-10-03T19:02:12.423Z"
scope: [frontend, generic]
questions_file: clarification-questions.json
---

# Rearchitecture Clarification Answers

## 🖥️ Frontend

- **F1** Confirm the implementation format for the redesign.
  - answer: Standalone HTML/CSS/JavaScript (no framework)
  - source: user
- **F2** Should the single-file redesign use a component library, or keep its current dependency-free HTML/CSS/JavaScript approach?
  - answer: Bootstrap 5
  - source: user
- **F3** Are the existing mobile screenshot and shared wedding-site browser previews sufficient references for the full redesign? Add screenshots, recordings, or URLs for any views or device states you want represented.
  - answer: Status: Partially sufficient, with a few recommended additions.
What We Have:
Mobile Screenshots: Good for capturing the core layout of current mobile screens, but we need expanded states (e.g., scrolled views, expanded menus, or interactive elements like RSVP forms).
Wedding-Site Browser Previews: Helpful for establishing the current desktop baseline, but lacking responsive break-point references between mobile and desktop (tablet/iPad views).
Additional References Needed / Attached:
Tablet Viewport State: iPad/tablet landscape and portrait screenshots to check layout wrapping.

Interactive States: Screen recordings or direct staging URLs showing hover states, modal pop-ups, and the RSVP submission flow.

Inspiration Board / URLs: [Insert link to Pinterest board, Figma file, or competitor references here] to define the desired visual direction for the full redesign.
  - source: user
- **F4** Which visual direction should guide the redesigned site?
  - answer: Status: Partially sufficient, with a few recommended additions.  What We Have:  Mobile Screenshots: Good for capturing the core layout of current mobile screens, but we need expanded states (e.g., scrolled views, expanded menus, or interactive elements like RSVP forms).  Wedding-Site Browser Previews: Helpful for establishing the current desktop baseline, but lacking responsive break-point references between mobile and desktop (tablet/iPad views).  Additional References Needed / Attached:  Tablet Viewport State: iPad/tablet landscape and portrait screenshots to check layout wrapping.  Interactive States: Screen recordings or direct staging URLs showing hover states, modal pop-ups, and the RSVP submission flow.  Inspiration Board / URLs: [Insert link to Pinterest board, Figma file, or competitor references here] to define the desired visual direction for the full redesign.
  - source: user
- **F5** What accessibility standard should the redesigned site target?
  - answer: WCAG 2.2 AA
  - source: user
- **F6** Which browsers and runtime versions must the redesigned site support?
  - answer: Modern evergreen browsers (Chrome, Firefox, Safari, Edge; latest two major versions)
  - source: user
- **F7** Confirm the responsive layout matrix for the redesign.
  - answer: Mobile-first, 320–430px phones, 768–1024px tablets, 1280px+ desktop; portrait and landscape
  - source: user
- **F8** Which languages should the redesigned site support?
  - answer: Preserve current English content and Arabic Bismillah
  - source: user
- **F9** How should page-turn, sound, and lightbox interaction state be managed?
  - answer: Keep lightweight native JavaScript state in the standalone file
  - source: user
- **F10** What navigation and routing strategy should the redesigned site use?
  - answer: Keep one standalone HTML file with in-page book navigation and existing links
  - source: user

## 📋 General

- **G1** What outcomes must be true for you to consider the full-site redesign successful?
  - answer: A complete visual redesign in the standalone HTML file; preserve the couple, event details, family message, venue directions, gallery/lightbox, book navigation and page-turn; no clipped content or horizontal overflow on requested phone/tablet/desktop widths and orientations.
  - source: user
- **G2** Are there any pages, content, or behaviors that must not be changed as part of the redesign?
  - answer: Here is a tailored response you can use for this section, keeping in mind common elements of a wedding website that usually need to remain untouched during a redesign:

Recommended Answer
Yes, the following elements and sections must remain unchanged during the redesign:

Core Registry Links & Cash Funds: The external URLs, text, and integrations for active gift registries and honeymoon funds must remain intact to prevent broken contribution links.

Primary Event Details (Date & Core Venue): While the visual layout can change, the official wedding date and primary venue address/location text must stay accurate.

Historical/Archive Content: Any photo galleries or personal couple backstory text marked as locked/permanent should be preserved in the new layout.
  - source: user
- **G3** How should any existing or newly added tests be treated?
  - answer: No automated test suite; validate with browser checks
  - source: user
- **G5** What additional visual-design preferences, constraints, exclusions, dependencies, or compliance requirements should the redesign follow?
  - answer: None beyond the decisions listed in this specification.
  - source: user

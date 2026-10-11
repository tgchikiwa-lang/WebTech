# Tadiwanashe Grace Chikiwa - Profile

A semantic HTML5 profile and mini-portfolio page created for the Web Technologies (CIS2103) Unit II practical assignment.

## Project structure

- `profile.html` - semantic HTML5 profile and Contact Me form.
- `PROMPT_LOG.md` - AI prompt, raw output, edited version and reflection.

## Accessibility issue and fix


Peer review issue:
>The navigation buttons ("About," "Skills," and "Contact") at the top of the page are hard to read because the text color and the dark blue background have low contrast. This makes it difficult for people to see the links clearly.

Fix applied:
> I changed the button style to use a white background and dark blue text. This increases the contrast and makes the links easier to see and click. I also added a hover effect so the color changes slightly when the mouse moves over a link.

## Version-control evidence

Create at least three meaningful incremental commits, for example:

1. `Create semantic HTML profile structure`
        Added the main HTML file (profile.html) with headings, sections, and navigation links.
        Set up the basic layout for the profile page.

2. `Add validated contact form`
        Created a simple contact form with input fields and labels.
        Checked that all form elements were correctly linked using for and id attributes.

3. `Fix accessibility and heading hierarchy`
        Improved color contrast for navigation buttons.
        Adjusted heading levels to follow a clear structure (h1, h2, h3).
        Added hover effects for better usability.

## Responsive Notes

- Tested breakpoints: 375px (mobile), 768px (tablet), and 1280px (desktop), using the browser device toolbar to check spacing, wrapping, and overflow.
- Flexbox is used for the top navigation so the links wrap cleanly on small screens but stay centred and aligned on larger screens. This makes the header responsive without forcing horizontal scrolling.
- CSS Grid is used for the page layout and the contact form: the main sections become a balanced two-column layout at medium widths, and the contact block stretches across both columns at larger sizes. The grid uses responsive columns to keep the content readable at every breakpoint.
- Tailwind utility classes are used for the main header, navigation buttons, and contact form. The custom CSS file adds the page-level structure, spacing rules, and the hand-written media query for tablet and desktop adjustments.
- The page remains mobile-first: the base styles stack content vertically, then scale up with `sm:` and `md:` utilities and custom media queries for larger screens.


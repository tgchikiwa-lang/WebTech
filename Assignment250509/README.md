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

- Tailwind CSS is loaded from its CDN, and utility classes provide the page styling without a separate stylesheet.
- The layout uses a mobile-first approach: navigation links and contact fields stack on narrow screens, then become horizontal navigation and a two-column form at the `sm` and `md` breakpoints.
- The profile and skills sections sit side by side at medium screen widths and above; the contact section spans both columns.
- Responsive padding and heading sizes improve spacing and readability on small and larger screens.
- Navigation links, form controls, and the submit button include visible keyboard-focus styles.


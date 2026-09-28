# Elemental Surf Lodge – landing pages

Static HTML/CSS landing pages for Elemental Surf Lodge, Newquay. They are pasted into the lodge's WordPress site (elementalsurflodge.com), so each page must be fully self-contained.

## Pages
- `index.html` – UK Surf Skate Expo partnership page (all CSS scoped under `.esl-expo`)
- `groups.html` – Group accommodation page (all CSS scoped under `.esl-groups`)
- `assets/` – local copies of images for reference only; live pages use WordPress URLs

## Rules
- UK English throughout (colour, centre, organise).
- No full stops at the end of headings.
- Plain HTML and CSS only: no frameworks, no build step, no JavaScript unless asked.
- Keep all CSS inside the page's scoping class (`.esl-expo`, `.esl-groups`, or a new `.esl-<page>` for new pages) so it can't clash with the WordPress theme.
- Images: use `https://elementalsurflodge.com/wp-content/uploads/...` URLs, not local `assets/` paths.
- Font: Montserrat from Google Fonts.
- Colours come from the CSS variables at the top of each page (`--navy`, `--amber`, `--yellow`, `--warm-grey`, `--charcoal`). Reuse them; don't add new colours without asking.
- Buttons are pill-shaped (`--cta-radius`) using the `.btn`, `.btn--ghost` and `.btn--solid` classes.
- Every change must work on mobile.
- Only change what was asked. Don't restyle or "tidy" other parts of a page.

## Contact details used on pages
- Email: info@elementalsurflodge.com
- Phone: +44 1637 808 800
- Address: 61 to 63 Tower Road, Newquay, TR7 1LX (between Towan and Fistral beaches)

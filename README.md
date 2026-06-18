# Fundamental Analysis Bootcamp Redesign

Drop these files into your existing repo root:

- `index.html`
- `index.css`
- `index.js`
- `icons/` folder

The redesign keeps the existing bootcamp structure and links, but shifts the visual system to the new dark finance/poster theme: black base, purple neon glow, acid-yellow CTA tickets, floating finance elements, module cards, and a final Warren Buffett-inspired value-investing section.

## Notes

- All custom visual elements are SVG files in `icons/`.
- `icons/warren-buffett.svg` is a stylized illustration for the final section. If your team has an official licensed PNG/photo, replace the image path in the `.oracle-img` tag.
- No fixed `body height` is used, so the layout will grow naturally with content.
- The mobile menu is controlled by `index.js`.

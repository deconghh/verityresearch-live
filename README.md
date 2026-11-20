# verityresearch.us

This repo only holds the **built** Verity website that GitHub Pages serves at https://verityresearch.us. Don't edit these files by hand.

- **Source:** `site/` on the `website-lovable` branch of the team repo `ubc-2026/verity`.
- **Design:** made in Lovable (project "Verity: Market Clarity"), also published at https://verity-research.lovable.app.

## Update the live site

1. In `ubc-2026/verity`, `cd site`, run `npm install` and `npm run build:static`.
2. Copy everything in `site/.output/public/` here, keeping `CNAME` and `.nojekyll`.
3. Commit and push to `main`. Pages republishes in a minute or two.

# Design Tooling Stack

A short list of Claude Code skills/tools worth stacking together for design work.

1. **Awesome Design MD — build from a real design system**
   [github.com/VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)
   A collection of design-system files reverse-engineered from real sites — Stripe, Notion, Linear, Figma, and more. Point Claude at one and it builds from a look that already works in the real world, instead of guessing at "nice." This is the foundation the rest build on.

2. **Taste — design rules that kill the generic look**
   [github.com/Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
   Adds real design rules and adjustable "dials" (things like layout variance and visual density) on top. This is the piece that stops the flat, averaged-out AI look and gives the output actual taste. It works alongside a design system, not instead of it.

3. **Impeccable — the polish pass**
   [github.com/pbakaus/impeccable](https://github.com/pbakaus/impeccable)
   Your quality-control layer. It runs design critiques and audits (hierarchy, clarity, spacing) and, in live mode, lets you click an element in your browser and have Claude hand you variations to choose from. This is where good becomes polished.

4. **Playwright — actually test that it works**
   [github.com/microsoft/playwright](https://github.com/microsoft/playwright)
   Built by Microsoft, Playwright opens your site in a real browser and clicks through it, so you're confirming it works instead of hoping. The honest final step most people skip.

5. **img2threejs — one photo into a 3D model**
   [github.com/hoainho/img2threejs](https://github.com/hoainho/img2threejs)
   Give it one flat photo of an object and it has Claude rebuild that object as a 3D model that runs right in your browser, built entirely in code (not a downloaded mesh). Genuinely impressive for a hero element or a product showcase.

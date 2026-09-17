# Baker's math

Three small tools for sourdough baking, in one static page.

- **Dough** — size a dough to a target hydration, split it across two flours, and let the calculator account for the flour and water your starter already brings.
- **Levain** — build the exact levain a dough needs from a spoonful of the starter you keep.
- **Feeding** — track how a starter's flour blend and hydration shift feed by feed.

Baker's percentages throughout: every amount is relative to total flour, and the starter counts as flour + water at its stated hydration (so a 100% starter is half flour, half water). The dough tool can also size the sour by pre-fermented flour (*Versäuerung*), the share of total flour that ferments in the starter.

**Live:** https://baking.loessl.org

## Run it

A single, dependency-free `index.html`. Open the file in a browser, or serve the folder:

    python3 -m http.server

No build step, no dependencies.

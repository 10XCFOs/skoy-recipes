# Skoy Recipes

Batch-cooking recipes optimized for flavor, storage, and reheating. Every recipe here has been cooked, revised, and eaten for a week straight.

**Live site:** [10XCFOs.github.io/skoy-recipes](https://10XCFOs.github.io/skoy-recipes/)

## Recipes

### Mains
- **Oven-Roasted Pulled Pork** — Two 8 lb shoulders, low and slow at 275°F. Carolina-style with soy, mustard, and full-strength apple cider vinegar. ~10 lbs yield, 20+ servings.
- **Electrolyte-Optimized Corned Beef Brisket** — Precision equilibrium cure with KCl-enhanced potassium. Split into crispy flat slices (bacon substitute) and pressed point hash for morning meal prep. 5–10 day cure.
- **Baby Back Ribs with Skoy Sauce Glaze** — Three racks foil-wrapped and slow-cooked hands-off at 275°F, then double-glazed with Skoy Sauce at 325°F for a caramelized lacquer finish. ~3 hr 15 min.

### Sides
- **Guy's Loaded Mash** — Instant Pot russet mash with butter, sour cream, ranch packet, and melted sharp cheddar on top. Loaded-baked-potato flavor in ~30 minutes. Batches well, reheats cleanly over 4–5 days.

### Sauces
- **Skoy Sauce — Carolina Barbeque** — Vinegar-forward mustard sauce with Worcestershire, butter, and red pepper flakes. Thin, punchy, built to last. 10 min, ~1 liter yield. Printable jar label included.

## Structure

```
skoy-recipes/
├── index.html                ← Landing page / recipe index
├── recipes/
│   ├── pulled-pork.html      ← Oven pulled pork
│   ├── corned-beef.html      ← Electrolyte-optimized corned beef brisket
│   ├── baby-back-ribs.html   ← Baby back ribs with Skoy Sauce glaze
│   ├── loaded-mash.html      ← Guy's Loaded Mash (Instant Pot)
│   └── skoy-sauce.html       ← Carolina barbeque sauce
├── assets/
│   ├── style.css             ← Shared stylesheet
│   └── skoy-sauce-label.pdf  ← Printable jar label
└── README.md
```

## Setup

Hosted via GitHub Pages. Settings → Pages → Source: deploy from `main`, root folder.

## Adding a recipe

1. Create a new `.html` file in `recipes/`
2. Copy the structure from an existing recipe page
3. Link `../assets/style.css` for consistent styling
4. Add a card link on `index.html`

---

Draper, Utah

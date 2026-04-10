# Skoy Recipes

Batch-cooking recipes optimized for flavor, storage, and reheating. Every recipe here has been cooked, revised, and eaten for a week straight.

**Live site:** [10XCFOs.github.io/skoy-recipes](https://10XCFOs.github.io/skoy-recipes/)

## Recipes

- **Oven-Roasted Pulled Pork** — Two 8 lb shoulders, low and slow at 275°F. Carolina-style. Enough for 10+ days.
- **Skoy Sauce — Carolina Barbeque** — Vinegar-forward mustard sauce with Worcestershire, butter, and red pepper flakes. Printable jar label included.

## Structure

```
skoy-recipes/
├── index.html              ← Landing page / recipe index
├── recipes/
│   ├── pulled-pork.html    ← Oven pulled pork
│   └── skoy-sauce.html     ← Carolina barbeque sauce
├── assets/
│   ├── style.css           ← Shared stylesheet
│   └── skoy-sauce-label.pdf ← Printable jar label
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

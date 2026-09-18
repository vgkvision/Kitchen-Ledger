# Kitchen Ledger Plus

A polished clone of the live family Kitchen Ledger app. The original `index.html` at the repo root is unchanged.

Open `kitchen-ledger-plus/index.html` in a browser (or host this folder the same way you host the original). This copy uses the **same localStorage keys and family-sync format**, so on the same phone or computer it will show the real household data. Try it beside the original before you switch.

## What stayed the same

Recipes, menu planner, rotation, suggestions, shopping list, insights, cooking mode, and family sharing all work the way they do today.

## What Plus finishes

- Quieter chrome: Rotation search and “What should we cook tonight?” stay on Rotation; Menu and Shopping are no longer buried under those filters.
- A **Tonight** card on the Menu Planner.
- **Add all to list** for each planned dinner on the Shopping List, with the first dish already expanded.
- Dish rename / move / delete stay visible on phones (no hover required).
- Cooking Mode does not close if you tap the dimmed background or press Escape.
- Undo last sync on this device, in case a pull replaced something it shouldn’t have.
- Home-screen friendly (Add to Home Screen via the web manifest).
- Slightly smaller dish photos, so family sync is less likely to hit JSONBin’s free-tier size limit.

# Kitchen Ledger Plus

A polished clone of the live family Kitchen Ledger app. The original `index.html` at the repo root is unchanged.

Open `kitchen-ledger-plus/index.html` in a browser, or use the Plus home-screen icon. Plus keeps its own saved copy, so a test dish stays in Plus.

A picture guide for the beta is in [`beta-guide.html`](beta-guide.html).

## Two home-screen icons (iPad / iPhone)

Use **Safari**, not Chrome. Add each URL separately:

1. Live app: `https://vgkvision.github.io/Kitchen-Ledger/` → Add to Home Screen as **Kitchen Ledger**
2. Plus: `https://vgkvision.github.io/Kitchen-Ledger/kitchen-ledger-plus/` → Add to Home Screen as **KL Plus**

A dish added in Plus stays in Plus. To test with the family, use **Start sharing** inside Plus and send them the new sync code plus the Plus link. Keep the original Kitchen Ledger sync code in the original app, and keep the Plus code in Plus. The same jsonbin.io API key can create that second share.

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

## Beta additions

- A name on new dishes, planned dinners, and shopping items.
- A **Want to try** shelf (name, link, and a note). It does not copy a full recipe off the web.
- **Repeat a past week** and **Fill open days with favorites** on the Menu Planner.
- **Store mode** on the shopping list: larger type, checked items hidden, menu picker tucked away.
- Uploaded photos stay on the phone that added them, so they are left out of the family-share payload.

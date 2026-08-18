# Best By

A single-page web app for tracking grocery expiry dates know what's about to go off before it does.

## What it does

Best By keeps a running list of what's in your kitchen and sorts it by urgency, so a glance tells you what needs eating first. Add an item with its name, category, quantity, and expiry date, and it lands on one of four shelves:

- **Past due** - already expired
- **Expiring soon** - 0–3 days left
- **This week** - 4–7 days left
- **Fresh** - 8+ days left

Each item shows a stamped day-count badge, its category tag, quantity, and expiry date. Mark an item **used** once you've eaten it, or **remove** it if it's gone off or was added by mistake. A filter bar lets you narrow the list down to a single category (Produce, Dairy & Eggs, Meat & Seafood, Bakery, Pantry, Frozen, Other).

## How data is stored

Everything you add is saved automatically and privately - tied to your account, not shared with anyone else. There's no login or setup step; just open the file and start adding items.

## Running it

Open `best-by.html` in any modern browser. No install, no server, no dependencies.

## Possible next steps

- Adjustable "expiring soon" window
- Reminder/notification digest
- Barcode or receipt-based quick-add
- Export to a shopping list

# Meridian Wardrobe

A clothing manager, outfit planner, and trip packer for Obsidian. Mobile-first, and it syncs reliably through Obsidian Sync (everything is stored as JSON-in-Markdown files, never in plugin data).

Runs fully standalone — it does not require the Meridian dashboard. If you *do* have the dashboard, the two share one shopping list.

## What it does

- **Clothing** — track every garment's wash state (clean / dirty / in laundry), condition (ok / damaged / needs replacement), and a wears-since-wash counter with a per-type wear limit. Items you own in identical multiples (socks, underwear, bras) are tracked as individual copies you can wear, launder, and retire one at a time. Record where you got each piece and when. Filter and sort by presentation (masc / androgynous / femme), type, formality, tags, and availability.
- **Outfits** — assemble outfits from named slots, each with a primary item and an explicit list of allowed alternatives (only those may stand in). An outfit shows as **Ready**, **Via alternatives** (called out clearly), or **Unavailable** (with the missing pieces named), all driven by your current laundry. Retire outfits, or send everything in one to the wash in a tap.
- **Wishlist + shopping** — keep a clothing wishlist and push items to your shopping list. Retired pieces get a one-tap **Replace** (adds to the shopping list) and **Recover** (un-retires).
- **Trips & packing** — plan a trip by number of days and it builds the packing list for you: day-scaled underwear and socks, swimwear and a towel if you'll be swimming, always-on toiletries, and any custom items you add (with autocomplete that remembers everything you've ever packed). Plan outfits onto the trip and see at a glance whether each is wearable.

## Install (BRAT)

1. Install the **BRAT** community plugin.
2. In BRAT: *Add beta plugin* → `SilentNinja06/outfit_obs`.
3. Enable **Meridian Wardrobe** in Community Plugins.

Development lives in the [obsidian-workspace monorepo](https://github.com/SilentNinja06/obsidian_workspace.obs) at `plugins/wardrobe`; releases are cut here for BRAT.

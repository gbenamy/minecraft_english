# Minecraft English Game (Kid Prototype)

Simple web game for learning English vocabulary with Minecraft-style items.

## What it does
- Two modes:
- `Learning / למידה`: says Hebrew first, then English, with one item image.
- `Game / משחק`: says only `Find <english word>`, then shows multiple image cards with Hebrew labels.
- Local image assets in `assets/images` (no runtime network dependency).
- Score, streak, and round tracking in game mode.

## Run
Open `/Users/gbenamy/personal/minecraft_english/index.html` in a browser.

Tip: In Chrome/Safari on macOS, allow sound and wait a moment for voices to initialize.

## Current word set
Diamond, Gold, Grass, Apple, Sword, Pickaxe, Torch, Bread, Water Bucket, Tree, Cow, Pig, Sheep, Chicken, Wolf, Cat.
Also added: Iron, Coal, Stone, Dirt, Sand, Glass, Bed, Chest, Furnace, Crafting Table, Door, Diamond Chestplate, Shovel, Axe, Map, Boat, Cake, Golden Apple, Zombie, Skeleton, Creeper, Spider.

## Image source baseline
Images were copied locally from the public `PrismarineJS/minecraft-assets` repository, version folder `data/1.21.5`.
Animal renders (`cow/pig/sheep/chicken/wolf/cat`) were replaced with Minecraft Wiki images (mob renders, not spawn eggs).

## Next good upgrades
- Add category mode (tools/food/blocks/ores)
- Add "review wrong answers" mode
- Add parent dashboard with per-word accuracy

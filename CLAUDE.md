# Masks: Champions Villains Pack

Content pack containing villain NPCs from the Champions collection.

## Overview

- **Module ID:** `masks-champions-villains`
- **Type:** Content pack (Actor compendium)
- **Dependency:** Requires `masks-newgeneration-unofficial`
- **Content:** 137 villain NPCs

## Structure

```
masks-champions-villains/
├── module.json                    # Module manifest
├── packs/champions-villains/      # LevelDB compendium (gitignored)
├── src/packs/champions-villains/  # JSON source files (version controlled)
├── images/champions-villains/     # NPC portraits
├── tools/                         # Pack conversion scripts
└── package.json
```

## Commands

```bash
npm install              # Install dependencies
npm run packs:to-ldb    # JSON → LevelDB (after git pull)
npm run packs:to-json   # LevelDB → JSON (for version control)
```

**Important:** Foundry must be closed when running pack conversion.

## Image Paths

Images are referenced as: `modules/masks-champions-villains/images/champions-villains/{filename}`

## Editing Content

1. Make changes in Foundry
2. Close Foundry (or go to welcome screen)
3. Run `npm run packs:to-json`
4. Commit the JSON changes

## JSON File Naming

Files follow the pattern: `{type}_{SafeName}_{id}.json`
- Example: `npc_VillainName_abc123def456.json`

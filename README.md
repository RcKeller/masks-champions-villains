# Masks: Champions Villains Pack

Villain NPCs from the **Champions** collection for FoundryVTT.

## Requirements

- FoundryVTT v13+
- PbtA system v1.1.16+
- [Masks: A New Generation (Unofficial)](https://github.com/RcKeller/masks-newgeneration-unofficial) module

## Installation

1. Install the required Masks module first
2. In FoundryVTT, go to Add-on Modules → Install Module
3. Paste the manifest URL:
   ```
   https://github.com/RcKeller/masks-champions-villains/releases/latest/download/module.json
   ```
4. Enable the module in your world

## Contents

This pack contains 137 villain NPCs ready to use in your Masks campaigns, complete with:
- Drives and abilities
- Villain moves
- Condition moves
- NPC portraits

## Development

```bash
# Install dependencies
npm install

# Convert JSON to LevelDB (after git pull)
npm run packs:to-ldb

# Convert LevelDB to JSON (for version control)
npm run packs:to-json
```

**Important:** Close Foundry before running pack conversion commands.

## License

MIT

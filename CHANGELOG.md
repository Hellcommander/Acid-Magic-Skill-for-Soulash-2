# Changelog

## Unreleased (2026-11-14)

### Added
- Custom sound effects for 13 abilities (Stable Audio, built from Noise Alchemy / Dark Fantasy Studio reference sounds; credit in the mod description). Mod combat sounds are new to Soulash 2, so please report any ability that plays no sound.
- Rare site Vitriol Mire with a recruitable Erosion Magus.
- Optional Soulash Extender version (needs the Variants and EffectValues plugins): Thermotoxic Spray converts its damage into Corrosion stacks, as its description says. Not yet tested in game.

### Changed
- Mod description now states that the mod was implemented with the aid of AI tools.

### Fixed
- Acid Dart and Hemolysis tooltips said "for 0 turns".
- Vitriol Step had a resistance with no damage type, which can crash the game when a character under it takes damage; it now grants acid resistance.
- Stacker and Damage To Stacks entries sat under effects, where the game ignores them (it reads them only from effects_keys); they are moved there. Thermotoxic Spray now gives 3 Corrosion stacks per hit. Not yet tested in game.
- The Vitriol Laboratory did not show up in the build list: it had no building group or minimum area, which every buildable vanilla building has. It is now listed under Military, with a minimum area of 30. Not yet tested in game.

## Earlier history

- 2026-10-23: Fix acid hall map and passive reference
- 2026-10-21: Adjustments to map linkage
- 2026-10-17: New art and icons generated via my local sd pipeline and new animations that are more fitting then just reusing the game animations
- 2026-10-12: Finally should be free of building issues
- 2026-10-07: Passive changes
- 2026-10-07: Passive changes
- 2026-10-07: Trainer working
- 2026-10-04: Update still needs trainers wired
- 2026-09-30: Remove invented milestone prerequisites
- 2026-09-30: Rename Thermotoxic Spray milestone file to match what it unlocks
- 2026-09-30: Wire milestone prerequisites and fix broken skill references
- 2026-09-29: Improvements to the amps including proc trigger stamina damaging acid converted from part of damage
- 2026-09-29: Remade the skill it now longer consumes its own stacks should hopefully show up now removed effect per stack
- 2026-09-29: First release

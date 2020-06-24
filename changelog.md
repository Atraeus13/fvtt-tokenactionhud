# Changelog

## [0.1.19] 2020-06-24
### Bugfix
- Default to the core role handler for each system if the third-party module is unavailable.
- DND5e: Fixed spell slot check. Now shows spells when there are higher-level slots available to upcast.
- DND5e: Don't display items with no quantity.

### Changed
- Tried to remove some unnecessary logging when debug mode enabled.
- Removed some cruft.

## [0.1.18] 2020-06-22
### Added
- DND5e - the order of feats and items now follows their draggable order in the inventory.

### Changed
- CSS - changed appearance of info next to subcategory name (currently only used to indicate spell slots).
- DND5e - spells should now be sorted by level and then alphabetically.

## [0.1.17] 2020-06-21
### Added
- MinorQOL & BetterRolls - added ability to right click weapons for versatile attack when one exists (right-click acts as normal click if item has no versatile property). Has a slight problem with BetterRolls which uses shift for advantage, because shift right click is hardcoded to bring up the context menu in some browsers, but I don't want to mess with BR's shift/ctrl/alt preferences.

### Changed
- Renamed some CSS classes because they were really long.
- Renamed consumables without charges to 'incomsumables'.
- Filtered consumables of type 'ammo' out of list, but their count should show in curly braces when assigned to a weapon.

## [0.1.16] 2020-06-20
### Changed
- Updated CSS for buttons because they were being overridden by the Alt5e sheet.

## [0.1.15] 2020-06-20
### Added
- Agnostic - basic hovering, adapted from Token Tooltip, borrowed from Kekilla's issues tracking
- DND5e - ability to abbreviate skills and abilities, suggested by Tercept
- DND5e - option to separate ability tests and saves, suggested by Tercept
- Changelog, we'll see how long I keep this up.
- Updated readme

### Changed
- DND5e roll handlers now extend the core DND5e roll handler rather than the base class
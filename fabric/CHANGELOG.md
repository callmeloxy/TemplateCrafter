# Changelog

## 1.1.0

### Summary

This update adds a complete template system overhaul for the vanilla Crafter, including slot-based template logic, x1/x64 slot limits, smarter automation handling, expected recipe result protection, and multiple UI/interaction improvements.

### Fixed

- Fixed template insertion logic stacking identical items into the first compatible slot
- Fixed incorrect handling of repeated ingredients inside crafting patterns
- Fixed disabled template slots being accidentally re-enabled by interactions
- Fixed multiple insertion edge cases with manual insertion, shift-click, and automation
- Fixed template synchronization and persistence issues
- Fixed recipe ambiguity problems with intermediate recipes such as:
  - Iron Bars
  - Iron Nuggets
  - Glass Panes
- Fixed incorrect crafts being triggered before the full template was completed

### Added

- Added slot-based template handling
- Added x1 mode for limiting template slots to 1 item per slot
- Added x64 mode for limiting template slots to 64 items per slot
- Added expected recipe result saving
- Added expected output protection system
- Added ghost result preview support
- Added smarter automation compatibility for storage systems and hoppers
- Added transparent UI buttons integrated directly into the Crafter screen
- Added translatable tooltips for template controls

### Improved

- Improved template reliability for automation workflows
- Improved compatibility with recipes using repeated ingredients
- Improved Crafter interaction behavior
- Improved template persistence and synchronization
- Improved overall UX and visual integration with the vanilla Crafter

### Notes

- Templates now validate both the crafting pattern and the expected crafting result
- Each Crafter stores its own independent template and slot limit mode

## 1.0.0

### Summary

Initial release of TemplateCrafter, adding a simple and lightweight recipe template system to the vanilla Crafter.

### Added

- Added the ability to save a single template per Crafter
- Added a button to save the current recipe layout (`S`)
- Added a button to clear the saved template (`X`)
- Added ghost recipe display directly in the Crafter UI
- Added automatic disabling of unused slots based on the saved template
- Added protection against invalid item insertion
- Added support for manual insertion, shift-click interactions, and hopper input
- Added per-Crafter template persistence after world reload
- Added client-server synchronization for template data

### Notes

- This mod is designed around a single template per Crafter
- Template buttons are integrated directly into the Crafter UI
- Minor visual edge cases may occur during certain cursor-held interactions, but template protection remains enforced

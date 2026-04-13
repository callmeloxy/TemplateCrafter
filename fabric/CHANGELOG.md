# TemplateCrafter 1.0.0

## Summary

Initial release of TemplateCrafter, adding a simple and lightweight recipe template system to the vanilla Crafter.

## Added

- Added the ability to save a single template per Crafter
- Added a button to save the current recipe layout (`S`)
- Added a button to clear the saved template (`X`)
- Added ghost recipe display directly in the Crafter UI
- Added automatic disabling of unused slots based on the saved template
- Added protection against invalid item insertion
- Added support for manual insertion, shift-click interactions, and hopper input
- Added per-Crafter template persistence after world reload
- Added client-server synchronization for template data

## Notes

- This mod is designed around a single template per Crafter
- Template buttons are integrated directly into the Crafter UI
- Minor visual edge cases may occur during certain cursor-held interactions, but template protection remains enforced

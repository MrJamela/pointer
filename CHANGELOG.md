# Changelog

## 14.0.1

Fixes on top of the original 14.0.0 for Foundry VTT v14, tested live on v14.369.

- Ordinary pings no longer move everyone's view. Only the GM's "Move player view on ping" does, as the settings window says.
- The settings window's tick boxes and icons show again. They used Font Awesome 6, which Foundry v14 no longer ships, so the
  chosen pointer and ping, ticked options, the delete icon and "Create new" all showed as the same empty box.
- Pressing a number-pad key over the map no longer throws an error.
- The GM's force ping works when ping and force ping are set to different kinds of input (a key for one, a click for the other).
- The pointer designer's preview is see-through again instead of black.
- The designer's slider tick marks line up with their sliders again.
- No longer requires libWrapper or socketlib (the module never used them).
- Removed an unused image, the out-of-date source map and empty manifest entries.

## 14.0.0

The original release for Foundry v14 by p4535992 and contributors:
https://github.com/p4535992/foundryvtt-pointer

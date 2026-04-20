[README.md](https://github.com/user-attachments/files/26905277/README.md)
# AffixScanner

![WoW Version](https://img.shields.io/badge/WoW-WotLK%203.4.3-blue)
![Addon Type](https://img.shields.io/badge/Addon-Item%20Overlay%20%26%20Tooltip-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

`AffixScanner` is a Wrath of the Lich King addon that detects affix items by scanning tooltips for `@affix@` and marks them across the UI with custom overlays, tooltip styling, and loot notifications.

## Features

- Draws a custom corruption icon overlay on affix items
- Adds the affix name directly to item tooltips
- Applies a corrupted-style tooltip skin to affix item tooltips
- Shows a custom loot toast when an affix item is looted
- Displays affix labels on character and inspect equipment slots

## Screenshots

Add screenshots here if you want to showcase:

- Corruption item icon overlays
- Custom tooltip styling
- Loot toast popups
- Character and inspect affix labels

## How It Works

AffixScanner scans item tooltips for the `@affix@` marker.

If the marker is found, the addon treats the item as an affix item and applies its custom UI effects, including icon overlays, tooltip annotation, tooltip skinning, and loot toasts.

## Supported UI Areas

- Bags
- Character equipment slots
- Inspect equipment slots
- Auction House item listings
- Standard Blizzard item buttons

## Compatibility

AffixScanner is built for the WotLK client and is designed to work with standard Blizzard frames without replacing existing UI behavior.

Current compatibility includes:

- Blizzard bag and inventory item buttons
- Auction House listings
- DragonUI bag support

The addon uses compatibility hooks and bag-provider logic where possible so it can support custom UI or bag addons without taking control away from them.

## Installation

1. Download or extract the addon folder into your WoW addons directory:
   `World of Warcraft\Interface\AddOns\AffixScanner`
2. Restart the game or reload your UI
3. Enable `AffixScanner` from the addon list at the character screen

## Notes

- The addon is self-contained and uses local texture assets
- Tooltip, overlay, and toast behavior are all driven by affix detection from the item tooltip
- Additional bag addon support can be expanded through compatibility providers

## Known Limitations

- Some third-party bag addons may still require dedicated compatibility support
- ElvUI is not officially supported at this time

## Commands

- `/affixscan` - scans your current bags for affix items
- `/tooltipskin on` - forces the custom tooltip skin on
- `/tooltipskin off` - forces the custom tooltip skin off
- `/tooltipskin check` - checks whether the current tooltip item is detected as an affix item

## Summary

AffixScanner makes affix items immediately recognizable by giving them:

- A corruption icon overlay
- Enhanced tooltip information
- A corrupted visual tooltip style
- Loot toast notifications
- Character and inspect slot labels

## Contributing

Bug reports, compatibility reports, and UI support fixes for additional bag addons are always useful.

If you use a custom bag addon and find missing overlays, open an issue with:

- The addon name
- The exact place where the overlay is missing
- A screenshot if possible



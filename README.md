# Revolt-Discord
Simple custom css to make revolt look more like Discord

## Features
 - Floating message bar
 - Channel headers matching channel background
 - Discord like selected server pill
 - Wider server list
 - Wider channel list
 - Server icon animations (hover only)
 - Discord's addFile icon
 - Server's notification's pin switched to middle left position
 - Discord-like server pings (in the bottom right corner) (requires electron21 minimum, revite uses electron17 right now)

## Installing
1. Copy the [raw JSON](https://raw.githubusercontent.com/0x454d505459/Revolt-Discord/main/theme.json) from the [theme.json](https://github.com/0x454d505459/Revolt-Discord/blob/main/theme.json)
2. Open Revite (the Revolt client), in the settings under the appearance tab, scroll until you find the `theme override` section and click on the import theme button
3. You are good to go!

## Uninstalling
1. Change to a different theme

## Known issues
- Doesn't work on android

## Electron21 and later
Some present and future features requires and will require the :has css pseudo-class which is only available in chromium version 105 and later which started being shipped with Electron version 21. Here is how to use it with revite
### Linux
1. Install package electron21 or later using you package manager of choice
2. Run revite by running `electron21 /usr/lib/revolt-desktop/` in a terminal. Note that it may be installed elsewhere
3. You should create a desktop entry file to avoid having to open it using the terminal

### Windows
Sorry I don't know

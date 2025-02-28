
# FNV Save Plugin

A plugin for Fallout New Vegas that enables saving game state through F5 key press.

## Features

- F5 key saves game state
- Checks if player is in combat or handling items before saving
- Simple integration with NVMP framework

## Installation

1. Download the latest release from the Releases section
2. Place the `FNVSavePlugin.dll` file in your Fallout New Vegas plugins folder
3. The plugin will automatically initialize when the game starts

## Usage

Press F5 in-game to save your current game state. The plugin will notify you if the save was successful or if there was an error.

## Building from Source

```bash
dotnet clean
dotnet restore
dotnet build -c Release
```

The compiled DLL will be in the `bin/Release/net7.0/win-x64` directory.

## License

MIT

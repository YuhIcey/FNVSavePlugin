#FNV Save Plugin
A plugin for Fallout New Vegas that enables saving game state through F5 key press.

Features
-   F5 key saves game state
-   Checks if player is in combat or handling items before saving
-   Simple integration with NVMP framework

#Installation
Download the latest release from the Releases section

Place the WildWastelandSavePlugin.dll file in your NVMP SDK Server Plugin Files Then in the command line of the SDK Put Plugins=WildWastelandSavePlugin/WildWastelandSavePlugin.dll

#The plugin will automatically initialize when the Server is booted up

#Usage
Typing /save 1-10 in-game chat will save your in-game save to your current game state. The plugin will notify you if the save was successful or if there was an error in chat. use /load 1-10 to load one of those saves in chat. or use F5 to just use the quicksave. 

#Building from Source
dotnet clean
dotnet restore
dotnet build
The compiled DLL will be in the bin/Debug/net8.0/ all 3 Dependencies needed directory.

#License
MIT


SAVE PLUGIN MADE BY YUHICEY, THIS PLUGIN CAN BE DISTRIBUTED AND MODIFIED IN ANY SHAPE OF FORM AS LONG AS THE SERVER SIDED CLIENTEL DOES NOT USE THIS FOR HARM!

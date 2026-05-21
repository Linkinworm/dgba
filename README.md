dolphin android with mgba integration

Usage: 
Enable a GBA from the gamecube controller slot
click cog to load a game, or dont, leaveing blank will just leave in multiboot mode. zelda games, ffcc etc
if gba is slot 1 inputs will only be GBA controls, useless for most games, works with GB player and zelda 4 swords though maybe others.
if GBA is slot 2 3 4, gamecube and GBA controls will show, useful for every other game

bios must be in the bios folder for gba, not provided. Saves will save in gba/saves folder, they work on a per slot so a gba in port 2 will save something like ZeldaALTTP-2.sav, port 3 would save zeldaALTTP-3.sav etc

new GBA options in sidebar after loading at the bottom of the list while gbas are enabled.


gba hosting / client modes:
hosting is enabled from running any gamecube game with a gba enabled, sidebar, then gba options host gba session
client modes:
dolphin, main menu click the menu option in the top, join gba session
client app, just run the app.

Once in client mode select a GBA slot (they are mashed together visually but each purple button is slot 1 2 3 4, or click random slot if you want i guess.
it should just find the host automatically and display the GBA you selected. 
Note you cant connect to slot 1 currently so 2 3 4 are the only ones you should enable

options for client mode:
gc view will show or hide the gamecube while fullscreening the GBA on hidden.
press back to access menu options. currently you can disconnect, choose another slot, or set the GBA screen quality (might be useful if your router wifi is bad)
you shouldnt be able to connect 2 people to the same slot, it will just do nothing visually try another slot option or just click random that will probably find what ever slot is available

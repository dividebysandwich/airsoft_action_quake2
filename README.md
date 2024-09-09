# Airsoft Action Quake
Play airsoft tournaments in Action Quake, includes improved LTK bot!
This is Action Quake 2 with Airsoft weapons!
The guns are still the same, but they now fire 6mm BBs. These plastic bullets can fly quite a distance thanks to the "hop up" mechanism (they're flying with a "spin", which stabilizes the flight path) and most of the time a single is deadly. The included bots are the LTK bots, but my improved version (they don't hang at doors anymore, etc.)

## Weapons
### MK23 SOCOM
Type: Gas Blowback (GBB)
Magazine: 20 BBs
Range: 20 Meters

### MP5A5
Type: Automatic Electric gun (AEG)
Magazine: 200 BBs (HiCap)
Range: 40 Meters

### M4A1
Type: Automatic Electric gun (AEG)
Magazine: 250 BBs (HiCap)
Range: 50 Meters

### Steyr SSG
Type: Bolt operated
Magazine: 50 BBs
Range: 60 Meters

### Benelli M3
Type: Pump action
Magazine: 8 Shells x 10 BBs
Range: 20 Meters

### Madmax Shotgun
Type: Gas
Magazine: 2 Shells x 10 BBs
Range: 20 Meters

## Console Variables
Note: These variables can only be set by the server.
`announcer [0/1]`
Toggles the announcement voice on or off

`newsounds [0/1]`
Toggles the new weapon sounds on or off

`placenode`
This is more of a command rather than a cvar, and can be used to manually place nodes at strategic positions. Use this if your bots fall off small walkways or such, and manually add nodes to where the bots should go. This only works while ltk_routing is set to "1"

`placetrigger`
Another command similar to "placenode", only that this is intended to be placed in front of pushbuttons. When a bot gets to this place he will run forward, thus triggering whatever pushbutton is in front of him. May be of help in elevators and stuff.

`ltk_jumpy [1]`
Toggle (0 or 1) variable that sets whether the bots should jump around more or not.

`mk23_spread [140]`
Sets spreading for the H&K MK23 pistol.

`dual_spread [300]`
Spreading of the Akimbo Pistols.

`mp5_spread [250]`
Spreading of the H&K MP5.

`m4_spread [300]`
Spreading of the Colt M4

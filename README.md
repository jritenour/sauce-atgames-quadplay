# sauce-atgames-quadplay
Various config files for the AtGames Legends QuadPlay 4 player control deck for OneSaUCE.  sdl2 mappings are mostly completely - I'm still working on udev and emulator specific configs. 

A bit of background as to why these configs are necessary.  The standard AtGames ALU control panel maps like this in sdl2 input maps:

A - Button 1

B - Button 2

C - Button 7

X - Button 0

Y - Button 3

Z - Button 5

Rewind - Button 6

Start - Button 9

Menu - Button 12

The QuadPlay deck completely breaks this, as Player 1 and 2 map like this:

A - Button 0

B - Button 6

C - Button 7

X - Button 1

Y - Button 3

Z - Button 7

Rewind - Button 13

Start - Button 11

Menu - Button 12

These changes not only mess with retroarch, but also screws up navigation in the OneSaUCE menus, hence my changes to controls.conf.  I admittedly am not an expert on inner workings of OneSaUCE/retrofe, I just hacked at configs file till I got a result that works well with the QuadPlay.  If anyone wants to take my work and improve on it, please do so! Otherwise I'll just keep tweaking it as I work through it. Admittedly, I spend most of my time in SaUCE on the arcade, followed by Dreamcast and PS1.  So those are the ones getting most of my attention rightnow as far as getting working smoothly with the quad.

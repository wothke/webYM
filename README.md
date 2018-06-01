# webYM

Copyright (C) 2018 Juergen Wothke

This is meant as simple example demonstrating how existing JavaScript based music emulators can be
adapted to the plugin API used by my generic WebAudio ScriptProcessor music player (see separate project). 

The used YM.js allows to play AtariST .YM music files. The player is rather compact - eventhough
its sound quality seems to be inferior to alternatives like zxTune (see see my spectreZX project).


A live demo of this program can be found here: http://www.wothke.ch/webYM/


## Credits
Based on original YM.js (see https://github.com/photonstorm/phaser-plugins/tree/master/YM.

 
## Howto build

There is nothing to be built here. Most of the relevant code can be found in backend_ym.js - with
some VU-meter visualization specific add-ons in ym_tracer.js



## License

The same license used by YM.js extends to the additions that turn it into a plugin that 
can be used with my generic player.
# chut
a little bash script to change your Mac system audio volume from your command line

**USAGE**
**`chut [][0][1-100][-][--][+][++][+++][--help][--show]`**

**ARGS** 
```
  from 0 to 100 : set the volume level (as a percentage)
  - or +        : decrease or increase the volume by a half bar
  -- or ++      : by a full bar
  --- or +++    : min/max
  --show        : show the current volume level
  --help        : this help message
  no value      : mute 
```

**INSTALL**

Download the code for chut anywhere 
```curl -O https://raw.githubusercontent.com/docgyneco69/chut/master/chut```

Set the exec flag on ```chmod +x chut```

Move it within your path, as an example $HOME/.bin/chut ```mv chut ~/.bin/chut``` 


**`EXAMPLES`**

**`chut`**          : mute the sound

**`chut 90`**       : set the volume to 90%

**`chut --`**       : reduce the volume by a half bar

**`chut +++`**      : set the volume to the maximum

**ENJOY**

Now toning down your music or that pesky zoom session is as simple as entering in your terminal of choice: 
**`chut`** - and to turn the volume right back up to full: **`chut +++`** 

# chut
a little bash script to change your Mac system audio volume from your command line

**USAGE AND ARGS**
**`chut [][0][1-100][-][--][+][++][+++][--help][--show]`**
```
  from 0 to 100 : set the volume level (as a percentage)
  - or +        : decrease or increase the volume by a half bar
  -- or ++      : by a full bar
  --- or +++    : min/max
  --show        : show the current volume level
  --help        : this help message
  no value      : mute 
```

**`EXAMPLES`**

**`chut`**          : mute the sound

**`chut 90`**       : set the volume to 90%

**`chut --`**       : reduce the volume by a half bar

**`chut +++`**      : set the volume to the maximum

**INSTALL**

>download the script ```curl -O https://raw.githubusercontent.com/docgyneco69/chut/master/chut```

>set its exec flag ```chmod +x chut```

>move **chut** anywhere within your path ```mv chut ~/.bin/chut```

>and... voila!

**ENJOY**
Now muting your music or that pesky zoom session is as simple as entering in your terminal of choice: 
>**`chut`**

and turning the volume right back up: 
>**`chut +++`** 

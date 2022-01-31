# chut
a little bash script to change your Mac system audio volume from your command line

#### USAGE 
**`chut [][0][1-100][-][--][+][++][+++][--help][--show][--mute]`**
```javascript
  from 0 to 100 : set the volume level (as a percentage)
  - or +        : decrease or increase the volume by a half bar
  -- or ++      : by a half bar
  --- or +++    : min/max
  --show        : show the current volume level
  --mute        : mute for the given seconds, then return to previous volume (default 10)
  --help        : this help message
  no value      : mute 
  
```

#### EXAMPLES
**` chut `** mute the volume

**` chut 90 `** set to 90% 

**` chut -- `** reduce by a full bar 

**` chut +++ `** set to the max

**` chut --mute 3 `** mute for 3 seconds, then return to previous volume


#### INSTALL
download the script, turn the exec flag on, move it somewhere within your path e.g. `$HOME/.bin/chut` 
```javascript
  > curl -O https://raw.githubusercontent.com/docgyneco69/chut/master/chut ; 
  > chmod +x chut ; 
  > mv chut ~/.bin/chut
```


#### ENJOY
now muting your music or that pesky zoom session is as simple as inputing >**` chut `** in your terminal of choice, turn it right back up with >**` chut +++ `**

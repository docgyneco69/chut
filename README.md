# chut
a small bash script to change your Mac system audio volume from the command line.

**USAGE** 
```**chut [][0][1-100][-][--][+][++][+++][--help][--show]**```

**ARGS**
```
`from 0 to 100` : set the volume level (as a percentage)
`- or +`        : decrease or increase the volume by a half bar
`-- or ++`      : by a full bar
`--- or +++`    : min/max
`--show`        : show the current volume level
`--help`        : this help message
`no value` 		  : mute

```

**EXAMPLES**
```  
  chut          : mute the sound
  chut 90       : set the volume to 90%
  chut --       : reduce the volume by a half bar
  chut +++      : set the volume to the maximum

```

**INSTALL**
download anywhere, preferably under your path ($HOME/chut, ~/chut, /usr/local/bin/chut etc.):
```mv chut ~/chut```
Don't forget to turn the exec flag on:
```chmod +x chut```

**ENJOY**
Now tuning down your music or that pesky zoom session in the background is as simple as entering in your terminal of choice: `chut`

To put the full volume back on: `chut +++`


# chut
> CHUT is a simple shell executable to mut or increase/decrease the system audio volume on Mac OS X.

> USAGE chut [][-][--][+][++]
      no arg will mute (default)
      [-][+] [--][++] to decrease or increase the volume
      [+++] to set to the maximum
      [-h][--help] display this message
NOTE sys sets volume as float (0-10/0.1) but outputs int (0-100/14)

> INSTALL anywhere under your path ($HOME/chut, ~/chut, /usr/local/bin/chut ...), e.g. :

mv chut ~/chut 

> Make exec :

chmod +x chut

> Now tuning down your music or that pesky website is as simple as entering in your terminal of choice :

chut

> Put it back on with 

chut ++


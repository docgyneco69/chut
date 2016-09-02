# chut
CHUT is a simple shell executable to mute, increase or decrease the system audio volume on Mac OS X.

>USAGE chut [][-][--][+][++]
+   no arg will mute (default)
+   [-][+] [--][++] to decrease or increase the volume
+   [+++] to set to the maximum
+   [-h][--help] display this message

>NOTE sys sets volume as float (0-10/0.1) but outputs int (0-100/14)

INSTALL anywhere under your path ($HOME/chut, ~/chut, /usr/local/bin/chut ...)
> mv chut ~/chut 

TURN the exec flag on
> chmod +x chut

ENJOY tuning down your music or that pesky website as simply as entering in your terminal of choice :
> chut --

> chut

FULL Volume back on with : 
> chut +++


Hope it proves useful!

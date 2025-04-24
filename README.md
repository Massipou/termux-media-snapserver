# termux-media-snapserver
A simple termux configuration for playing audio from a smartphone to many devices synchronously

Just install snapserver and mpd on termux and replace theire configurarion files in ~/../usr/etc/

install MALP app (for example)  on the smartphone and add a profile with localhost as hostname port 8600

install a smartcast client on audio clients and connect to the phone with his private IP as host streamport 8004 control port 8005.

If the snapserver is also an audio device, you have to disable all audio output excepted snapcast from MALP in 
server property > output

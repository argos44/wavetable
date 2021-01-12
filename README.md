# wavetable
SoundBlaster Live Emu, etc Gravis Ultrasound wavetable cards
HI!

Good news.... if you dont have ISA slot pcs (386DX), and cannot get hold of Gravis Ultrasound cards for that reason, there turned out to be a hack made by probably spacex or someone else, no idea, just download this:

http://manpages.ubuntu.com/manpages.gz/xenial/man4/snd_emu10kx.4freebsd.gz

and add it to autosart at startup as script...

it will hang, but login again with console, (not xwindows) after reboot, and delete the file.

then just type startx, or reboot.

you will hear a better sound.

# snapcraft build files for Foot - a fast, lightweight and minimalistic Wayland terminal emulator
\
ssh can be used to escape from the snap's confined environment. ssh keys directory is /home/᚜user᚛/snap/foot-terminal/common/.ssh/

For autoconnection put to your /home/᚜user᚛/snap/foot-terminal/common/.config/foot/foot.ini something like this:  
shell=ssh -t user@localhost tmux -u new -A

Also this snap allows to activate the terminal emulator by opening any character device: xdg-open /dev/tty

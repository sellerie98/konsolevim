Bash script that opens files specified in a new terminal window in vim, working around the conflict of gvim and vim (at least under Arch Linux).
By default the script tries to use the default terminal by reading the $TERMINAL variable (you need to setup yourself e.g. by writing "export TERMINAL=<your favourite term emu>" into your .bashrc file) or simply starting up the default terminal emulators on supported DEs/WMs

Currently supporting default terminals of:
- Cinnamon
- GNOME
- i3-wm
- KDE Plasma

More coming soon

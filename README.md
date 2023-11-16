# ttmux

A simple wrapper script, born out of convenience. It starts a new
alacritty instance based upon the included config and spawns a tmux
session inside it. The alacritty config is rather basic and leaves
things like the scrollback buffer to tmux, the colors are based upon the
classic rxvt palette. The tmux sessions are named as specified in the
tmux configuration. If the standard configuration wasn't changed, the
session can be managed through *ctr-b s*.

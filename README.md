# Keyboard Layout Modification [us_appendix](us_appendix)

Add german umlauts to us basic layout via AltGr. Append `/usr/share/X11/xkb/symbols/us` with the snippet and load the updated layout via `> setxkbmap -layout us -variant german`.

*Nota bene*: To map capslock to escape, add `-option caps:escape` to the `setxkbmap` command, i.e. `> setxkbmap -layout us -variant german -option caps:escape`

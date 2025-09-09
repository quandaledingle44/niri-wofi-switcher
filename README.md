# niri-fuzzel-switcher
An adapted simple bash script to use wofi to quickly switch to a specific window in niri. props to the original writer, i just replaced the command to wofi and uploading it here to credit them ig.

Install Requirements:
1) bash
2) jq
3) wofi
4) niri

How to use:
1) Download niri_wofi_switcher, make it executable, and put it somewhere in your $PATH
2) Add a keybinding to the binds section in ~/.config/niri/config.kdl (e.g. `Mod+G { spawn "niri_wofi_switcher"; }`)

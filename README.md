# TIC-80-Geany-Syntax-Highlighting
Use these simple configuration files to enable syntax highlighting for TIC-80 in [Geany](https://www.geany.org/)

## Installation
* Locate Geany config folder for your OS
* Put filetypes.lua in the **filedefs** folder
* Put TIC-80.conf in the **colorschemes** folder
* Start Geany and set 'TIC-80' as your theme via View->Change Color Scheme...'

Standard Lua keywords which are duplicated in TIC-80 (eg print, exit) are treated as TIC-80 keywords.

You can modify the actual color of TIC keywords by changing the tic_words value (default bright yellow = #f0f000) in the [named colors] section of TIC-80.conf

**IMPORTANT** This modifies and extends the standard Lua keyword definitions for Geany. If you edit Lua files in Geany for other (non-TIC) purposes, duplicated keywords will be highlighted as described above.

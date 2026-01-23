Basic Hyprland screenshot utility.

Support for annotations and window selection

I made this because I wanted to practice my bash skills and because hyprshot doesn't support annotations

```
Usage: katshot [opts]
	-h                   Print this message
	-m <mode>            The mode to use for screenshot area selection (area, window, output, layer, surface)
	-f <filename>        Name of the outputted file
	-d <directory>       Path to the directory screenshots are stored in (created if it doesn't exist)
	-o                   Save the screenshot only onto clipboard (incompatible with -n)
	-n                   Don't copy screenshot to clipboard (incompatible with -o)
	-c <mode>            Specify clipboard mode (yes, no, only)
	-a <satty/swappy>    Open screenshot in annotation app, satty is used if neither is specified
	-z                   Freeze display during screenshot
```

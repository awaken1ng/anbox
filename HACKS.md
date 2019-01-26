- ANBOX_IGNORE_ALT_TAB=true|false

As name suggests, drops Alt-Tab events.
Can be useful in single-window since alt-tabbing out of it also switches applications in there.


- ANBOX_ALLOW_NON_FREEFORM=true|false|"package.name"

Allow windows that are not a part of freeform stack.
For example, if after running a game there is no window, but you can hear the music in the background, Anbox might have skipped window creation for it because it doens't support freeform.


- ANBOX_WINDOW_OVERRIDE="Window title"
- ANBOX_FORCE_FULLSCREEN=exclusive|fake|false

Force fullscreen for the window with the title defined in ANBOX_WINDOW_OVERRIDE.

Quick and dirty fork of [mjkoo's script](https://github.com/mjkoo/pianobar-notify) updated for python3.

#pianobar-notify

A simple script to create dbus notification bubbles with album art and song
information from [pianobar](https://github.com/PromyLOPh/pianobar/).

Forked from the jreese's [similar script](https://github.com/jreese/pianobar-python),
although the behavior of this script now differs significantly. It supports
album art, caches album art on disk, and now uses dbus notifications rather than
the old style pynotify notifications. Backwards compatibility is not maintained
with the old style notifications, although this is a possibility for a later
improvement.

## Installation

Installation is very easy, just:

1. Place `event.py` in `~/.config/pianobar/`
2. Make event.py executable with `chmod 755 event.py`
3. Add `event_command = <homedir>/.config/pianobar/event.py` to `~/.config/pianobar/config`


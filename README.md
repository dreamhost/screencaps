screencaps
==========

A screen capture utility for uploading screen capture images to DreamObjects on OS X.  The code is written in Python and utilized the OS X built-in screencapture utility.

The utility calls "screencapture" in interactive mode, the equivalent of Shift-Command-4.  After a screen shot is taken, it is stored in the tmp directory, uploaded to DreamObjects, and opened in a browser window in the background.

In addition to being a useful command-line tool, a keyboard shortcut can be created to call an Automator script to execute it.

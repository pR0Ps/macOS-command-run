macOS-command-run
=================

Makes it easy for non-technical people on macOS to run commands on directories via drag/drop.

As an example, the template workflow uses `ffmpeg` to convert all `*.flac` files in the directory
dropped on it to `*.mp3` files. This can easily be modified to suit other needs.

Making an app file
------------------

1. Open the CommandRun.workflow file in Automator.
2. Modify the notification texts, what the script does, etc.
3. Click File -> Convert To, and select Application.
4. Save the application, making sure to change the "File Format" (at the bottom of the save dialog)
   to "Application".

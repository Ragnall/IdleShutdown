IdleShutdown
============

Bash script to shutdown when idle and downloads are finished.

Requires xprintidle

This script will watch to see that the mouse is idle and also that there are no downloads in progress before shutting down.
Downloads are sensed by watching for change in the size of ~/Downloads.

It must be run as root.  Put gksu in front of the command in the launcher.


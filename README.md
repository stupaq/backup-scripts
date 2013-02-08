Backup scripts for (Arch)Linux
==============================

pacbak
------

Backups list of all packages installed explicitly from repos with pacman
(ArchLinux specific). Has an option to reinstall all packages from backup
file in case of pacman database corruption.

backup
------

General backup script with support for ssh, fs and loop file destinations.
Backup profiles are read from ~/.backup-profiles (example profile included,
enables profile definition must have eXecution and Readable permissions).
You can specify pre- and post- triggers - commands to execute, excludes and
whatever you like, you can run several backups with one command.

Disclaimer 
==========

Use at your own risk.

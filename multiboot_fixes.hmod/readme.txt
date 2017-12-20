=== Multiboot Fixes ===

This mod will do the following

1. Separate the game directories so hakchi doesn't erase NES games when syncing SNES games.

2. Optionally separate the clover profiles to prevent corrupting anything.

3. If needed, patch /bin/hsqs to work properly with the per-system game directories.

Once installed, you can just add and sync a .hsqs file like you would a game, everything will work.

=== Separating Save Files ===

If you want separate save profiles for each system, you can FTP or telnet into the classic and create the following folders, but don't create the one that corresponds to your system:

/var/lib/foreign-clover/nes-usa
/var/lib/foreign-clover/nes-jpn
/var/lib/foreign-clover/snes-usa
/var/lib/foreign-clover/snes-jpn

=== Note for USB-host users ===

For saves, just create those four folders in your hakchi/saves/ folder on the USB drive

For games, you'll create those four folders in the hakchi/games/ folder and place the games for each system in their respective folder.
=== Multiboot Fixes ===

This mod will do the following

1. Separate the game directories so hakchi doesn't erase NES games when syncing SNES games

2. Separate the clover profiles to prevent corrupting anything.

3. Prevent clovercon from breaking when switching system images.

4. Patch /bin/hsqs to work properly with the per-system game directories

Once installed, you can just add and sync a .hsqs file like you would a game, everything will work.

A note about cleanup... this mod does not delete the saves for the "foreign" system images when it's uninstalled.  If you want to completely remove all traces of ever modding the system, you can do that manually by deleting /var/lib/foreign-clover when running the nand firmware and before uninstalling hakchi.
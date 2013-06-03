This is a convertion of the config files from
[TV Aerospace and Pizza](http://forum.kerbalspaceprogram.com/showthread.php/15348-0-20-x-Taverio-s-Pizza-and-Aerospace-v1-4-1)
for use with
[Module Manager](http://forum.kerbalspaceprogram.com/showthread.php/31342-0-20-ModuleManager-for-all-your-stock-modding-needs-current-version-1-01).

NOTE: this is NOT standalone; you will need to download the original mod to
make use of it. No models, textures, or dlls are included. Neither are the
config files for any new (non-copied) parts (eg, the NTBI wings). Also, it
currently does not do anything with KineTechAnimation.

Instructions:
- download the original mod and extract to a working directory
- delete the Squad directory from for the freshly extracted
  TV Aerospace-1.4.1/GameData directory (be careful to NOT delete the Squad
  directory in the KSP GameData directory!!!)
- Copy the Squad directory from this package into TV Aerospace-1.4.1/GameData
- Copy the TV PP/TV\_PP.cfg from this package to
  TV Aerospace-1.4.1/GameData/TV PP
- Copy/merge(mac) the contents of the TV Aerospace-1.4.1/GameData directory
  into KSP-root/GameData

While data is written to GameData/Squad, the orignal files are not touched:
the resized parts are specified via part2.cfg which sits beside the original
part.cfg. Tavarius's tweaks to the stock parts are in TV PP/TV\_PP.cfg and are
applied via Module Manager.

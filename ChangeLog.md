## Change Log ##

2011-08-20: v.19

  * bugfix: loading a long sample threw a confusing, empty error message. thx to clay morrow!

2011-07-17: v.18

  * bugfix: reset forced loop bits when making a new kit. this could be an issue when overwriting speech kits. thx to clay morrow!

2011-06-29: v.17

  * remove "create new kit" button (not needed)
  * add "export sample" button
  * make it possible to edit existing kits
  * make it possible to select+drop multiple samples
  * tidy up display of empty kits

2011-06-27: v.16

  * bring back support for 8-bit .wavs
  * some emulation of game boy sound while prelistening

2011-06-19: v.15

  * a bunch of minor UI fixes, e.g. use native file dialogs

2011-06-19: v.14

  * show samples when clicking them.

2011-06-19: v.13

  * made it possible to drag-drop .gb, .kit, .wav files into LSD-Patcher.

2011-06-19: v.12

  * some dither slider fixes.

2011-06-18: v.11

  * listen to sounds by clicking them in the UI (thx Clay)
  * fix visual error that could happen when creating new kit (thx Clay)

2011-06-15: v10 - interface improvements.

  * drop "compile kit" button. it's not needed.
  * add some more error popups in case of errors.
  * always show total kit size to avoid confusion.
  * if a .gb file is not selected at startup, quit.

2011-06-13: v9

  * add error messages when trying to add samples of some unsupported formats

2011-06-07: v8

  * auto-open Load ROM file dialog when starting program

2011-05-17: v7

  * when compiling kits, make sure they have at least one sample

2007-03-25: v6

  * added support for loading 16-bit WAV samples
  * added menu option "Import kits from ROM" for importing all kits from another ROM image. useful at version upgrades

2006-08-08: v5

  * bugfixed. problems with creating new kits on previously unused kit spaces

2006-07-08: v4

  * made room for more kits - now possible to fit about 50 kits on each ROM image. this new space will only be visible on LSDj v3.6.0 and up
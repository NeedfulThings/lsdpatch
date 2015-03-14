This tool can be used to compile and patch your own sample kits into Little Sound Dj.

### Requirements ###

  * A reasonably new version of Java. http://www.java.com
  * The original Little Sound Dj ROM image.
  * (optional) A set of .wav files to import.

If you want to transfer the ROM images to cartridge, you will also need a backup system, like the GB Xchanger or GB Transferer.

### Startup ###

Double click the .jar file. If this doesn't work, try "java -jar LSDPatcher" on the command line.

### Patching in ready-made sample kits ###

  1. Load the original Little Sound Dj ROM image.
  1. Select the sample bank you wish to overwrite. This is done by using the combo box in the top left.
  1. Click "load kit" and select the kit to patch in.
  1. Press "save rom..." to save the new Little Sound Dj ROM image.
  1. Use your new ROM image with pleasure.

### Version upgrade (Move kits from old ROM) ###

  1. Open new version ROM
  1. Select "Import kits from ROM" in menu
  1. Select old version ROM (with your custom kits)
  1. Save ROM & use it

### Patching in your own samples ###

  1. Load the original Little Sound Dj ROM image.
  1. Select the sample bank you wish to overwrite. This is done by using the combo box in the top left.
  1. To get rid of any old samples, select them and click "drop sample."
  1. Press "add sample" to add a sample. (The program looks for 16-bit .wav files.)
  1. Repeat previous step until you added all samples needed. If you run out of space, text will turn red and you have to drop samples.
  1. Type the name of your new kit into the white textfield left to the "rename kit" button. Then, commit the change by clicking the "rename kit" button.
  1. Press "save rom..." to save the new Little Sound Dj ROM image.
  1. Use your new kit with pleasure.

The total sample time for one kit is limited to about 2.8 seconds. When the text in the lower left turns red, the kit is full and you must either drop some sample or cut down the length of the samples you already use.

The dithering slider may improve the perceived bit depth when going from 8/16-bit to 4-bit by adding some random noise.

### On Preparing Samples ###

  * The sound amplitudes should be pushed up as much as possible. Normalize and then maybe add +3db gain.
  * LSDPatcher has really crappy resampling routines, no antialiasing or interpolation. It may be a good idea to do the conversion from 44100 to 11468 Hz in your normal wave editor.
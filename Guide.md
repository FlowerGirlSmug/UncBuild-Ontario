# UncBuild-Ultimate FAQ & Help

### If I'm playing on UncBuild-Ultimate and my opponent is playing on a different Dolphin (Zubuild, ILPM, etc.) can we play together?

#### Unfortunately, no. Dolphin netplay requires both Dolphin's to be the same version, and it checks the SHA hash to determine this. You and your opponent must both be on UncBuild-Ultimate Dolphin in order to netplay each other. You'll know your on the same version if the name in the top-left is the exact same, or by going to Help > About and checking the Revision number.
-
### Help! My opponent and I desync'd, what's happening?

#### If you and your opponent desync'd the most likely answer is either your SD.raw's are different, your tag files are different, or both. In order to netplay without desyncs make sure your using the same SD.raw file and your tag files are both on the same version, if you don't both have the same ones netplay will IMMEDIATELY desync 
-
### How do I change my SD card and my tag files?
#### The SD.raw file can be changed by clicking Config > Paths > SD Card Path and selecting the "...", Dolphin will prompt you to select your SD.raw file, I highly recommend either renaming the file or putting it in a seperate folder to distrinquish them, you and your opponnent can have differently named files as long as the file itself is identical.
#### The tag files can be changed using the scripts in the Tags folder in the UncBuild-Ultimate folder, simply double click on the script for the tags you want and close the command prompt after it finishes.
-
### I clicked the script but the tags didn't change, what gives?
#### The scripts work by locating a ZIP file and unzipping to the `Sys\Wii\title\00010000\52534245\data` directory, the scripts are *very* simple and if something goes wrong the most likely culprit is the ZIP files or location of them has been accidentally moved or deleted. Make sure to not touch the "Zips_ignore" folder to avoid this. Also ensure that Windows allows scripts to run, in which case google is your friend. In the event that no matter what the scripts do not work you can always manually change the tag files, simply Unzip the contents of the ZIP file with the tags of your choosing, and move the `autosv0.bin` & `autosv1.bin` files to `Sys\Wii\title\00010000\52534245\data`.

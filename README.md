<html>
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<!--<title>America's Most Haunted - Project to color the DMD</title>-->
</head>
<body>
<h1>America's Most Haunted - Project to color the DMD</h1>
Once upon a time, I started a project to add color to the DMD animations in Spooky Pinball's America's Most Haunted game.  Once I got past the technical hurdles, I quickly got bored with the tedious coloring.  I didn't even have enough left in the tank to color this page.  Still, I wanted to share what has been done.
<BR><BR>
Maybe someone will be motivated to pick up the torch and continue with the coloring.  If so, please let me know, <a href="https://pinside.com/pinball/community/pinsiders/herg">PM herg at Pinside</a>.
<BR><BR>
<h2>SD card files for users with one of the Chroma-Color LCD displays I built</h2>
<a href="http://ledocd.com/files/AMH_SD_CHROMA_INDEX_20220410.zip">Download indexed SD update files</a>
<BR>
<a href="http://ledocd.com/files/AMH_AVKERNEL_PCM5102_DAC_CHROMA_20200325.zip">Download AV firmware for use with Chroma-Color LCD</a>
<BR>
Unzip and copy PROP_088.BIN to the DMD/ directory
<BR>
Format the SD card.  Do NOT simply erase the files from it.  Put the files on an SD card (SanDisk Extreme Pro highly recommended) per Spooky's instructions
<BR>
<h2>SD card files for users with a Pin2DMD with v3.0 or greater firmware</h2>
<a href="http://ledocd.com/files/AMH_SD_CHROMA_INDEX_20220410.zip">Download indexed SD update files</a>
<BR>
<a href="http://ledocd.com/files/AMH_AVKERNEL_PCM5102_DAC_PIN2DMD_20200325.zip">Download AV firmware for use with PIN2DMD</a>
<BR>
Unzip and copy PROP_094.BIN to the DMD/ directory
<BR>
Format the SD card.  Do NOT simply erase the files from it.  Put the files on an SD card (SanDisk Extreme Pro highly recommended) per Spooky's instructions
<BR>
<h2>View the Animations</h2>
<a href="http://ledocd.com/amh_color/view_table.html">Live view of all animated GIFs</a>
<BR>
<h2>How to recover the AV firmware if you mess it up</h2>
Here's a <a href="https://youtu.be/dMOnqMgSajo">video</a> to show the process.
<BR>
<BR>
1. Connect a mini-USB cable to the Propeller port. It's the one of the upper right section of the board.
<BR>
2. Download and install the <a href="https://developer.parallax.com/propelleride/">PropellerIDE</a>.
<BR>
3. Download the <a href="http://ledocd.com/files/amh_AV_prop_recovery.zip">recovery project from my website</a>.
<BR>
4. From within PropellerIDE, open the project file, av_kernel_23.spin
<BR>
5. Select the COM port that shows up when the mini-USB cable is plugged in.
<BR>
6. Click on the Run button.
<BR><BR>
This should build the code, transfer it into the game's RAM, run the code, read the SD card, and update the Propeller EEPROM to the code that's on the card.  If you are unable to get this to work, contact me.  I have replacement EEPROM ICs that have a good AV firmware load on them.
</body>
</html>

# MirroredQWERTY
QWERTY keyboard layout but mirrored

<h1> Installation Instructions (Tested on Ubuntu 20.04): </h1>

1. Download this project's files

2. Put "zz" file (from MirroredQWERTY folder) in /usr/share/X11/xkb/symbols/

3. Put "evdev.xml" file (from MirroredQWERTY folder) in /usr/share/X11/xkb/rules/ and overwrite the file that's in there (see "Troubleshooting" for more info)

4. Restart computer

5. Go to System Settings -> Region & Language. Click "+", click "English (United States)", scroll and click "MirroredQWERTY", then click "Add" green button. 

It should now be available in the top right hand corner of your menu, a drop-down menu that allows you to click and select the keyboard layout you want (default would probably be "en" with a down arrow next to it).
  
<h1> Troubleshooting (And Notes) </h1>

A. Steps 4 and 5 might need to be flipped, I don't remember (you may need to restart again after #5, but I don't think so).

B. In step 3, I got the file from [this link](http://people.uleth.ca/~daniel.odonnell/Blog/custom-keyboard-in-linuxx11#e) which was basically what I used to figure out how to create the layout (if you want to check the steps); [this Ubuntu guide](https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions) was also helpful.

C. I skipped one of the steps of updating xorg.lst (it was an optional step on the first link).

D. You could probably copy the "zz" file's contents and paste it in the "en" file and it should still show up, if you don't want "zz" to show up (it should appear as "en" in your top right corner).

E. This might work for any system using xkb?

F. The default keyboard shortcuts for switching between keyboard layouts is Shift+Super+Space (to go to the previous layout) and Super+Space (to shift to the next layout in order). If you want to change this, you can go to Settings -> Devices -> Keyboard Shortcuts (then scroll to "Typing" section).

G. For learning a layout, I find it helpful on a second screen (or smartphone) to pull up the layout to look at while typing and memorizing on some kind of typing test like typeracer.com.

H. If you'd like to try to create a custom layout of your own, you just need to go to the "zz" file for instance and switch around the values of the keys. I don't know what all the codes are for the keys, but you can get some ideas by finding other codes in the files in the /usr/share/X11/xkb/symbols/ folder.

<h1> Happy Typing! </h1>

Let me know if anything needs to be adjusted!

# gemesys_repository
GEMESYS Repository on GitHub

Initial Public Repository - Creation date: January 26, 2016

Update: Android APK files (Android Packages) for GEMESYS Android apps (gDosBox, APL's and GNUplot37)  - May 20, 2019

Note: All these APK files have been signed by: GEMESYS Ltd.
Previous versions of these programs are available on the Google Playstore, and we are attempting to update
the Playstore version of these apps.  These are 32-bit apps, but should run on 64-bit Android devices.

 gDosBox -   Basic Android DosBox, as per the DOSBox 0.74 source, (used JNI (Java Native Interface) and SDL 1.2/1.3)
             to allow DOSbox to run on Android Tablets and Phones.  The GEMESYS version of DOSbox includes corrections to
             the DOS floating-point code, which were developed for the original Blackberry Playbook version.  The keyboard
             is invoked by pressing the "Ab" ghostkey, top left of the Android screen.  Use Android 'back' key to close
             the keyboard.  Note, the Android on-screen ghostkey "1" is the return key.  To see all your files for all 
             the various applications here, you can start gDosBox, enter "dir/p", close the Android keyboard with the
             Android back-arrow key, and page thru all your files by pressing the "1" ghostkey when you see the prompt
             "Press Return to continue..".   In gDosBox, the up-arrow key will bring back your last command, and you 
             can re-enter it.
           
 GNUplot37 - GNUplot ver. 3.7 for Android.  Start GNUplot37, and enter: "splot sin(x)+sin(y)"  to confirm it works. This
             should create a 3-d plot.  Try: "set isosam 40; set hid; splot sin(x)+sin(y)" to give it a good workout.
             There are many demo programs included.  These have extension: "DEM".
             
 APLse     - A freeware version of the original STSC/Manugistics APL interpreter.  This APL uses a "unified" keyboard,
             so the ")" key is as per the standard ASCII location (shift of the zero key).  But you will need to download
             and make default the "Hacker's Keyboard", so that your Android keyboard can generate "Alt-key" sequences.
             To exit any APL interpreter, you use the command: ")OFF".  The APL workspaces for APLse have extension: AWS
 
 sAPL      - The I.P. Sharp IBM P/C APL interpreter, which runs the full mainframe Sharp APL from the IBM 360 (and later
             their big Amdahl machine), using an interpreter for IBM 360 Assember code.  So this app is actually running
             an interpreter on an interpreter running on an interpreter.  It works surprisingly well, and the math is 
             accurate, and has passed a number of verification exercises. (Eg. Confirm against results published in the
             original "Gilman and Rose" APL textbook. ("APL, An Interactive Approach", by Gilman & Rose, published by 
             John Wiley & Sons, Inc.).  This APL requires APL characters to be generated with "ALT-key" sequences. You 
             need to download the "Hacker's Keyboard" from Google Playstore, and use the Android "Settings" key to make
             the "Hacker's Keyboard" your Default Keyboard. (You can change this anytime.)
             The APL workspaces for sAPL have extension: SAW
             
 TryAPL2   - The IBM (Madrid) version of demostration APL interpreter, TryAPL2, developed for the IBM P/C to showcase
             the features, characteristics and capabilities of the IBM APL2 product.  You press the ghostkey "5" to 
             accept the "IBM Agreement", and jump to the APL workspace, where APL commands and keystroke can be entered.
             The TryAPL2 interpreter can be used with the gKeyboard, which provides a simple Android keyboard that 
             has yellow "sticker" images for the APL characters.   The APL workspaces for TryAPL2 have extension: TRY
             
 WatAPL    - This is a version of the original IBM/PC Watcom APL, circa 1984.  Much of the Watcom software (including
             their original 'C/C++' and Fortran-77 compilers), are available from the https://www.openwatcom.org 
             Also, a good summary of the OpenWatcom C-compiler is here: http://www.azillionmonkeys.com/qed/watfaq.shtml 
             The WatAPL interpreter here is from the original Watcom product in 1984.  The gKeyboard is also useful
             with this APL, as WatAPL uses shifted keyvalues for the APL characters.  Note that all the APL's here are
             running under gDosBox, and have small workspaces.  But APL is ideal for a "pocket-computer", as it lends 
             itself to quick, (but maybe complex) calculations, and small, one-off programs.  Any APL workspace can be
             saved with ")SAVE wsname", and reloaded later, with the ")LOAD wsname" command.  The APL command ")LIB"
             will show the workspaces and other files available on the virtual disk.  Note: With the WatAPL interpreter,
             on Android, you have to press the screen top-left "Ab" ghostkey, and then press ghostkey "1" to bring up 
             the Android keyboard.  If using Hackers Keyboard, or a standard Android keyboard, the ")" key is generated
             in APL by pressing the double-quote key.  The WatAPL workspaces have no default extension, but you can 
             assign anyone you want, eg: ")SAVE wsname.WAP" You can then reload later in new session with ")LOAD wsname.WAP"

gKeyboard  - This provides a trivial application, which allows the gKeyboard to be loaded. You still need to use the
             Android Settings feature (the little "gear" icon), to select this keyboard as your default keyboard.  This
             keyboard is useful for TryAPL2 and Watcom APL.  You will need to use "Hacker's Keyboard" for sAPL and APLse,
             as those APL's require the APL characters to be created with the ALT-key sequence, which only the Hacker's
             Keyboard has.

sAPL.zip   - This is a zipfile containing the IP Sharp APL for IBM/PC interpreter.  It can run in a DOSbox window on
             Window or Linux.  DosBox for Windows and Linux can be downloaded and installed from: https://www.dosbox.com 

Mark Langdon, GEMESYS Ltd., May 20, 2019

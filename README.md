# OpenSCAD-notepad-plus-plus-Language
This is a posting of Justblair's OpenSCAD/Notepad++ Language File (including useage guide) from Thingiverse: https://www.thingiverse.com/thing:15363

#Summary This guide is for Windows Users.

I am growing to love OpenSCAD as a creative tool for 3D design but I do find that it's text editor lacks many of the basic features that I appreciate when writing code... Namely:

Auto-Completion Syntax Highlighting Collapsible Outline levels Line Numbering Automatic Tabbing Search and Replace Block Tabbing using the tab key.

I was pleased to discover however that you don't need to put up with the standard text editor. There is a feature that allows you to conveniently use the text editor of your choice with OpenSCAD. My editor of choice is Notepad++ a fast well featured open source text editor. You can download it from http://notepad-plus-plus.org/

Notepad++ supports many different programming languages but not unfortunately OpenSCAD. It does however have the facility that allows you to create your own language file which I have included here.

This is definitely a work in progress as I have had to make a few compromises due to the limitations of Notepad++'s language editor. I dare say other more experienced coders opinions will differ as to how best to syntax code the OpenSCAD language.

I am currently working on adding auto-complete functionality to notepad++ as we speak. I have included a working though not complete file called openscad_removethisbitandcopy.xml. Currently most if not all functions will auto-complete, what is going to take me longer is adding call-tips to all the functions which would be nice though is not critical.

** Edits *** 13/5/2012 Added extension type to openscad.xml so that Notepad++ will now automatically detect language when .scad files are opened. Thankyou CrazyJaw, saved me some time there.

Instructions Installing The Language File

I assume that you have already downloaded and installed both OpenSCAD and Notepad++

Download the openscad.xml file.

Open Notepad++

In the view menu pick the User-Defined Dialogue... item

In a moment the User-Defined dialogue box will appear. Select Import

The Open dialogue box will appear, navigate to where you downloaded the openscad.xml file and open it.

That should be the openscad language file installed. You cna check by looking under the Language menu in Notepad++. At the bottom should be Openscad. Using Notepad++ With OpenSCAD

Open OpenSCAD, Create a new file and save it.

In the Design menu select Automatic Reload and Compile

In the View menu select Hide editor

Leaving OpenSCAD running, now find your newly created .scad file in Windows Explorer, right hand click on it and select Edit with Notepad++

Arrange both OpenSCAD and Notepad++ on your screen/s so that both can be seen at once. If you are using Windows Vista or 7 you can drag the title bars of the applications to the left and right sides of the screens to do this easily.

Edit your .scad file in Notepad++. Each time you save the file (CTRL+S) you will see that OpenSCAD will recompile the object. You will need to choose the Openscad language from the Languages menu. You will also need to either modify the color scheme for the language file or chose a dark theme for notepad itself. Enjoy all the advanced text editing features of Notepad++ as well as syntax highlighting of your code!!!

Enabling Auto-Completion in Notepad++

Download the file named openscad_removethisbitandcopy.xml and copy it into either c:\Program Files\Notepad++\plugins\APIs (Windows 32bit) or C:\Program Files (x86)\Notepad++\plugins\APIs (Windows 64bit) or something like that depending on your setup.

Rename the .xml file to openscad.xml

Restart notepad and try it out. Auto-Complete can be activated by clicking CTRL-Space at any time.

If you want Auto-Complete to be even more automatic, you can turn it on so that it will detect the functions as you type them... Go to Settings and click Preferences.

When the dialogue box appears, select the Backup/Auto-Completions tab. Under the Auto-Completion section choose your preferred options.

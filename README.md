# OpenSCAD-notepad-plus-plus-Language

This is a posting of Justblair's OpenSCAD/Notepad++ Language File (including useage guide) from Thingiverse: https://www.thingiverse.com/thing:15363

This guide is for Windows Users and has been adapted from Justblair's orignal guide

## Introduction 

OpenSCAD's text editor lacks many of the basic features that when writing code, namely:

- Auto-Completion
- Syntax Highlighting 
- Collapsible Outline levels 
- Line Numbering 
- Automatic Tabbing
- Search and Replace
- Block Tabbing using the tab key.

You can download Notepad++ from http://notepad-plus-plus.org/

Notepad++ includes many different programming languages out-of-the-box, but not unfortunately OpenSCAD. It does however have the facility that allows you to create and import your own language file.

This is a work in progress

## Installation

### Notepad++

Assuming Notepad++ is installed, follow the below steps. (Instructions are copied from Notepad++  User Defined Language installation instructions found here: [notepad-plus-plus/userDefinedLanguages (github.com)](https://github.com/notepad-plus-plus/userDefinedLanguages#using-a-udl-from-this-collection)

For now, you have to manually install a new User Defined Language.

1. Download the [XML Language file](./openscad.xml) .

   - From the file's page, click on either the "Raw" button (which will take you to a page where you can copy/paste the raw contents), or even easier, just click on the copy raw contents button, which will immediately place the raw contents in your clipboard for pasting.
     ![image](https://user-images.githubusercontent.com/17455758/185504202-754541f7-ee6f-4e77-9a6b-2338448e0dfa.png)
   - Do not just right click to try to download the file from either the as either of those right-click actions will download the GitHub web page for that file (which is not the UDL's XML file and will not work).

   2. Import the file by placing the file in your `userDefineLangs` folder and restarting Notepad++.  (It is also possible to use the User Defined Language dialog box and click **Import**, but that method is the "old way" and is no longer recommended: it's more steps, and harder to maintain, so there is no good reason to do it that way).  On Windows 10, this location is here: `%AppData%\Notepad++\userDefineLangs`. More details of what those steps entail can be found in the ["Import a UDL" section](https://npp-user-manual.org/docs/user-defined-language-system/#import-a-udl) of the official documentation.
   3. Download the [autoCompletion XML file](./autocompletion/openscad.xml)  and put it in the `autoCompletion\` sub-folder of your Notepad++ installation directory `C:\Program Files (x86)\Notepad++\autoCompletion`.  More details can be found in the online User Manual in the ["autoCompletion"](https://npp-user-manual.org/docs/auto-completion/) and ["configuration files details"](https://npp-user-manual.org/docs/config-files/#other-configuration-files) sections.
      - Auto-Complete can be activated by clicking CTRL-Space at any time.
      - If you want Auto-Complete to be even more automatic, you can turn it on so that it will detect the functions as you type them... Go to Settings and click Preferences. When the dialogue box appears, select the Backup/Auto-Completions tab. Under the Auto-Completion section choose your preferred options.

### OpenSCAD Configuration

1. Open OpenSCAD, Create a new file and save it.
2. In the Design menu select Automatic Reload and Compile
3. In the View menu select Hide editor
4. Leaving OpenSCAD running, now find your newly created .scad file in Windows Explorer, right hand click on it and select Edit with Notepad++
5. Arrange both OpenSCAD and Notepad++ on your screen(s) so that both can be seen at once. If you are using Windows 7 or newer, you can drag the title bars of the applications to the left and right sides of the screens to do this easily.
6. Edit your .scad file in Notepad++. Each time you save the file (CTRL+S) you will see that OpenSCAD will recompile the object. You will need to choose the Openscad language from the Languages menu. You will also need to either modify the color scheme for the language file or chose a dark theme for notepad itself. Enjoy all the advanced text editing features of Notepad++ as well as syntax highlighting of your code!!!

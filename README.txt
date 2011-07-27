Just a place to store some common config files etc

_____
FONTS

I use the excellent Envy Code R fonts in Console and Visual Studio.

See http://damieng.com/blog/tag/envy-code-r for further info


_______
CONSOLE

Console is much nicer than the Windows console window.

1. Download Console from http://sourceforge.net/projects/console/

2. Unzip and copy to Program Files. The shortcuts and reg files used here assume C:\Program Files (x86)\Console2\

3. Console/Console.xml contains my preferred settings. It includes a Git tab with an icon, which you might want to remove if you don't use Git. Copy this to C:\Users\<Profile name>\AppData\Roaming\Console\Console.xml if you want to use it.

4. Make a copy of console.exe so that you have 2 copies of the exe file:

* C:\Program Files (x86)\Console2\Console.exe
* C:\Program Files (x86)\Console2\Console2.exe

This allows you to have 2 separate shortcuts in your taskbar and start menu, each opening a different tab. The right-click "Pin to Taskbar" / "Pin to Start Menu" options don't allow you to add more than one option pointing to the same exe (I might be missing something here...)

5. The console folder includes a couple of shortcuts, which you can add to task bar / start menu if you want

6. Run the .reg file if you want to create right-click context menu options

BTW, to copy text in Console, you have to hold down the shift key and select the text!

___
GIT

After installing git, you might want to enable editing of commit messages in Notepad++

Copy Git/npp.sh to installation folder, e.g. C:\Program Files (x86)\Git\npp.sh

Run the following: 

git config --global core.editor "'C:\Program Files (x86)\Git\npp.sh'"


_____________
VISUAL STUDIO

Install the awesome Envy Code R font, then import the settings for screen scheme and a few other shortcuts.

There are a few scenarios where text color isn't quite right (e.g. font color clashes with dark background) but nothing that's bothered me enough to fix it yet.
Just a place to store some common config files etc

_______
CONSOLE

Copy console.xml to C:\Users\<Profile name>\AppData\Roaming\Console
Make a copy of console.exe
C:\Program Files (x86)\Console2\Console.exe and C:\Program Files (x86)\Console2\Console2.exe

Copy shortcuts to task bar / start menu 

The Git Bash shortcut uses console2.exe, so you can have separate entries in start menu and task bar.

___
GIT

Copy npp.sh to installation folder, e.g. C:\Program Files (x86)\Git\npp.sh

Run the following: 

git config --global core.editor "'C:\Program Files (x86)\Git\npp.sh'"
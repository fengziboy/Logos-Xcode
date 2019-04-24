# Logos-Xcode 
#### Logos Syntax Highlight in Xcode 
Logos-Xcode brings Logos Syntax Hightlight to Xcode (tested on 9.4 and 10.x). 
  
## How To Install
0 - You should make a backup of the folder `/Applications/Xcode.app/Contents/SharedFrameworks/DVTFoundation.framework/Versions/A/Resources`  
1 - Clone this repo `git clone https://github.com/s2339956/Logos-Xcode` to any place you want.  
2 - Cd to the folder with `cd Logos-Xcode`.  
3 - Assert that Xcode is completed terminated.  
4 - Run `python(3) xclangspec_generator.py`.  
5 - Run `chmod +x install.sh`, in order to give execution rights.  
6 - Run `sudo ./install.sh`, to run the installation script.  
7 - The script should explain itself, just follow the instructions.  
  
### Explaining Why It Needs Root 
To be honest, I hate when a script can only be run as root (security reasons), but in this case that's needed for writing to `/Applications/Xcode.app/Contents/SharedFrameworks/DVTFoundation.framework/Versions/A/Resources`.  
You do not need to trust my word, since all the code is open source and I suggest everyone to read.  
  
## Images
Select Editor -> Syntax Coloring -> Logos on the menu.
![SS showing autocompletion0](imgs/SS_import.png)
![SS showing autocompletion1](imgs/SS_hook.png)
![SS showing autocompletion2](imgs/SS_Live.png)
![SS showing autocompletion3](imgs/SS_end.png)
![SS showing autocompletion1](imgs/SS_c.png)
  
## Disclaimer
This code is provided `as it is`, without any `warranty`.  
READ all the code before using it, since I am not responsible if it eventually breaks any future xcode version.  
  
## Based on the work of: (See Fork) 
* Tiago Bastos (Fork) 
* Alex Karahalios (Install Script) 
* Bret Victor (Syntax file) 
* Graham Henstridge (Syntax file) 

# Syntax Highlighting Consistency 

Consistent syntax highlighting files for different code editors. Currently includes: 
* [VSCode](https://code.visualstudio.com/)
* [GTKSourceView](https://wiki.gnome.org/Projects/GtkSourceView) ([Gedit](https://gitlab.gnome.org/GNOME/gedit) (Gnome), [Mousepad](https://gitlab.xfce.org/apps/mousepad) (Xfce), [Pluma](https://github.com/mate-desktop/pluma) (MATE), [Xed](https://github.com/linuxmint/xed) (Linux Mint) etc)
* [micro](https://micro-editor.github.io/)

Currently Supported Languages: 
* C - DONE 
* Go - DONE 
* JavaScript - DONE
* Java - DONE
* JSON - DONE 
* XML - DONE
* Lua - DONE
* C++ - DONE
* Bash - DONE 
* Python 3 - 
* HTML - 
* CSS - 
* Markdown - 

Planned: 
* Support for [ranger](https://github.com/ranger/ranger) code preview and [bat](https://github.com/sharkdp/bat) file viewing  
* Add more languages (Possibly Rust, Haskell, PHP, C# etc). I will probably add new langauges if/when I start using them  
* Make script which allows quick generation of new colourschemes  
* Try to implement VSCode style "nested bracket colours" to other editors  

## Setup 

### Requirements 

At least one of the listed text editors. 

### Installation 

`make` to copy needed files to relevant folders (note, this will overwrite your VSCode `settings.json` file, the current one will be backed up to `settings.json.old`)  
`make clean` to remove all the needed files 

## Usage 

micro: `Ctrl-e` to bring up command prompt, and `set colorscheme railscastscustom` to set correct theme  
VSCode: Should work automatically  
GTKSourceView Programs: Set the theme to `Railscasts Custom`  

## Screenshots 

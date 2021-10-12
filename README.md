# GnomePI

## Post Installation script for Arch based Gnome desktop enviroments
The goal of this script is to configure the Gnome desktop enviroment with all the themes and software that I consider core components of my gnome desktop.

## Requirements
This script was made with Pseudo-Manjaro, Manjaro or Manjaro based distributions like Garuda will be required for a painless install. Many of the software/extensions installed with the script require dependancies installed by default on Manjaro. 


(Garuda Linux is recommended for a Manjaro experience without the Manjaro bloat. STRONGLY RECOMMENDED to remove Chaotic AUR if you go the route of Garuda.)

Arch users this is a post install script, as such it does not include installing any of the core components of your system such as network management, window management, etc. 

## Installation
Make the script executable (Right click the .sh file within nautilus -> click on properties -> click on Permissions -> toggle 'Allow executing file as program') and run it in a terminal like any other shell script.
or chmod 775. 

### Extension
Extensions are added automatically through the script, after the script exits gnome-session you must enter gnome-extensions and enable the installed extensions.

Fildem may require some tinkering to get working

![Screenshot from 2021-06-17 11-09-00](https://user-images.githubusercontent.com/864630/122452193-da852880-cf5d-11eb-8ca8-27e481ab682c.png)

### Arch
By the way, I use Arch.


## ConfigurationShare
The config files located within the Config directory are automatically moved to where they should* be. There may be an issue with Doom/Emacs, as the config file can either be located in ~/.doom.d OR ~/.local/doom. Emacs will only listen to one location. 


## Customization
All emacs configs are done through the doom .el files. Do not touch the Emacs files. 

Most of the customizations to the gnome-shell will be achieved through gnome-extensions. 

Glava is configured for a 1080p screen, If your screen resolution is larger, or smaller you will want to edit the config file inside the glava folder before running the script, or follow the install path after the script has ran.

![Peek 2021-10-12 13-18](https://user-images.githubusercontent.com/20939357/137024232-cf9ce954-e3c7-47a3-8ce5-7072e0181f51.gif)

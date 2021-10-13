# GnomePI (testing)

## Post Installation script for Arch based Gnome desktop enviroments
The goal of this script is to configure the Gnome desktop enviroment with all the themes and software that I consider core components of my gnome desktop.

## Initial Setup
You will need to run these commands in a terminal before running the script.

![pacman](https://user-images.githubusercontent.com/20939357/137064208-1b1c06f6-c0b7-4b38-a7e8-4c167683013f.jpg)


```
sudo pacman -Sy yay fish emacs

```
![yay](https://user-images.githubusercontent.com/20939357/137063617-ed2974d1-242a-41dc-896a-5cac6e4d8c09.jpg)

```
yay -S firefox-appmenu-bin gnome-shell-extension-pop-shell-bin gtksourceview3-fish-git mcfly-bin --noconfirm --needed
```


## Requirements
This script was made for Manjaro. It will work on garuda linux as well.

## Installation
Make the script executable (Right click the .sh file within nautilus -> click on properties -> click on Permissions -> toggle 'Allow executing file as program') and run it in a terminal like any other shell script.
or chmod 775. 

### Extension
Extensions are added automatically through the script, after the script exits gnome-session you must enter gnome-extensions and enable the installed extensions.

Fildem may require some tinkering to get working

![appmenu](https://user-images.githubusercontent.com/20939357/137024804-3e7fc617-4858-4b1b-a18e-5ee78731abaa.jpg)

Note that the Fildem global Appmenu only functions with applications that actually give it the necessary data. As such GTK4 apps will not display an appmenu.

### Arch
By the way, I use Arch.


## Configuration
The config files located within the Config directory are automatically moved to where they should* be. There may be an issue with Doom/Emacs, as the config file can either be located in ~/.doom.d OR ~/.local/doom. Emacs will only listen to one location. 


## Customization
All emacs configs are done through the doom .el files. Do not touch the Emacs files. 

![doom](https://user-images.githubusercontent.com/20939357/137025685-2cebd9fe-7535-4356-bb93-e06421150701.jpg)



Most of the customizations to the gnome-shell will be achieved through gnome-extensions. 



Glava is a nice addition to Gnome if you have the spare resources, i've opted to leave it out of this script for various reasons.
I will the glava config files incase you want to install it later. https://github.com/jarcode-foss/glava

![Peek 2021-10-12 13-18](https://user-images.githubusercontent.com/20939357/137024232-cf9ce954-e3c7-47a3-8ce5-7072e0181f51.gif)


## Original Files
If you would like to visit any of the original creators repos, go to the forked Repo's in my profile and follow them back to the original creator.
The software & extensions used in this script were not created by me.

https://github.com/Malangalag?tab=repositories

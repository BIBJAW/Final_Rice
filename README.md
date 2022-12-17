# I3-Simple DE
Just a very minimal asthetic Configuration of i3-gaps.

**Point to be noted:** Don't apply the configs blindly.It's created in an Arch system, so I don't know what will be different in other distros. Also I hope that you at least know how modules work and how to apply them. Else you are good to go with it. 
(Codes are a bit messy, I will fix them within 7th January )

## Must do to make it work: 
 -  Make these files executable using ```chmod +x```  command ==> ```/i3/scripts/powermenu``` & ```/polybar/launch.sh```

## **Descriptions:** 
- **OS:** Arch Linux
- **Window Manager:** [i3-gaps](https://github.com/Airblader/i3)
- **Bar:** [polybar](https://github.com/polybar/polybar)
- **Launcher:** [rofi](https://github.com/davatorium/rofi)
- **Compositor:** [picom-jonaburg](https://github.com/jonaburg/picom)
- **Terminal:** [alacritty](https://github.com/alacritty/alacritty)
- **Icons**: [papirus](https://www.gnome-look.org/p/1166289/)
- **Themes**: [Gruvbox Dark Borderless Theme](https://www.gnome-look.org/p/1681313/)
- **Backgrounds Repo**: [backgrounds](https://github.com/BIBJAW/backgrounds) 

## **Packages Used** :
- xorg-server
- xorg-xinit
- i3-gaps
- i3lock
- polybar
- rofi
- alacritty
- lxappearance-gtk3
- nitrogen
- ttf-roboto
- ttf-font-awesome
- picom-jonaburg

## **Keybindings**

| Keybindings  |        Actions         | 
| :---:        |        :----:          |
| mod+t        | Tiling Mode            |
| mod+e        | Tab Mode               |
| mod+s        | Stacking Mode          |
| mod+d        | rofi drun              |
| alt+d        | rofi rum               |
|alt+d         | rofi windows           |
|mod+Shift+e   |Power Menu              |
| mod+return   | alacritty terminal     |
|mod+Shift+q   | Kills a window         |
|mod+r         | resize window(vim keys)|
|mod+z         | horizontal             |
|mod+a         | vertical               |
|mod+f         | toggle fullscreen      |
|mod+space     | floating window        |
|mod+q         | focus floating window  |
|mod+p         | focus parent           |
| mod+w        | firefox                |
|mod+n         | pcmanfm                |

## **Apps assigned to Workspaces**
| Workspace Number | Assigned Apps                                             |
| :-:              | :-                                                        |
| 1                | Alacritty                                                 |
| 2                | Firefox                                                   |
| 3                |  Vscode                                                   | 
| 4                | Thunar                                                    | 
| 5                |  Telegram                                                 |
| 6                | Gimp                                                      |
| 7                | Onlyoffice, Atril, Marktext                               |
| 8                | Lxappearance,Stacer,Transmission,Yad,Gnome-Disks,Nitrogen |


## Screenshots

### UI
![DE](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/UIview.png)
### Desktop
![DE](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/DesktopView.png)
### Terminal
![Terminal](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/Terminals.png)
### File Manager
![File Manager](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/PcmanFM.png)
### VS Code
![VS Code](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/VisualStudio.png)
### Firefox
![Firefox](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/firefox.png)
### Rofi
![Launcher](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/RofiMenu.png)
### Power Menu
![Menu](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/PowerMenu.png)

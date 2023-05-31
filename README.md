# ALERT!!!: All My configs will be maintained [here](https://github.com/bibjaw99/workstation) from now on....
# I3-Simple DE
Just a very minimal asthetic Configuration of i3-gaps using Gruvbox Theme.

**Point to be noted:** Don't apply the configs blindly.It's created in an Arch system, things and package names will be a bit different in other distros, You have to keep that in mind. Also I hope that you at least know how modules work on polybar(you donnot have to know it necessarily but safe to know eg. lm_sensors is needed for displaying that temp of cpu...) and how to apply them. Else you are good to go with it. 

## installation: 
- **step:1**
```
 git clone https://github.com/BIBJAW/Final_Rice && chmod +x ~/Final_Rice/MYDE/i3/scripts/powermenu && chmod +x ~/Final_Rice/MYDE/polybar/launch.sh
 ```
 - **step:2**
 1. Now open your file manager and go to ~/Final_Rice/MYDE.
 2. Copy the **alacritty**,**i3**,**polybar**,**picom**,**rofi** folder in ~/.config (remove or backup folders with similar name first or you can change the names and revert back if something goes wrong)
 

## **Descriptions:** 
- **OS:** Arch Linux
- **Window Manager:** [i3-gaps](https://github.com/Airblader/i3)
- **Bar:** [polybar](https://github.com/polybar/polybar)
- **Launcher:** [rofi](https://github.com/davatorium/rofi)
- **Compositor:** picom
- **Terminal:** [alacritty](https://github.com/alacritty/alacritty)
- **Icons**: [papirus](https://www.gnome-look.org/p/1166289/)
- **Themes**: Orchis gtk theme
- **Backgrounds Repo**: [backgrounds](https://github.com/BIBJAW/backgrounds) 
- **Music Player:** [cmus](https://cmus.github.io/)
- **Visualizer:** [cava](https://github.com/karlstav/cava)

##  **Packages Used for the rice:**
- xorg-server
- i3-gaps
- i3lock
- polybar
- rofi
- pcmanfm
- alacritty
- lxappearance-gtk3
- nitrogen
- ttf-roboto
- ttf-font-awesome
- picom
- cava
- cmus
- mate-polkit

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
| :-:              | :-:                                                       |
| 1                | Alacritty                                                 |
| 2                | Firefox                                                   |
| 3                |  Vscode                                                   | 
| 4                | pcmanfm                                                   | 
| 5                | Telegram                                                  |
| 6                | Gimp                                                      |
| 7                | LibreOffice,Marktext,Atril                                |
| 8                | Lxappearance,Stacer,Transmission,Yad,Gnome-Disks,Nitrogen |


## Screenshots

### UI View
![DE](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/uiview.png)
### Desktop
![DE](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/desktop.png)
### Terminal
![Terminal](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/terminal.png)
### File Manager
![File Manager](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/pcman.png)
### VS Code
![VS Code](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/vscode.png)
### Rofi
![Launcher](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/rofi.png)
### Power Menu
![Menu](https://github.com/BIBJAW/i3-gruvbox/blob/main/screenshots/Power.png)

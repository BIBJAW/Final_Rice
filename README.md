# I3-Simple DE
Just a very minimal asthetic Configuration of i3-gaps.

**Point to be noted:** Don't apply the configs blindly.It's created in an Arch system, so I don't know what will be different in other distros. Also I hope that you at least know how modules work and how to apply them. Else you are good to go with it. 

## installation: 
- **step:1**
```
 git clone https://github.com/BIBJAW/Final_Rice
 chmod +x ~/Final_Rice/MYDE/i3/scripts/powermenu
 chmod +x ~/Final_Rice/MYDE/polybar/launch.sh
 ```
 - **step:2**
 1. Now open your file manager and go to ~/Final_Rice/MYDE.
 2. Copy the **alacritty**,**i3**,**polybar**,**picom**,**rofi** folder in ~/.config (remove or backup similar folders first or you can change the names and revert back if something goes wrong)
 3. Place the ahsan.rasi (rofi theme) in /usr/share/rofi/themes (that's where I keep my rofi theme usually)
 

## ** Descriptions: ** 
- **OS:** Arch Linux
- **Window Manager:** [i3-gaps](https://github.com/Airblader/i3)
- **Bar:** [polybar](https://github.com/polybar/polybar)
- **Launcher:** [rofi](https://github.com/davatorium/rofi)
- **Compositor:** [picom-jonaburg-fix](https://github.com/Arian8j2/picom-jonaburg-fix)
- **Terminal:** [alacritty](https://github.com/alacritty/alacritty)
- **Icons**: [papirus brown](https://www.gnome-look.org/p/1166289/)
- **Themes**: [Gruvbox Dark Borderless Theme](https://www.gnome-look.org/p/1681313/)
- **Backgrounds Repo**: [backgrounds](https://github.com/BIBJAW/backgrounds) 
- **Music Player:** [cmus](https://cmus.github.io/)
- **Visualizer:** [cava](https://github.com/karlstav/cava)

## **Packages Used for the rice: **
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
- picom-jonaburg-fix
- cava
- cmus 

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

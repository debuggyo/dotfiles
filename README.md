# Hyprland Dotfiles

**Install Dependencies**

```
yay -S hyprland kitty thunar hyprpaper-git fish sddm waybar-hyprland wofi hyprshot
chsh fish
sudo systemctl enable --now sddm
```

**Copy config files**

Super + Q to open a terminal
```
git clone https://github.com/debuggyo/dotfiles
thunar
```
Move the folders contained into .config

**Keybinds**

Super + T     Open Terminal *( kitty )* |

Super + E     Open File Manager *( Thunar )*

Super + Esc   Exit Hyprland and go to SDDM

Super + Q     Close active window

Super + R     Run app chooser menu *( wofi )*

Super + W     Open Web Browser *( Firefox )*




**Screenshot tools** *( hyprshot )*

Super + S     Select Region

Super + X     Full Screen *( Select Monitor )*

Super + U     Select Window

**Desktop Screenshots**
![2023-01-13-103755_hyprshot](https://user-images.githubusercontent.com/96699361/212225618-18543b87-d771-431d-8e9a-74f0a4495714.png)


*- Supply your own GTK themes, icons and fonts ( have atleast 1 Nerd Font installed for waybar to look correct )*

*- Includes background since colours are made for the background.*

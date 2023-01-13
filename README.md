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




**Screenshot** *( hyprshot )*

Super + S     Select Region

Super + X     Full Screen *( Select Monitor )*

Super + U     Select Window

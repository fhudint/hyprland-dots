### :octocat: ‎ <samp>HI THERE! THANKS FOR DROPPING BY!</samp>
This repository contains my personal configuration files for the Hyprland WM. With this configuration, I can easily manage and deploy my dotfiles across all of my devices. To use these files, simply clone this repository and run the script.

* **Window Manager** • [Hyprland ](https://github.com/hyprwm/Hyprland)🎨 Tiles Everywhere!
* **Shell** • [Zsh ](https://www.zsh.org)🐚 Shell Platform!
* **Terminal** • [WezTerm ](https://github.com/wez/wezterm) 💻 A powerful Terminal with GPU Support!
* **Panel** • [Waybar ](https://aur.archlinux.org/packages/waybar-hyprland-git)🍧 Patched Waybar Following Hyprland FAQ!
* **Notify Daemon** • [Dunst ](https://github.com/dunst-project/dunst) 🍃 Minimalist and functional!
* **Launcher** • [Rofi ](https://github.com/lbonn/rofi) 🚀 Rofi for Hyprland with Wayland Support!
* **File Manager** • [Thunar](https://github.com/xfce-mirror/thunar) for GUI and [ranger](https://github.com/ranger/ranger) 🔖 for Console!

# Setup

## Instalation

<details>
<summary><b> Installatio for Arch Linux</b></summary>

### I'am using yay as aur helper

```sh
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si

```
### Installing dependency

```sh
yay -Sy hyprland-git waybar-hyprland-git wezterm sddm-git ranger dunst zsh thunar
```

</details>

<details>
<summary><b>Regenerate the fonts cache</b></summary>
This ensures all existing caches are cleaned and regenerated for all installed fonts.

```sh
fc-cache -rv
```

</details>

## :bouquet: ‎ <samp>ACKNOWLEDGEMENTS</samp>

|   | Inspiration and Resources                                                  |
|:-:|:---------------------------------------------------------------------------|
| 1 | [linuxmobile ( リナックス )](https://github.com/linuxmobile)               |
| 2 | [Chris Titus](https://github.com/christitustech)                           |
| 3 | [rē](https://github.com/owl4ce)                                            |

## Credits
© [fhudint](https://github.com/fhudint)

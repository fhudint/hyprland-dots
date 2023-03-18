### :octocat: ‎ <samp>HI THERE! THANKS FOR DROPPING BY!</samp>
This repository contains my personal configuration files for the Hyprland WM. With this configuration, I can easily manage and deploy my dotfiles across all of my devices. To use these files, simply clone this repository and run the script.

* **Window Manager** • [Hyprland ](https://github.com/hyprwm/Hyprland)🎨 Tiles Everywhere!
* **Shell** • [Zsh ](https://www.zsh.org)🐚 Shell Platform!
* **Terminal** • [WezTerm ](https://github.com/wez/wezterm) 💻 A powerful Terminal with GPU Support!
* **Panel** • [Waybar ](https://aur.archlinux.org/packages/waybar-hyprland-git)🍧 Patched Waybar Following Hyprland FAQ!
* **Notify Daemon** • [Dunst ](https://github.com/dunst-project/dunst) 🍃 Minimalist and functional!
* **Launcher** • [Rofi ](https://github.com/lbonn/rofi) 🚀 Rofi for Hyprland with Wayland Support!
* **File Manager** • [Thunar](https://github.com/xfce-mirror/thunar) for GUI and [ranger](https://github.com/ranger/ranger) 🔖 for Console!

# SETUP

## INSTALLATION (DEPENDENCY)

<details>
<summary><b> Arch Linux Distribution</b></summary>

# Using yay as AUR helper

```sh
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si

```
# Dependency

```sh
yay -Sy hyprland-git waybar-hyprland-git wezterm sddm-git ranger dunst zsh thunar swaybg alsa-utils brightnessctl imagemagick thunar thunar-archive-plugin thunar-volman ffmpegthumbnailer tumbler
```
</details>

<details>
<summary> <b>Rofi with Wayland support</b> </summary>

> ```sh
> git clone https://github.com/lbonn/rofi.git
> cd rofi
> meson setup build
> ninja -C build
> sudo ninja -C build install
> ``` 
</details>

## INSTALLATION (PREREQUISITES)

<details>
<summary><b>Fonts</b></summary>

# Using Font Fira Code

```sh
mkdir -p $HOME/Downloads/FiraCode
cd $HOME/Downloads/FiraCode
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/FiraCode.zip
unzip '*.zip'
rm -rf '*.zip'
cd
sudo mv $HOME/Downloads/FiraCode/ /usr/share/fonts/
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

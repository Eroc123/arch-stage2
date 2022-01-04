# arch-stage2

A script to customise arch after a minimal system has been installed. 

Needed packages before running this script

- base, linux (or other kernal), linux-firmware
- git (to download this script)
- sudo

After rebooting into the new arch installation, install git and download the script

> git clone https://github.com/eroc123/arch-stage2

then change dir

> cd arch-stage2

Run install.sh

> chmod +x install.sh
> ./install.sh

# What gets installed

- base-devel
- A couple of useful monitoring utilities:
    - acpi - Allows for management and monitoring of battery
    - htop - CLI-based system monitor
- xorg
- sddm - A display manager for graphical login
- Pulseaudio audio server
    - pulseaudio
    - pulseaudio-jack
    - pulseaudio-alsa
- i3-gaps (wm)
- Thumbnailers (ffmpegthumbs & ffmpegthumbnailer)
- feh - an image previewer that is also used to set wallpapers
- Authentication applications (gnome-keyring & polkit-kde-agent)
- dunst - A notification daemon
- picom - X compositor that allows for visual effects like dual kawase blur and shadows
- Tap to click, Palm detection, and Natural Scrolling
    - Two finger leftclick
    - Three for middle click

## Appearance

- qt5ct - Configuration utility for Qt applications
- lxappearance - Configuration utility for GTK+ applications
- Breeze - The KDE Breeze suite, for both Qt and GTK+, with icons
- Font Awesome - Used for icons in the bar
- DejaVu font - System font
- Weather Icons - For the weather module in the bar

## Utilities

- nano - text editor
- PCManFM - A graphical light-weight file manager
- spectacle - KDE's screenshot utility, which can run CLI commands that are bound to keys
    - Shift+PrtScn = Copy area to clipboard
    - Ctrl+PrtScn = Opens spectacle after taking a shot
- Alacritty - A terminal
    - In case you have problems running Alacritty, termite is also installed as an alternative
- Firefox browser
- cava - Audio spectrum viewer

## Shell

- zsh

Inspired from https://github.com/mlgomez/arch-stage2

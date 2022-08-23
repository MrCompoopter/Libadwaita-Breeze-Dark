
# Libadwaita-Breeze-Dark
A "port" of the Breeze Dark GTK4 theme for Flatpak Libadwaita applications

![preview](https://github.com/MrCompoopter/Libadwaita-Breeze-Dark/blob/main/preview.png)

## What it cant do
- Automatically change color schemes based on the Plasma Color Scheme
- Properly theme normal non-libadwaita GTK4 apps
- Anticipate libadwaita apps' theme breaking custom css
- Properly theme non-flatpak libadwaia apps

## What it is
- A simple Breeze Dark theme for libadwaita
- A modification of the Breeze-GTK GTK4 theme with the Breeze Dark colorscheme in mind, made for the maximum compatibility with libadwaita apps.

## Installation
1. [Download the gtk.css file](https://github.com/MrCompoopter/Libadwaita-Breeze-Dark/releases) and put it in `~/.config/gtk-4.0/`. Backup the pre existing gtk.css file if it exists.
2. Use [Flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal) to give all flatpak apps permissions to read these directories
![directories](https://cdn.discordapp.com/attachments/452692526462140417/1011621646391586876/Screenshot_20220823_200302.png)
3. Reboot your system to make sure that all flatpak libadwaita apps would use the new theme

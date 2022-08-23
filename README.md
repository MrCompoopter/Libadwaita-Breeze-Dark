# Libadwaita-Breeze-Dark
A modification of the Breeze Dark GTK4 theme made specifically for Flatpak Libadwaita applications

![preview](https://github.com/MrCompoopter/Libadwaita-Breeze-Dark/blob/main/preview.png)

## What it is
- A barely working Breeze Dark GTK theme for apps with libadwaita.
- A modification of the Breeze-GTK GTK4 theme's css with the Breeze Dark color scheme in mind, with maximum compatibility with various libadwaita apps as a focus (even when it sometimes means making this theme less accurate to the Breeze visual style).

## What it can't do / What it isn't
- Automatically change color schemes based on the Plasma Color Scheme.
- Properly theme normal non-libadwaita GTK4 apps (breaks Breeze-GTK's GTK4 theming, though there aren't many GTK4 non-libadwaita apps anyways).
- Anticipate and/or circumvent libadwaita apps' theme-breaking custom css.
- Properly theme non-flatpak libadwaita apps (requries libadwaita to be recompiled with a custom theme).
- A one-to-one port of the GTK4 and/or GTK3 and/or QStyle Breeze style.

## Installation
1. [Download the gtk.css file](https://github.com/MrCompoopter/Libadwaita-Breeze-Dark/releases) and put it in `~/.config/gtk-4.0/`. Backup the pre existing gtk.css file if it exists.
2. Use [Flatseal](https://flathub.org/apps/details/com.github.tchx84.Flatseal) to give all flatpak apps permissions to read these directories.
![directories](https://cdn.discordapp.com/attachments/452692526462140417/1011621646391586876/Screenshot_20220823_200302.png)
3. Reboot your system to make sure that all flatpak libadwaita apps would use the new theme.

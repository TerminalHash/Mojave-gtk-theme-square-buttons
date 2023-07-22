<img src="https://github.com/vinceliuice/Sierra-gtk-theme/blob/imgs/logo.png" alt="Logo" align="right" /> Mojave Gtk Theme
======

Mojave is a Mac OSX like theme for GTK 3, GTK 2 and Gnome-Shell which supports GTK 3 and GTK 2 based desktop environments like Gnome, Pantheon, XFCE, Mate, etc.

#### This a unnoficial fork with square toolbar buttons and plume color variant, because round buttons it's bad. This not mainline project, just for lulz.

## Requirements
### GTK2 Murrine engine requirements.

- gtk-murrine-engine  `Fedora/RedHat`
- gtk2-engines-murrine  `Ubuntu/Mint/Debian`
- gtk-engine-murrine  `Arch/Manjaro`

### GTK2 pixbuf engine requirements.

- gtk2-engines  `Fedora/RedHat`
- gtk2-engines-pixbuf  `Ubuntu/Mint/Debian`
- gtk-engines  `Arch/Manjaro`

### Installed Dependency requirements.

- sassc
- optipng
- inkscape
- libglib2.0-dev-bin  `ubuntu 20.04`
- libglib2.0-dev  `ubuntu 18.04` `debian 10.03` `linux mint 19`
- libxml2-utils  `ubuntu 18.04` `debian 10.03` `linux mint 19`
- glib2-devel  `Fedora` `Redhat`

## Installation

### From source

After depends all installed you can Run

```bash
./install.sh
```

#### Install tips

Usage:  `./install.sh`  **[OPTIONS...]**

|  OPTIONS:           | |
|:--------------------|:-------------|
|-d, --dest           | Specify theme destination directory (Default: $HOME/.themes)|
|-n, --name           | Specify theme name (Default: Mojave)|
|-c, --color          | Specify theme color variant(s) **[light/dark]** (Default: All variants)|
|-o, --opacity        | Specify theme opacity variant(s) **[standard/solid]** (Default: All variants)|
|-a, --alt            | Specify titlebutton variant(s) **[standard/alt]** (Default: All variants)|
|-s, --small          | Specify titlebutton size variant(s) **[standard/small]** (Default: standard variants)|
|-t, --theme          | Specify primary theme color variant(s) **[default/blue/purple/pink/red/orange/yellow/green/grey/plume/all]** (Default: MacOS blue)|
|-i, --icon           | activities icon variant(s) **[standard/normal/gnome/ubuntu/arch/manjaro/fedora/debian/void]** (Default: standard variant)|
|-l, --libadwaita     | Install gtk4.0 theme in $HOME/.config/gtk-4.0 for libadwaita apps|
|-g, --gdm            | Install GDM theme, you should run this with sudo!|
|-r, --revert         | revert GDM theme, you should run this with sudo!|
|-h, --help           | Show this help|

#### AUR for ArchLinux/Manjaro
Search `mojave-gtk-theme-square-git` : https://aur.archlinux.org/packages/mojave-gtk-theme-git/

    yay -S mojave-gtk-theme-square-git

### Kde theme
[McMojave-kde](https://github.com/vinceliuice/McMojave-kde)

### Icon theme
[McMojave-circle](https://github.com/vinceliuice/McMojave-circle)

### Wallpaper
[Mojave default wallpapers](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/wallpapers)

## Fix entries issues of dark version on Firefox

Use "light theme" for webs on Firefox.

1. Go to `about:config`,

2. create a pref called `widget.content.gtk-theme-override` of type String,

3. and give it a value of `Mojave-light`. This will fix it.

### Firefox theme
[Intall Firefox theme](src/other/firefox)

#### Preview
![01](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/firefox01.png?raw=true)
![02](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/firefox02.png?raw=true)

## Screenshots

#### Mojave
![01](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/screenshot01.jpeg?raw=true)
![02](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/screenshot02.jpeg?raw=true)
![03](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/screenshot03.jpeg?raw=true)
![04](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/screenshot04.jpeg?raw=true)
![05](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/screenshot05.jpeg?raw=true)
![GDM_theme](https://github.com/vinceliuice/Mojave-gtk-theme/blob/images/login_screen.png?raw=true)

# TODOLIST

 

### Desktop

- [x] configure Xfce panels
- [ ] configure the Xfce window manager
- [ ] remove stroke from panels (xfwm)
- [x] find all the necessary indicators for the systray
- [ ] hide the menu as default for all applications, toolbars everywhere if possible
- [x] look for a functional, DE-independent users and groups manager (gnome-system-tools)
- [x] add necessary controls to the settings manager: audio settings (pavucontrol), users and groups (?)
- [ ] set of dedicated icons in Thunar, style toolbar and sidepane with gtk3 css
- [ ] look for a solution to integrate search capabilities, through Catfish in Thunar
- [ ] look for a solution for CSD in all Xfce applications, perhaps through their common library libxfce4ui
- [ ] reorganize menus and usability, hide unnecessary or misleading user applications, rename with convenience, patch .desktop files and/or at session level
- [ ] evalutate xfwm4 and mutter as an alternative
- [ ] find a working and contemporary browser, an email client (maybe Geary ?)
- [ ] search for essential apps and test them (eg. xfce4-terminal, gnome-system-monitor, gedit, parole, eog, evince, etc.)
- [ ] try pamac as package and update manager
- [ ] look for a method to move xfce4-pulseaudio-plugin to the systray

 

### System

- [x] create a vm
- [x] [install basic system Arch](https://wiki.archlinux.org/index.php/Installation_guide)
- [x] install most common gui library toolkits like gtk3, qt5, tk, etc.
- [x] install Xfce with panels, softwares, goodies in their latest release, devel versions from AUR
- [x] install dconf-editor, xfconf, kconfig, gconf-editor
- [x] install lightdm and lightdm-greeter-gtk, at now
- [x] configure local and install libibus, ibus-ui-gtk3
- [x] install NetworkManager and network-manager-applet-gtk3
- [x] install xfce4-power-manager
- [x] install alsa, pulseaudio and xfce4-pulseaudio-plugin
- [x] install firewalld
- [x] create a system-boilerplate to track all the changes
- [x] create a session file, based on xfce4-session
- [ ] configure pulseaudio to not lock the server
- [ ] dispose a PKGBUILD

 

### Theme

- [x] fork Adwaita theme, gtk3 commit [5428379f](https://gitlab.gnome.org/GNOME/gtk/tree/5428379fad31f1637c920d97a3d0303f606bfb6e), version 3.24.8
- [x] fork default theme, [xfwm4](https://git.xfce.org/xfce/xfwm4/tree/?h=xfwm4-4.13.2), version 4.13.2
- [x] set up the theme base, import resources from library gtk+
- [ ] look for a solution to apply dark variant in panels and panel elements without overloading
- [ ] write some css for panels and xfce4-whiskermenu-plugin
- [ ] try transitions and css animations of gtk3
- [ ] adapt for qt, qt5 and kde related

 

### Icons

- [x] fork of [ubuntu-mono-light](https://bazaar.launchpad.net/~ubuntu-art-pkg/ubuntu-themes/trunk/files/head:/ubuntu-mono-light/) and [ubuntu-mono-dark](https://bazaar.launchpad.net/~ubuntu-art-pkg/ubuntu-themes/trunk/files/head:/ubuntu-mono-dark/) icons, the latest version available
- [x] fork of [elementary-icons](https://launchpad.net/elementaryicons/3.x/3.1) icons, version 3.1
- [x] fork of [adwaita-icon-theme](https://github.com/GNOME/adwaita-icon-theme) symbolic icons, the latest version available
- [ ] adjustments to contributions and licenses
- [ ] fixes required for Spectrum-iconset (missing icons and links)
- [ ] necessary fixes for Spectrum-iconset-light and Spectrum-iconset-dark (missing icons and links)
- [ ] fix systray icons in Xfce
- [ ] replace unsuitable icons with other free set of icons
- [ ] create a script with detect for shadows and strokes elements
- [ ] remove all shadows from the icons
- [ ] simplify all icons by removing unnecessary elements (eg. elements outside the viewbox)
- [ ] modify all elements by removing strokes and adapting their dimensions
- [ ] arrange as best as possible all the icons, necessary for the pre-release

 

### Miscellaneous

- [ ] simple website, take inspiration from Alpine Linux for content organization

 

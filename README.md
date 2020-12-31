# PinePhone-openSUSE-Phosh
A repo with mobile-friendly config files for PinePhone by Pine64 running openSUSE Tumbleweed and using Phosh desktop. This repo hosts config files for basic (mostly) GUI software one could expect from a smartphone and configuration scripts to make it easier to install and configure for end users. It's a mix of native .rpm packages and flatpaks. Flatpaks are marked with [F].

This includes:

**Web Browser**: Ungoogled Chromium [F] with "uBlock Origin", "User-Agent Switcher" and "Chromium Web Store" extensions installed. 

User-Agent set by default is Chrome/Android. 

These custom flags are enabled: #enable-stacked-tab-strip (Enabled), #extension-mime-request-handling (Always prompt for install), #show-avatar-button (Never), #enable-accelerated-video-decode (Enabled), #enable-force-dark (Enabled) https://github.com/Eloston/ungoogled-chromium

**Music Player**: audacious https://audacious-media-player.org/

**Image Viewer**: nomacs - when You open a folder with images, swipe down from the top to see image roll, swipe up from the bottom to see file's metadata info or double tap to go into fullscreen mode https://nomacs.org/

**Video Player**: mpv https://mpv.io/installation/

**Text Editor**: gedit with "Word Completion" & "Find In Files" plugins https://wiki.gnome.org/Apps/Gedit

**Document Viewer**: qpdfview https://github.com/bendikro/qpdfview

**Calculator**: galculator http://galculator.mnim.org/

**Archive Manager**: file-roller https://wiki.gnome.org/Apps/FileRoller

**Terminal Emulator**: xfce4-terminal https://gitlab.xfce.org/apps/xfce4-terminal

**Custom shell**: fish http://fishshell.com/

**Process Viewer**: htop https://htop.dev/

------------------------------------

Additional software:

**Maps**: gnome-maps https://wiki.gnome.org/Apps/Maps

**Disk Usage Analyzer**: baobab https://wiki.gnome.org/action/show/Apps/DiskUsageAnalyzer?action=show&redirect=Apps%2FBaobab

**Sound Recorder**: soundrecorder https://wiki.gnome.org/Design/Apps/SoundRecorder

**Sound Converter**: gnome-sound-converter https://soundconverter.org/

**Torrent Client**: transmission-qt https://transmissionbt.com/

**Twitch Client**: orion https://alamminsalo.github.io/orion/

**YouTube Client**: freetube [F] https://freetubeapp.io/

**Instant Messenger**: telegram-desktop with 90% interface scale https://telegram.org/

-------------------------------------

Tweaks:

**dconf-editor** installed for, well, dconf configuration https://wiki.gnome.org/Apps/DconfEditor

**gnome-tweaks** installed for easy way to change icon theme or font https://wiki.gnome.org/Apps/Tweaks

**flatseal** installed for easy flatpak permissions management https://flathub.org/apps/details/com.github.tchx84.Flatseal

-------------------------------------

Theme:

**Apps**: Yaru-Green-dark https://github.com/Jannomag/Yaru-Colors

**Icons**: Papirus-Dark https://github.com/PapirusDevelopmentTeam/papirus-icon-theme

**Interface Text**: Sans Regular 10

**Document Text**: Sans Regular 10

**Monospace Text**: Monospace Regular 10

# PinePhone-openSUSE-Phosh
A repo with mobile-friendly config files for PinePhone by Pine64 running openSUSE Tumbleweed and using Phosh desktop. This repo hosts config files for basic (mostly) GUI software one could expect from a smartphone and configuration scripts to make it easier to install and configure for end users. It's a mix of native .rpm packages and flatpaks. Flatpaks are marked with [F].

This includes:

**Web Browser**: Angelfish https://invent.kde.org/plasma-mobile/plasma-angelfish - because it provides a better mobile-friendly experience & has hardware acceleration by default. AdBlock is currently NOT available.

![angelfish](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/angelfish.png)
![angelfish](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/angelfish2.png)
![angelfish](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/angelfish3.png)

[DEPRECATED, but still available in the script & repo]
Ungoogled Chromium [F] with "uBlock Origin", "User-Agent Switcher" and "Chromium Web Store" extensions installed. 

User-Agent set by default is Chrome/Android. 

These custom flags are enabled: #enable-stacked-tab-strip (Enabled), #extension-mime-request-handling (Always prompt for install), #show-avatar-button (Never), #enable-accelerated-video-decode (Enabled), #enable-force-dark (Enabled) https://github.com/Eloston/ungoogled-chromium

![ungoogled-chromium](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/ungoogled-chromium.png)
![ungoogled-chromium](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/ungoogled-chromium2.png)
![ungoogled-chromium](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/ungoogled-chromium3.png)

**Music Player**: audacious https://audacious-media-player.org/

![audacious](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/audacious.png)
![audacious](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/audacious2.png)
![audacious](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/audacious3.png)
![audacious](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/audacious4.png)

**Image Viewer**: nomacs - when You open a folder with images, swipe down from the top to see image roll, swipe up from the bottom to see file's metadata info or double tap to go into fullscreen mode https://nomacs.org/

![nomacs](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/nomacs2.png)

**Video Player**: mpv https://mpv.io/installation/

![mpv](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/mpv.png)
![mpv](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/mpv2.png)

**Text Editor**: gedit with "Word Completion" & "Find In Files" plugins https://wiki.gnome.org/Apps/Gedit

![gedit](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/gedit.png)
![gedit](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/gedit2.png)

**Document Viewer**: qpdfview https://github.com/bendikro/qpdfview

![qpdfview](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/qpdfview.png)
![qpdfview](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/qpdfview2.png)

**Calculator**: kalk https://invent.kde.org/plasma-mobile/kalk

![kalk](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/kalk.png)

**Archive Manager**: file-roller https://wiki.gnome.org/Apps/FileRoller

![file-roller](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/file-roller.png)
![file-roller](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/file-roller2.png)

**Terminal Emulator**: xfce4-terminal https://gitlab.xfce.org/apps/xfce4-terminal

![terminal](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/terminal.png)

**Custom shell**: fish http://fishshell.com/

**Process Viewer**: htop https://htop.dev/

![htop](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/htop.png)

------------------------------------

Additional software:

**Maps**: gnome-maps https://wiki.gnome.org/Apps/Maps

![maps](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/maps.png)
![maps](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/maps2.png)

**Disk Usage Analyzer**: baobab https://wiki.gnome.org/action/show/Apps/DiskUsageAnalyzer?action=show&redirect=Apps%2FBaobab

![baobab](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/baobab.png)

**Sound Recorder**: soundrecorder https://wiki.gnome.org/Design/Apps/SoundRecorder

![srecorder](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/srecorder.png)
![srecorder](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/srecorder2.png)

**Sound Converter**: gnome-sound-converter https://soundconverter.org/

![sconverter](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/sconverter.png)

**Torrent Client**: transmission-qt https://transmissionbt.com/

![transmission](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/transmission.png)
![transmission](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/transmission2.png)
![transmission](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/transmission3.png)

**Twitch Client**: orion https://alamminsalo.github.io/orion/

![orion](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/orion.png)
![orion](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/orion2.png)
![orion](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/orion3.png)

**YouTube Client**: freetube [F] https://freetubeapp.io/

![freetube](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/freetube.png)
![freetube](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/freetube2.png)

**Multimedia Downloader**: youtube-dl https://youtube-dl.org/

**Instant Messenger**: telegram-desktop with 90% interface scale https://telegram.org/

![telegram](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/telegram.png)
![telegram](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/telegram2.png)
![telegram](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/telegram3.png)

-------------------------------------

Tweaks:

**dconf-editor** installed for, well, dconf configuration https://wiki.gnome.org/Apps/DconfEditor

![dconf](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/dconf.png)

**gnome-tweaks** installed for easy way to change icon theme or font https://wiki.gnome.org/Apps/Tweaks

![tweaks](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/tweaks.png)
![tweaks](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/tweaks2.png)

**flatseal** [F] installed for easy flatpak permissions management https://flathub.org/apps/details/com.github.tchx84.Flatseal

![flatseal](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/flatseal.png)
![flatseal](https://github.com/perrsona1234/PinePhone-openSUSE-Phosh/blob/main/PineShots/flatseal2.png)

-------------------------------------

Theme:

**Apps**: Yaru-Green-dark https://github.com/Jannomag/Yaru-Colors

**Icons**: Papirus-Dark https://github.com/PapirusDevelopmentTeam/papirus-icon-theme

**Folders**: Papirus-Folders with GREEN color

**Interface Text**: Sans Regular 10

**Document Text**: Sans Regular 10

**Monospace Text**: Monospace Regular 10

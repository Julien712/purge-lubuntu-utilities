# purge-lubuntu-utilities

- Purge LibreOffice:

```bash
sudo apt purge -y libreoffice-core libreoffice-common ure uno-libs-private libuno-purpenvhelpergcc3-3 libuno-cppu3 libuno-sal3 libreoffice-style-breeze libreoffice-style-colibre
```

- Purge VLC:

```bash
sudo apt purge -y vlc vlc-data vlc-l10n vlc-bin vlc-plugin-samba vlc-plugin-svg vlc-plugin-notify libvlccore9
```

- Purge qpdfview, Quassel, Transmission, Imagemagick, LXimage and VIM:

```bash
sudo apt purge -y qpdfview qpdfview-pdf-poppler-plugin quassel quassel-data transmission-qt transmission-common imagemagick-6.q16 imagemagick-6-common imagemagick imagemagick-common lximage-qt lximage-qt-l10n vim vim-common vim-runtime
```

- Purge 2048-qt, qps, screengrab, skanlite, noblenote, picom and compton:

```bash
sudo apt purge -y 2048-qt qps screengrab skanlite noblenote picom compton
```

- Purge all : 

```bash
sudo apt purge -y libreoffice-core libreoffice-common ure uno-libs-private libuno-purpenvhelpergcc3-3 libuno-cppu3 libuno-sal3 libreoffice-style-breeze libreoffice-style-colibre
sudo apt purge -y vlc vlc-data vlc-l10n vlc-bin vlc-plugin-samba vlc-plugin-svg vlc-plugin-notify libvlccore9
sudo apt purge -y qpdfview qpdfview-pdf-poppler-plugin quassel quassel-data transmission-qt transmission-common imagemagick-6.q16 imagemagick-6-common imagemagick imagemagick-common lximage-qt lximage-qt-l10n vim vim-common vim-runtime
sudo apt purge -y 2048-qt qps screengrab skanlite noblenote picom compton
```

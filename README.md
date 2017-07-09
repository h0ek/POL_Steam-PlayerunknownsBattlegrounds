# POL_Steam-PlayerunknownsBattlegrounds
PlayOnLinux script for Playerunknown's Battlegrounds

This script will configure PlayOnLinux with Wine Staging x64 which allow to install and play [Playerunknown's Battlegrounds](https://www.playbattlegrounds.com/) game.

Required:

[PlayOnLinux](https://www.playonlinux.com/pl/download.html) >=4.2.10

[Wine](http://www.wine-staging.com/news.html) >= 2.10_staging

VCRUN2015 installed using winetricks
```WINEARCH=win64 WINEPREFIX=$HOME/.PlayOnLinux/wineprefix/Steam/ winetricks vcrun2015```

Warning! This script allow you to install game but it's not playable yet. Work is in progress. Fingers crossed.

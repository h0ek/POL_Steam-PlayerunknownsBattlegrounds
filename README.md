# POL_Steam-PlayerunknownsBattlegrounds
PlayOnLinux script for Playerunknown's Battlegrounds

This script will configure PlayOnLinux with Wine Staging x64 which allow to install and play [Playerunknown's Battlegrounds](https://www.playbattlegrounds.com/) game.

Required:

[PlayOnLinux](https://www.playonlinux.com/pl/download.html) >=4.2.10

[Wine](http://www.wine-staging.com/news.html) >= 3.6

[VCRUN2015](https://www.microsoft.com/en-US/download/details.aspx?id=48145) (use winetricks)

Go to Virtual Drive settings in PlayOnLinux and choose Miscellaneous tab -> Run Shell and paste below command.

```WINEARCH=win64 WINEPREFIX=$HOME/.PlayOnLinux/wineprefix/Steam/ winetricks vcrun2015```

Warning! This script allow you to install game but it's not playable yet. Work is in progress. Fingers crossed.

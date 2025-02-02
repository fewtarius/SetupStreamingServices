## Setup Streaming Services
This script will provide a UI to select any URLs found in the `data/links.index` source file, and will create desktop icons and add them to Steam.  It is compatible with all devices running SteamOS.

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/SteamFork/SetupStreamingServices/main/.images/20240709.jpg"/></td>
  </tr>
</table>

### Supported URLs
The list below is based on the index found in the source tree and may not contain the full list.  Review [data/links.index](/data/links.index) for the most up-to-date data.

* [ABC IView](https://iview.abc.net.au)
* [Amazon Luna](https://luna.amazon.com/)
* [Amazon Prime Video](https://www.amazon.com/video)
* [Antstream](https://live.antstream.com/)
* [Apple TV](https://tv.apple.com/)
* [Binge](https://binge.com.au)
* [BBC iPlayer](https://www.bbc.co.uk/iplayer/)
* [Crave](https://www.crave.ca/)
* [Criterion Channel](https://www.criterionchannel.com)
* [Crunchyroll](https://www.crunchyroll.com/)
* [Curiosity Stream](https://curiositystream.com)
* [Discord](https://discord.com/app)
* [Disney+](https://www.disneyplus.com/)
* [DocPlay](https://www.docplay.com)
* [Dropout](https://www.dropout.tv/browse)
* [Emby Theater](https://emby.media/)
* [HBO Max](https://www.max.com/)
* [Home Assistant](https://demo.home-assistant.io/)
* [Hulu](https://www.hulu.com/)
* [Kanopy](https://www.kanopy.com)
* [Nebula](https://nebula.tv/)
* [Netflix](https://www.netflix.com/)
* [Paramount+](https://www.paramountplus.com/)
* [Peacock TV](https://www.peacocktv.com/)
* [Plex](https://app.plex.tv/)
* [Pocket Casts](https://play.pocketcasts.com)
* [SBS Ondemand](https://www.sbs.com.au/ondemand/)
* [Spotify](https://open.spotify.com/)
* [Stan](https://www.stan.com.au)
* [TikTok](https://www.tiktok.com/)
* [Twitch](https://www.twitch.tv/)
* [Twitter](https://twitter.com/)
* [Vimeo](https://vimeo.com/)
* [Xbox Game Pass Streaming](https://www.xbox.com/play)
* [YouTube Music](https://music.youtube.com/)
* [YouTube TV](https://tv.youtube.com/)
* [YouTube](https://www.youtube.com/)
* [webRcade](https://play.webrcade.com/)

### Installation
Before running this script, be sure to switch to desktop mode and install Google Chrome from the discovery software center.  Once completed, open `konsole`, and paste the installation script to get started.

```
curl -L https://github.com/SteamFork/SetupStreamingServices/raw/main/install.sh | bash
```

Return to Gamescope, and use the [SteamGridDB](https://github.com/SteamGridDB/decky-steamgriddb) Decky plugin to add images to the new streaming services launchers.

### Uninstalling
1. Delete the launchers from Steam.
2. Remove the related .desktop files from ~/Applications.
3. Delete steamfork-browser-open from ~/bin.

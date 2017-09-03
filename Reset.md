# ![Logo](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Logos/WebTools-48x48.png) Factory Reset

### WebTools Menu
The Factory Reset will return WebTools to the same condition it was in, the very first time you installed WebTools.

This can be useful if a plug-in has become lost to WebTools or if some unknown plug-in has failed to migrate or for many other issues.

You will need to migrate your previously installed plug-ins once again after using the Factory Reset button.

See the [[UAS (Unsupported App Store)|UAS]]

### Manually
You'll need to delete two directories, as well as one file, and then restart your Plex Media Server

* WebTools Cache directory
  * Locate the [Cache Directory](https://support.plex.tv/hc/en-us/articles/202967376-Clearing-Plugin-Channel-Agent-HTTP-Caches), and delete the directory named `com.plexapp.plugins.WebTools`
  * Support Directory, by doing the following:
    * Locate the [Cache Directory](https://support.plex.tv/hc/en-us/articles/202967376-Clearing-Plugin-Channel-Agent-HTTP-Caches)
    * Go one directory up
    * Go into the directory named `Data`
    * Delete the Directory named `com.plexapp.plugins.WebTools`
  * Channel Prefs
    * Locate the [Cache Directory](https://support.plex.tv/hc/en-us/articles/202967376-Clearing-Plugin-Channel-Agent-HTTP-Caches)
    * Go one directory up
    * Go into the directory named `Preferences`
    * Delete the File named `com.plexapp.plugins.WebTools.xml`


***

[[Home|Home]] | [[Back|Change-Log]] | [[Next|WT-Forum]]
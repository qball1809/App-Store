# ![Logo](https://github.com/ukdtom/WebTools.bundle/blob/master/Wiki/WebTools/Logos/WebTools-48x48.png) Frequently Asked Questions

**Note:** This page is constantly updated, and is based on the feedback from the [Plex Forums support thread:](https://forums.plex.tv/discussion/288191)

## FAQ (Frequently Asked Questions):
* Q1: I manually installed Webtools, but when PMS is restarted, the WebTools.bundle directory is removed?
  * Most likely, you also installed WebTools under the `Resource/Plug-ins-XXXX`directory as well. You must delete it from that location, and then manually reinstall WebTools in the [`Library/Plug-Ins`](https://support.plex.tv/hc/en-us/articles/201106098) directory
* Q2: When I browse to `http://IP_OF_PMS:33400` nothing happens
  * Make sure that you opened your PMS server's firewall to port 33400 and 33443
* Q3: WebTools is not working, and you asked me for the WebTools logs. Where are they located
  * Make a zip file of the [entire logs](https://support.plex.tv/hc/en-us/articles/200250417-Plex-Media-Server-Log-Files) directory, including sub-directories, and **do not** use the PMS built in "Download logs" functionality
* Q4: When I click on the link in the Channels View, nothing happens
  * You should not click on it, type the URL in to your browser
* Q5: I see untranslated strings for my language, but when clicking on the Language tab, it does say 100% for my language
  * Most likely, the translation was done after the version of WebTools was released. Simply click on the button named [["Force Language Translation Update"|Language]]

***

[[Home|Home]] | [[Back|Known Issues]] | [[Next|Credits]]
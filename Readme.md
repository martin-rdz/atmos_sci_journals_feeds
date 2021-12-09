# RSS feeds of atmospheric science journals


## Feeds

Exchanging information between feed readers can be done via the [OPML format](https://en.wikipedia.org/wiki/OPML), which can be directly imported into most feed readers.
At least for [RSSOwl](#RSSOwlnix) also filters and tags can be included.
Currently, the following feeds are included into the [atmos_sci_journals_feeds.opml](atmos_sci_journals_feeds.opml) file:

- [ACP - recent papers](https://acp.copernicus.org/articles/xml/rss2_0.xml)
- [AMT - recent papers](https://amt.copernicus.org/articles/xml/rss2_0.xml)
- [ANGEO - recent papers](https://angeo.copernicus.org/articles/xml/rss2_0.xml)
- [GMD - recent papers](https://gmd.copernicus.org/articles/xml/rss2_0.xml)
- [BAMS](https://journals.ametsoc.org/journalissuetocrss/journals/bams/bams-overview.xml)
- [JAMC](https://journals.ametsoc.org/journalissuetocrss/journals/apme/apme-overview.xml)
- [JAOTech](https://journals.ametsoc.org/journalissuetocrss/journals/atot/atot-overview.xml)
- [Journal of Climate](https://journals.ametsoc.org/journalissuetocrss/journals/clim/clim-overview.xml)
- [JAS](https://journals.ametsoc.org/journalissuetocrss/journals/atsc/atsc-overview.xml)
- [Monthly Weather Review](https://journals.ametsoc.org/journalissuetocrss/journals/mwre/mwre-overview.xml)
- [Weather and Forecasting](https://journals.ametsoc.org/journalissuetocrss/journals/wefo/wefo-overview.xml)
- [JMSJ](http://jmsj.metsoc.jp/RSS.xml)
- [JGR: Atmospheres](https://agupubs.onlinelibrary.wiley.com/action/showFeed?jc=21698996&amp;type=etoc&amp;feed=rss)
- [QJRMS](https://rmets.onlinelibrary.wiley.com/action/showFeed?jc=1477870X&amp;type=etoc&amp;feed=rss)
- [Nature Geoscience](http://feeds.nature.com/ngeo/rss/current)
- [npj Climate and Atmospheric Science](http://feeds.nature.com/npjclimatsci/rss/current)
- [Geophysical Research Letters](https://agupubs.onlinelibrary.wiley.com/feed/19448007/most-recent)


## Readers
Regrettably Google Reader was discontinued and I could not find a full replacement.
For destop applications RSSOwlnix comes rather close, but with the disadvantage, that it cannot aggregate in the background (i.e., without opening the software regularly).

### RSSOwlnix

- Fork of RSSOwl (https://github.com/Xyrio/RSSOwlnix)
- java-based, quite powerful (filters, tags, saved searches, ...)
- Setup
    - Download the a version from the releases https://github.com/Xyrio/RSSOwlnix/releases (expand the `Assets`)
    - upack the `.zip` and run executable (`RSSOwlnix.exe`)
    - Import the `atmos_sci_journals_feeds.opml` file: `File/Import...`

### other options

- [QuiteRss](https://quiterss.org/) (only briefly looked into it)
- [Feedly](https://feedly.com/) (seemed rather limited without the Pro option)
- Thunderbird (did not try it myself, seems less powerful)
- Tiny Tiny RSS (self-hosted web reader; did not try it)


## Contribute
If you have any corrections or suggestions, please raise an issue or create a pull request.

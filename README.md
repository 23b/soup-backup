# 23b/soup-backup
This fork replaces wget with curl to make it mac compatible.

```sh
$ chmod 700 soup-backup
$ ./soup-backup http://www.soup.io/export/dead23cafe42babe17n0n00b.rss
```

First make the file executable.

Then call the script with your soup export RSS URL as the single argument. To
determine the export URL: Go to your soup, login, and open the options panel.
You'll find the export URL under 'Privacy'.

The export RSS file and the enclosures will be saved in your current working
directory. This script requires *curl* and xsltproc.

https://github.com/neingeist/soup-backup

# alternatives to this

### schlabber

This a python3 scraper: downloads text/video/etc, incl. meta, creates monthly folders
https://github.com/Blickfeldkurier/schlabber

How to get this to work on mac:
using [homebrew](https://brew.sh):
```sh
$ brew install python3
$ pip3 install requests
$ pip3 install beautifulsoup4
$ chmod 700 shlabber.py
$ ./shlabber.py kitchen
```

### ripsoup

Another python scraper
https://github.com/rixx/ripsoup
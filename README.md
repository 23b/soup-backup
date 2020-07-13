# 23b fork of neingeist/soup-backup
This fork replaces wget with curl to make it mac compatible.

To make the file executable run

```sh
$ chmod 700 ./soup-backup
```

then follow the instructions from neingeist

## neingeist soup-backup

This script saves your soup including enclosures and might kill your cat
(laughing or not.) A little .sh by neingeist (http://nein.gei.st.)

Usage: 

  ./soup-backup http://www.soup.io/export/dead23cafe42babe17n0n00b.rss

Call the script with your soup export RSS URL as the single argument. To
determine the export URL: Go to your soup, login, and open the options panel.
You'll find the export URL under 'Privacy'.

The export RSS file and the enclosures will be saved in your current working
directory. This script requires wget and xsltproc.

* https://github.com/neingeist/soup-backup

# alternativ

## schlabber

This a python3 scraper: downloads text/video/etc, incl. meta, creates monthly folders
* https://github.com/Blickfeldkurier/schlabber

How to get this to work on mac:
using [homebrew](https://brew.sh):
```sh
$ brew install python3
$ pip3 install requests
$ pip3 install beautifulsoup4
$ chmod 700 shlabber.py
$ ./shlabber.py kitchen
```

## ripsoup

Another python scraper
* https://github.com/rixx/ripsoup
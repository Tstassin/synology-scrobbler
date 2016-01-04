# synology-scrobbler

Download files (Download zip button) :
- INFO
- Scrobbler.php
- fujirou_common.php
- lyric.php

In file lyric.php, replace (line 26) the words USER and PASSWORD with your last.fm username and password, save the changes.

Windows users use 7-Zip application, from within the File Manager of the 7-Zip application
- Select the 4 files
- right-click the selection and "7-Zip"->"Add to archive..."
- Select archive format "tar"
- Click "OK"
- You now have SOMENAME.tar file
- From within the File Manager of the 7-Zip application again
- right-click the SOMENAME.tar file and "7-Zip"->"Add to archive..."
- Select archive format "gzip"
- Select word size "258"
- Click "OK"
- You now have the SOMENAME.tar.gz file
- Rename it to SOMENAME.aum

Go to your synology diskstation DSM -> Audio Station -> Settings -> Lyrics Plugin
Click add, select the SOMENAME.aum file, upload it.
Don't forget to validate activation of the new module by checking it's checkbox and saving settings.

Here you go, you now have for every song full lyrics and last.fm scrobbling

T. Stassin

Credits to great work from :

Fujirou http://fujirou2.blogspot.be/2013/02/lyricwiki-complete-lyric-lyrics-module.html

Ben-xo https://github.com/ben-xo/PHP-Scrobbler/blob/master/Scrobbler.php

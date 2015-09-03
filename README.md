# crontab
```bash
50 23 * * * /home/braeden/Auto-run.sh
0 19 * * * /home/Diskmonitor.sh
30 23 * * * rsync --ignore-existing -av --progress --itemize-changes --delete /media/braeden/Media/ /home/braeden/MediaBackup
10 23 * * * rsync --ignore-existing -av --progress --itemize-changes --delete /home/braeden/Videos /media/braeden/Media/Video\Editing/
20 23 * * * rsync --ignore-existing -av --progress --itemize-changes --delete /home/braeden/Pictures /media/braeden/Media/Pictures/PicturesHDD/
```

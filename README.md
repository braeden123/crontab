# crontab
```bash
50 23 * * * /home/braeden/Auto-run.sh
0 19 * * * /home/Diskmonitor.sh
30 23 * * * rsync --ignore-existing -av --progress --itemize-changes /media/braeden/Media/ /home/braeden/MediaBackup
```

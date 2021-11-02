# Extract GPS data from video files

Command below extracts geotagging from video using a GPX format file.

```sh
$ exiftool -p gpx.fmt -ee my_video.mp4 > geotag.gpx
```

## References

- http://gpxviewer.1bestlink.net/
- https://exiftool.org/geotag.html#GPX
- https://github.com/exiftool/exiftool/tree/master/fmt_files
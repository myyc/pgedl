pgedl
=====

`pgedl` (*Pretty Google Earth downloader*) is a simple tool that downloads
images through the *Pretty Google Earth* API, together with their metadata
in JSON format, in case you want to keep the details. If this fails, it
just downloads the image from its *Earth View* URL.

::

    usage: pgedl [-h] [-o directory] id

    Download Pretty Google Earth wallpapers.

    positional arguments:
      id                    the id of the wallpaper to be downloaded (e.g. 6311)

    optional arguments:
      -h, --help            show this help message and exit
      -o directory, --output directory
                            the output directory (default: ~/.gearth)

# VitaHub

A Gtk application written in Python that allows you to easily stream your PS Vita's screen using the vita-udcd-uvc plugin by xerpi.

![Image of main stream menu](https://i.ibb.co/Kwk4Rch/Screenshot-from-2020-10-08-21-03-04.png)

**Current features:**
* Stream PS Vita screen at one of five resolutions
* Enable 60fps on lower resolutions
* Record stream to a file at 30fps or 60fps (requires mkvtoolnix to fix framerate of recorded file)
* Config file to set default options

**Planned features:**
* Backup and restore PS Vita save files over USB or FTP

**Requirements:**
* Python 3
* [opencv-python 4.4.0.44](https://pypi.org/project/opencv-python/)
* [PyGObject 3.38.0](https://pypi.org/project/PyGObject/)
* [mkvtoolnix](https://mkvtoolnix.download/downloads.html) (Optional, only needed to fix framerate issue of recorded videos)
<!-- * [psutil 5.7.2](https://pypi.org/project/psutil/) -->
* [PSVita UDCD USB Video Class plugin](https://github.com/xerpi/vita-udcd-uvc)



**Installation:**
1. Install Python 3 and the above Python packages
2. Install xerpi's vita-udcd-uvc plugin
3. Clone/download this repo
4. Run Main.py using Python 3

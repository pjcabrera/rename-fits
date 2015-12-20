# rename-fits
Checks the FITS header for DATE-OBS, EXPTIME, and FILTER values, then renames FITS files to match the ESA/PSA and NASA/PDS archive filename format

Usage: renameFITS.py [options]

Copyright 2015 PJ Cabrera - Licensed under the Apache License 2.0
http://www.apache.org/licenses/LICENSE-2.0

Options:

  --version                         show program's version number and exit

  -h, --help                        show this help message and exit

  --in=PATH                         set input path [default: ./]

  --out=PATH                        set output path [default: ./renamed/]

  -i INITIALS, --initials=INITIALS  set your initials [default: none]

  -o OBJ, --object=OBJ              set the object name [default: 67P]

  -m, --move                        don't keep original files; rename & move files to outpath

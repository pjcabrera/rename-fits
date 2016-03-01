# rename-fits
Checks the FITS header for DATE-OBS, EXPTIME, and FILTER values, then renames FITS files to match the ESA/PSA and NASA/PDS archive filename format

Written by PJ Cabrera

With improvements and suggestions by Tony Angel

**Note: before running, you need to install astropy.**

**If you installed the Anaconda Python environment, you don't need to install astropy. It's already installed.**

To install Astropy from source, you can either use

**pip install astropy**


Alternatively, you can download a tarball for the latest release of astropy from PyPI, then expand the tarfile and run:

**python setup.py install**

Once you install Python and astropy, run the script from the command line with:

**python /path/to/the/script/rename-fits.py --in=/path/to/your/files/ --out=/path/to/renamed-copies/ -i place-your-initials-here**

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

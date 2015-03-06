# digcom
## Overview
A helpful script to identify LOCKSS Archival Units for Digital Commons collections. The script prints a list of all archival unit parameters and ids for a given collection for reference and import into a LOCKSS Title DB.

## Usage
$ ./digcom.py -h

    Usage: digcom.py {--lockss|--metaarchive} [--tdb-title=TITLE] MANIFESTPAGEURL

Options:

    --version            show program's version number and exit
  
    -h, --help           show this help message and exit

  Output mode:
  
    -l, --lockss       LOCKSS output mode
    
    -m, --metaarchive  MetaArchive output mode

  LOCKSS options:
  
    --tdb-title=TITLE  output TDB fragment for title TITLE

## License
See LICENSE.txt

# Rogue-MySQL-Server

The script starts a MySQL server that requests and retrieves files from clients that connect to it.

## Features
- Single file retrieval or specify a file-list
- Specify a number of attempts to use for each file
- Tested on Windows and Linux

```
usage: RogueSQL [-h] [-p port] [-f filename] [-l filelist] [-a attempts] [-v]
                [-d]

Rogue MySQL server

optional arguments:
  -h, --help   show this help message and exit
  -p port      port to run the server on
  -f filename  specify a single filename to retrieve
  -l filelist  path to file with list of files for download
  -a attempts  how many times to request a file before giving up
  -v           toggle verbosity
  -d           log debug messages
```

All downloaded files will be contained in `Downloads` folder.






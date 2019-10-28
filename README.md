# obp-gen-mobi
Convert ebooks from epub to mobi format

## How to run this tool
### Setup
This script requires `calibre` to be installed on your system. On Debian (or Debian-based distributions) this package can be installed via

`apt-get install calibre`

### Run
To run the process, place a copy of the **epub edition of the book** in the _obp-gen-mobi_ folder. Finally, run:

`bash run prefix`

where _prefix_ is the name of the book; i.e.: `bash run Screpanti-Labour-Value`.

### Clean-up

`bash clean [-y]`

would remove temporary files (untracked files and folders stored in the _obp-gen-mobi_ folder). The script asks for the user's confirmation before removing the files, but if you are running this as part of a script you might want to use the`-y` flag to bypass the confirmation.
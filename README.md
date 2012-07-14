Torcl
=====

Torcl is a command line interface to search and download torrent files.  It's written in bash and relies on edbrowse and aria2c.

Prerequisites
-------------

edbrowse http://the-brannons.com/edbrowse/

aria2c http://aria2.sourceforge.net/

Installation
------------

Put torcl somewhere on your path and make it executable.  Something like this:

cp torcl $HOME/bin/

chmod +x $HOME/bin/torcl

Usage
-----

Run torcl

Type 'search <some terms>' to search for torrents.  The list will be output with some numbers on the left.  The source is isohunt.com.

Type 'download <number>' to download the relevant torrent.  Give it a second to finish it.

Type 'torrent' to begin downloading from the torrent file you just grabbed.

Type 'help', or anything else, to print a short usage message.

Press "ctrl-c" to exit.  Torcl does clean up after itself, deleting temporary files and killing sub-processes.

Todo
----

- Check for the prerequisite programs
- Cleanup the output
- Add sources other than isohunt
rastapatch
==========

This is rastapatch, a patch file colorizer. Highlights changed words (as good
as it can guess) in unidiff patch files.

(c) Copyright 2012 by Neels Janosch Hofmeyr <neels@hofmeyr.de>, published
    under the General Public License v3, except for the part copied from
    termcolor.py, which is clearly marked with its own terms in the source.

Naming:
I am not a Rasta in any way; the colors I chose to colorize the diffs,
completely by random, ended up resembling "rasta colors", that's all.

The project home page is http://hofmeyr.de/rastapatch/

Source is available at https://github.com/neeels/rastapatch

Usage:

  rastapatch myfix.patch

  svn diff | rastapatch - | less -R

TODO: rastapatch is not streamy yet, i.e. it reads the entire input before
      starting to print its output.

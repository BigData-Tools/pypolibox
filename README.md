*pypolibox* is part of a database-to-text generation (NLG) software built
on Python 2.6, the Natural Language Toolkit I{NLTK} and Nicholas
Fitzgerald's *pydocplanner*.

Using a database of technical books and some user input, pypolibox generates
sentences descriptions. These descriptions are then used by the *OpenCCG*
surface realiser to generate written sentences in German.


# Installation #

Please install Python 2.6, python-nltk and python-argparse before running
pypolibox. In order to generate sentences (instead of abstract sentence
descriptions), you will need to install
[OpenCCG](http://openccg.sourceforge.net/). You will also need a copy of the
correspoding German OpenCCG grammar fragment (written by Martin Oltmann, not
released yet).


# Usage #

Please see `__init__.py` (and/or generate the complete documentation with
epydoc).


# Licence #

None yet. You may read the code and run it in a non-commercial setting, though.
(My thesis advisor has given me the permission to open source this project, but
has not decided on a license, yet.)

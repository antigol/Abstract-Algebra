This package attempts to implemenent finite abstract algebra in python.
It is written by Naftali Harris and licensed under the GNU General Public
License, Version 3.

INSTALLATION
============

    $ sudo python setup.py install


USAGE
=====

    $ python3
    Python 3.5.3 (default, Jan 19 2017, 14:11:04)
    [GCC 6.3.0 20170118] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>> from absalg import *
    >>> print(Zn(2) * Zn(2))
    e: (0, 0)
    a: (0, 1)
    b: (1, 0)
    c: (1, 1)

       | e | a | b | c |
    ---+---+---+---+---+
     e | e | a | b | c |
    ---+---+---+---+---+
     a | a | e | c | b |
    ---+---+---+---+---+
     b | b | c | e | a |
    ---+---+---+---+---+
     c | c | b | a | e |
    ---+---+---+---+---+

    >>>  


LICENSE INFO
============

See "COPYING"

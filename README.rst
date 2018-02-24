empyscripts
###########

.. image:: https://travis-ci.org/empymod/empyscripts.svg?branch=master
   :target: https://travis-ci.org/empymod/empyscripts
   :alt: Travis-CI
.. image:: https://coveralls.io/repos/github/empymod/empyscripts/badge.svg?branch=master
   :target: https://coveralls.io/github/empymod/empyscripts?branch=master
   :alt: Coveralls

This repo contains *add-ons* for the electromagnetic modeller **empymod**.
These add-ons provide some very specific, additional functionalities:

  - ``tmtemod``: Return up- and down-going TM/TE-mode contributions for
    x-directed electric sources and receivers, which are located in the same
    layer.
  - ``fdesign``: Design digital linear filters for the Hankel and Fourier
    transforms.

There is also ``empyscripts.versions()``, which can be used to show date, time,
and package version information at the end of a notebook or script:

  - ``versions('HTML')`` for Jupyter Notebooks, and
  - ``versions()`` for IPython, QT, and Python consoles.

For information regarding installation and empymod have a look at
https://empymod.github.io.


License information
===================

Copyright 2017-2018 Dieter Werthmüller

Licensed under the Apache License, Version 2.0. See the ``LICENSE``-file or the
documentation for more information.
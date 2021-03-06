==============
pytest-astropy
==============

This is a meta-package that pulls in the dependencies that are used by
`astropy`_ and some `affiliated packages`_ for testing. It can also be used for
testing packages that are not affiliated with the Astropy project.

.. _astropy: https://astropy.org/en/latest/
.. _affiliated packages: https://astropy.org/affiliated

Dependencies
------------

The following dependencies are installed by this package:
* The `pytest`_ testing framework for Python
* `pytest-remotedata`_, a ``pytest`` plugin used for controlling access to data
  files hosted online
* `pytest-doctestplus`_, a ``pytest`` plugin that provides advanced features
  for testing example code in documentation
* `pytest-openfiles`_, a ``pytest`` plugin for detecting file handles that were
  inadvertently left open at the end of unit tests
* `pytest-mpl`_, a ``pytest`` plugin that facilitates image comparison for
  `matplotlib`_ figures
* `pytest-arraydiff`_, a ``pytest`` plugin that enables the generation and
  comparison of data arrays produced during unit tests

.. _pytest: https://doc.pytest.org
.. _pytest-remotedata: https://github.com/astropy/pytest-remotedata
.. _pytest-doctestplus: https://github.com/astropy/pytest-doctestplus
.. _pytest-openfiles: https://github.com/astropy/pytest-openfiles
.. _pytest-mpl: https://github.com/matplotlib/pytest-mpl
.. _matplotlib: https://matplotlib.org
.. _pytest-arraydiff: https://github.com/astrofrog/pytest-arraydiff

Installation
------------

The ``pytest-astropy`` plugin can be installed using ``pip``::

    $ pip install pytest-astropy

It is also possible to install the latest development version from the source
repository::

    $ git clone https://github.com/astropy/pytest-astropy
    $ cd pytest-astropy
    $ python ./setup.py install

In either case, the plugin will automatically be registered for use with
``pytest``.

Development Status
------------------

Questions, bug reports, and feature requests can be submitted on `github`_.

.. _github: https://github.com/astropy/pytest-astropy

License
-------
This package is licensed under a 3-clause BSD style license - see the
``LICENSE.rst`` file.

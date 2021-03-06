.. figure:: http://i.imgur.com/vzC5zmA.gif
   :alt: 

|Build Status| |Documentation Status| |Dependency Status| |Codecov|

|PyPI version| |PyPI| |License|

SAWS
====

To view the latest ``README``, ``docs``, and ``code`` visit the GitHub
repo:

https://github.com/donnemartin/saws

To submit bugs or feature requests, visit the issue tracker:

https://github.com/donnemartin/saws/issues

Changelog
=========

0.2.1 (2015-09-23)
------------------

Bug Fixes
~~~~~~~~~

-  Fixed `#29 <https://github.com/donnemartin/saws/issues/29>`__:
   Dependency python-prompt-toolkit > 0.50 breaks saws.

0.2.0 (2015-09-22)
------------------

Features
~~~~~~~~

-  Added support for
   `#18 <https://github.com/donnemartin/saws/issues/18>`__: Multiple
   syntax highlighting themes.

-  Added improved support for
   `#17 <https://github.com/donnemartin/saws/issues/17>`__: Execute
   shell commands within ``SAWS``, including piping.

Bug Fixes
~~~~~~~~~

-  Fixed `#21 <https://github.com/donnemartin/saws/issues/21>`__:
   Current command is overwritten on screen when refreshing resources
   with F5, by jonathanslenders.

Updates
~~~~~~~

-  Updated ``README`` installation section with:

   -  ``Virtualenv`` instructions.
   -  Details on how to run AWS named profiles/credentials.
   -  Supported/tested platforms.

-  Updated ``README`` developer installation section with a new command
   to build the docs.

-  Updated docs.

0.1.1 (2015-09-21)
------------------

Bug Fixes
~~~~~~~~~

-  Fixed `#14 <https://github.com/donnemartin/saws/issues/14>`__: Fuzzy
   completions are sometimes showing incorrect completions for built-in
   commands and subcommands.

Updates
~~~~~~~

-  Updated ``README`` installation section on how to run ``SAWS``.

-  Updated docs.

-  Updated description, download url, license, and classifiers in
   setup.py.

0.1.0 (2015-09-21)
------------------

-  Initial release.

.. |Build Status| image:: https://travis-ci.org/donnemartin/saws.svg?branch=master
   :target: https://travis-ci.org/donnemartin/saws
.. |Documentation Status| image:: https://readthedocs.org/projects/saws/badge/?version=latest
   :target: http://saws.readthedocs.org/en/latest/?badge=latest
.. |Dependency Status| image:: https://gemnasium.com/donnemartin/saws.svg
   :target: https://gemnasium.com/donnemartin/saws
.. |Codecov| image:: https://img.shields.io/codecov/c/github/donnemartin/saws.svg
   :target: https://codecov.io/github/donnemartin/saws/saws
.. |PyPI version| image:: https://badge.fury.io/py/saws.svg
   :target: http://badge.fury.io/py/saws
.. |PyPI| image:: https://img.shields.io/pypi/pyversions/saws.svg
   :target: https://pypi.python.org/pypi/saws/
.. |License| image:: http://img.shields.io/:license-apache-blue.svg
   :target: http://www.apache.org/licenses/LICENSE-2.0.html

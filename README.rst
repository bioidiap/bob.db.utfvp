.. vim: set fileencoding=utf-8 :
.. Wed 03 Aug 2016 09:05:32 CEST

.. image:: http://img.shields.io/badge/docs-stable-yellow.png
   :target: http://pythonhosted.org/bob.db.utfvp/index.html
.. image:: http://img.shields.io/badge/docs-latest-orange.png
   :target: https://www.idiap.ch/software/bob/docs/latest/bioidiap/bob.db.utfvp/master/index.html
.. image:: https://travis-ci.org/bioidiap/bob.db.utfvp.svg?branch=master
   :target: https://travis-ci.org/bioidiap/bob.db.utfvp
.. image:: https://coveralls.io/repos/bioidiap/bob.db.utfvp/badge.svg?branch=master
   :target: https://coveralls.io/r/bioidiap/bob.db.utfvp
.. image:: https://img.shields.io/badge/github-master-0000c0.png
   :target: https://github.com/bioidiap/bob.db.utfvp/tree/master
.. image:: http://img.shields.io/pypi/v/bob.db.utfvp.png
   :target: https://pypi.python.org/pypi/bob.db.utfvp
.. image:: http://img.shields.io/pypi/dm/bob.db.utfvp.png
   :target: https://pypi.python.org/pypi/bob.db.utfvp
.. image:: https://img.shields.io/badge/raw-data--files-a000a0.png
   :target: http://www.sas.ewi.utwente.nl


=============================================
 UTFVP Fingervein Database Interface for Bob
=============================================

This package contains an interface for the evaluation protocols of the `UTFVP
Fingervein Database`_. Notice this package does not contain the raw data files
from this dataset, which need to be obtained through the link above.


Installation
------------

This package only contains database access functions so it is easy to
programatically reproduce evaluation results obtained in papers. You normally
don't install this package, unless you're modifying it. Instead, install one of
our top-level frameworks for vein image processing, such as ``bob.bio.vein``.


.. Write your references here:
.. _bob: https://www.idiap.ch/software/bob
.. _utfvp fingervein database: http://www.sas.ewi.utwente.nl

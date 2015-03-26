Swiss Army Knife for Data Work.
===============================

For details read the main package docstring.

Open source software licensed under the MIT license.

Install
-------

1. Install setuptools

2. Either install directy from PyPI usinging easy_install:
  
    $ easy_install datautil

   OR install from the source obtainable from the mercurial/git repository:

    $ hg clone https://github.com/okfn/datautil

    or

    $ git clone https://github.com/okfn/datautil.git
  
## Tests

1. Ensure you also have install 'xlrd' and 'gdata' (options mentioned 
   in setup.py) and nose (for running tests):

    $ easy_install nose xlrd gdata

2. Run the tests:

    $ nosetests datautil/tests/

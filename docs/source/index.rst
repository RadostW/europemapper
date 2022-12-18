europemapper Documentation
==================================

.. toctree::
   :hidden:
   :maxdepth: 1

europemapper is a python package for making Wikipedia style maps or choropleths in SVG format.

How to install
''''''''''''''

.. prompt:: bash $ auto

  $ python3 -m pip install europemapper

and you'll be good to go.

Package contents
''''''''''''''''

.. automodule:: europemapper.europemapper
   :members:
   
Example use
'''''''''''

.. prompt:: python >>> auto

    >>> import europemapper
    >>> europemapper.make_map('poland_in_europe.svg',{"pl":"green"})
    
    
.. prompt:: python >>> auto

    >>> import europemapper
    >>> style = {'at': 'red', 'ba': 'red', 'be': 'red', 'bg': 'red', 'by': 'red', 'ch': 'red', 'cy': 'red', 'cz': 'red', 'de': 'red', 'dk': 'red', 'ee': 'red', 'es': 'red', 'fi': 'red', 'fr': 'red', 'gr': 'red', 'hr': 'red', 'hu': 'red', 'ie': 'red', 'is': 'red', 'it': 'red', 'lt': 'red', 'lu': 'red', 'lv': 'red', 'md': 'red', 'me': 'red', 'mk': 'red', 'mt': 'red', 'nl': 'red', 'no': 'red', 'pl': 'red', 'pt': 'red', 'ro': 'red', 'rs': 'red', 'se': 'red', 'si': 'red', 'sk': 'red', 'xk': 'red', 'ua': 'red', 'gb': 'red'}
    >>> europemapper.make_map('european_countries.svg',style)


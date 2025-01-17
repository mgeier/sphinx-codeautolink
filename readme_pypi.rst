sphinx-codeautolink
===================
|pyversions| |downloads| |license| |readthedocs|

Automatic links from Python code examples to reference documentation
at the flick of a switch!
sphinx-codeautolink analyses the code in your documentation
and inserts links to definitions that you use.

For a live demo, see our online documentation on
`Read The Docs <https://sphinx-codeautolink.rtfd.org>`_.

Installation
------------
sphinx-codeautolink can be installed from the Package Index via ``pip``.

.. code:: sh

   $ pip install sphinx-codeautolink

Note that the library is in early development, so version pinning is advised.
To enable sphinx-codeautolink, modify the extension list in ``conf.py``.
Note that the extension name uses an underscore rather than a hyphen.

.. code:: python

   extensions = [
       ...,
       "sphinx_codeautolink",
   ]

That's it! Now your code examples are linked.
For ways of concatenating multiple examples
and setting default import statements among other things,
have a look at the online documentation.

.. |pyversions| image:: https://img.shields.io/pypi/pyversions/sphinx-codeautolink
   :alt: Python versions

.. |downloads| image:: https://img.shields.io/pypi/dm/sphinx-codeautolink
   :alt: monthly downloads

.. |license| image:: https://img.shields.io/badge/License-MIT-blue.svg
   :target: https://choosealicense.com/licenses/mit
   :alt: License: MIT

.. |readthedocs| image:: https://rtfd.org/projects/sphinx-codeautolink/badge/?version=stable
   :target: https://sphinx-codeautolink.rtfd.org/en/stable/
   :alt: documentation

xlutils documentation
=====================

This package provides a collection of utilities for working with Excel
files. Since these utilities may require either or both of the :mod:`xlrd`
and :mod:`xlwt` packages, they are collected together here, separate from either
package. The utilities are grouped into several modules within the package, each
of them is documented below:

:doc:`xlutils.copy <copy>`
  Tools for copying :class:`xlrd.Book` objects to :py:class:`xlwt.Workbook.Workbook` objects.

:doc:`xlutils.display <display>`
  Utility functions for displaying information about :mod:`xlrd`-related
  objects in a user-friendly and safe fashion.

:doc:`xlutils.filter <filter>`
  A mini framework for splitting and filtering existing Excel files into new
  Excel files.

:doc:`xlutils.margins <margins>`
  Tools for finding how much of an Excel file contains useful data.

:doc:`xlutils.save <save>`
  Tools for serializing :class:`xlrd.Book` objects back to Excel files.

:doc:`xlutils.styles <styles>`
  Tools for working with formatting information expressed the styles
  found in Excel files.

.. toctree::
   :hidden:

   copy.txt
   display.txt
   filter.txt
   margins.txt
   save.txt
   styles.txt


Working with xlutils
--------------------

The following sections describe how to install the package, contribute
to its development and the usual boilerplate:

.. toctree::
   :maxdepth: 1

   installation.txt
   development.txt
   api.txt
   changes.txt
   license.txt

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


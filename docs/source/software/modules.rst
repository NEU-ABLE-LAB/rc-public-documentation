.. _using_module:

*************
Using Module
*************

The module system on Discovery includes many commonly used scientific software packages
that you can load in your path when you need it and unload it when you no longer need it.

Use the ``module avail`` command to show a list of the most currently available software on Discovery.

.. note::

   Some modules might conflict with each other, resulting in the software not behaving as expected.
   Also, if there are multiple versions of software, and you load more than one version of the software,
   only the latest version will be used. Use ``module list`` to view the modules you currently have loaded in your path.

.. tip::

   Use the ``which`` command to display which version of a software package you have in your path.
   For example, ``which python`` will display the version of python that you have in your path.


Module commands
===============
The following are common module commands that are useful for interacting with software packages on Discovery.


.. list-table::
   :widths: 20 100
   :header-rows: 1

   * - Module Command
     - Function
   * - ``module avail``
     - View a list of all of the available software packages on Discovery that you can load
   * - ``module list``
     - Displays a list of the software packages currently loaded in your path
   * - ``module show <module name>``
     - View the details of a software package
   * - ``module load <module name>``
     - Load a software package into your environment
   * - ``module unload <module name>``
     - Remove a single software package from your environment
   * - ``module purge``
     - Removes all of the loaded software packages from your environment

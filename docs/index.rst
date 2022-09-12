.. MDMolecule documentation master file, created by
   sphinx-quickstart on Mon Sep 12 16:30:45 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to MDMolecule's documentation!
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


.. contents:: Table of Contents

-----------------
About the module
-----------------
This module defines the HDMolecule class closely inspired by one
of the ASE example at: https://wiki.fysik.dtu.dk/ase/tutorials/atomization.html

------------------------------
Functions in class HDMolecule
------------------------------

~~~~~~~~~~~
Atom_energy
~~~~~~~~~~~
    Calculate the energy of one separated atom of the element the 
    homonuclear diatomic molecule consists of using the ASE EMT energy
    calculator.

        Returns:
            float: the energy of the atom in eV

~~~~~~~~~~~~~~~~
Molecule_energy
~~~~~~~~~~~~~~~~
    Calculate the energy of the homonuclear diatomic molecule using
    the ASE EMT energy calculator.

   Returns:
      float: the energy of the molecule in eV

~~~~~~~~~~~~~~~~~~~
Atomization_energy
~~~~~~~~~~~~~~~~~~~
    Calculate the atomization energy of the homonuclear diatomic
    molecule using the ASE EMT energy calculator.

    The atomization energy is the energy it takes to break apart a
    molecule into separate atoms. It is calculated as: the energy
    of the individual atoms - the energy of the molecule.

      Returns:
         float: the atomization energy of the molecule in eV

~~~~~~~~~~~
Analyze_N2
~~~~~~~~~~~
    Creats an object N2 of the class HDMolecule. 

    Prints the nitrogen atom energy, molecule energy and atomization energy, all in eV.

~~~~~~~~~~~~~~~
Analyze_exp_N2
~~~~~~~~~~~~~~~
    Print out an energy analysis an N2 molecule with a
    bond length of 1.1 Å as found in experiments.

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

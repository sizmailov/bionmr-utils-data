===================================================
Atom/Residue convertion tables for Amber <-> Charmm
===================================================

Columns description
-------------------

1. ``residue_index`` - sequential number of residue
 
   * ``0`` stands for first residue
   * ``-1`` stands for last residue
   * ``1`` stands for any residue

1. ``amber_aName`` - amber atom name 

1. ``amber_rName`` - amber residue name  

1. ``charmm_aName`` - charmm atom name 

1. ``charmm_rName`` - charmm residue name 


1. ``amber_rNames`` - ``|``-separated list of amber resdiue names, no spaces. 


Combined records example
------------------------
Next two tables are considered equivalent:

.. code-block:: text

    residue_index,amber_rNames,amber_aName,charmm_aName
    0,DA5|DT5|DG5|DC5,HO5',H5T

and 

.. code-block:: text

    residue_index,amber_rNames,amber_aName,charmm_aName
    0,DA5,HO5',H5T
    0,DT5,HO5',H5T
    0,DG5,HO5',H5T
    0,DC5,HO5',H5T





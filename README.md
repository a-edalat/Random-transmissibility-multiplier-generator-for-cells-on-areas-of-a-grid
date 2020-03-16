# Random transmissibility multiplier generator for cells on areas of a grid

This script is designed to create MULTX, MULTX-, MULTY, MULTY- for a dual porosity system with values currently only applied to the fracture cells.

There are two separte versions created,

In the first instance:
User needs to provide the dimensions of their model, and the folder they wish the output files to be saved at, the script saves the output for each of the four keywords with GRDECL format in that location.

On the second instance:
Script can read an existing FIPNUM or similar property, understands its dimension and create a transmissibility generator for it. This instance can be modified to work on the part of the grid, based on specific values in FIPNUM rather than working on the whole grid.

# Random transmissibility multiplier generator for cells on areas of a grid

This script is designed to create MULTX, MULTX-, MULTY, MULTY- for a dual porosity system wih values currently only applied to the fracture cells.

User need to provide the dimensions of their model, and the folder they wish the output files to be saved at, the script saves the output for each of the four keywords with GRDECL format in that location.

Current limitation:
It populates the values to the whole model, and user cannot isolate an area.

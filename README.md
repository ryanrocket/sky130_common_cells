# sky130_common_cells
A repository of common cells in GDS format for the SKY130 process. 

## Cell Design / Derivation
The basis of the cell designs come from the original macros provided in the PDK for Magic. Cells were then manipulated into more usable structures in compliance with the DRC. All cells have been checked for passing DRC. 

## Naming Conventions
How the cell names are structured for ease of use.

### MOSFETs
Struct: (n/p)mos\_(vth)\_(w/l)\_(fingers)\_(repeat-y)\_(guarded)

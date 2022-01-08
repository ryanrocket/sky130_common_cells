# sky130_common_cells
A repository of common cells in GDS format for the SKY130 process. 

## Cell Design / Derivation
The basis of the cell designs come from the original macros provided in the PDK for Magic. Cells were then manipulated into more usable structures in compliance with the DRC. All cells have been checked for passing DRC. 

## Naming Conventions
How the cell names are structured for ease of use.

### MOSFETs
Example name: nmos_1v8_1w15_f1_m3_g
 - nmos = NFET
 - 1v8 = Voltage Threshold
 - 1w15 = W/L = 1/.15
 - f1 = 1 Finger
 - m3 = Repeat 3 in y-direction
 - g = guard ring present

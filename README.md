# Terminal_Tedium_Patches
Pure Data patches  for the mxmxmx's Terminal Tedium Eurorack module 
(with raspberry PI zero and PD Vanilla used for this patches)

# 8-tapes.pd
## 1.01
8-tapes is a granular algorithm for the Terminal Tedium that have 8 indipendent tapes. 
1 second that you can record per tape. 
For each tape you can read a section that goes from 1 millisecond to the full recording of 1 second.
Pitch control and 3 way to records the arrays:
  - tedium_input 23 record all the arrays
  - tedium_input 25 record one array at every tap
  - tedium_input 24 start the automatic recording of one array at time

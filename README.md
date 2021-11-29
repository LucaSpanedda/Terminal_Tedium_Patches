# Terminal_Tedium_Patches
Pure Data patches  for the mxmxmx's Terminal Tedium Eurorack module 
(with raspberry PI zero and PD Vanilla used for this patches)

# autostart.pd
This patch is opened as the Mother-patch- use the third button on the panel of the TT
module, for change the patch: 
1/2 trigger close a patch, 2/2 trigger open the next patch
the test patch is opened by default.

# 6-tapes.pd
6-tapes is a granular algorithm for the mxmxmx's Terminal Tedium 
that have 6 indipendent tapes. 
1 second that you can record per tape. 
For each tape you can read a section that goes from 1 millisecond to the full recording of 1 second.

### Knobs:
  - adc0 control the grain dimension
  - adc1 control the clock of generation for every grain (density)
  - adc2 control the pitch: original up to 8 ocataves
  - adc3 control the amp of the direct sound: ADC
  - adc4 control the amp of the granulation
  - adc5 control the clock of the automatic recorded when actived: tedium_input 24
  - 
### 3 way to records the arrays:
  - tedium_input 23 record all the arrays
  - tedium_input 25 record one array at every tap
  - tedium_input 24 start the automatic recording of one array at time


### 1.00
granular read of 1 voice 


### 0.00 - 0.99
patch for test and study the mxmxmx's Terminal Tedium

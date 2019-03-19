---
layout: default
title: Beer DNA extraction
image: /images/protocols/beer-dna-extraction.jpg
---

## Requirements

The most important: **a bootle of beer (33cl)**. In our first prototype, we used a Chimay red.

Needed consumables
- 10x 50ml Falcon tubes
- 4x 5ml Eppendorf tubes
- 4ml Tris-buffer pH7.4 1M
- Pipette tips
- Ethanol bath
- 2ml Lysis buffer: 2% Triton X-100, 1% SDS, 10mM NaCl, 10mM Tris HCl, 1mM EDTA
- Magnetic beads (SPRI beads to purify DNA, AMPure Beads XP or similar; check-out https://www.ncbi.nlm.nih.gov/pubmed/22267522 for cheap and functional SPRI beads)
- 70% Ethanol solution
- DNA purification Columns such as https://tinyurl.com/y29rg4my
- 750µl Buffer PE

Needed material
- 1x 500ml Erlenmeyer
- 1x Transfer Pipette
- P10 pipette
- P20 pipette
- P200 pipette
- P1000 pipette
- P5000 pipette
- (Thermo-regulated) Centrifuge
- Vortex
- Magnet
- Spectrophotometer (Nanodrop)

## Beer DNA extraction

0. Pre-cooled the centrifuge so that it starts at 4℃. This is optional. But we hypothesize that keeping the beer at the preferred drinking temperature improves the sequencing results [proof is needed].

### Extract the yeast from the beer

1. Shake the beer bottle (a bit)
2. Transfer into an 1000ml Erlenmeyer flask (the big glass that looks like a triangle)
    
    You should carefully shake it to remove most of the CO2
    
3. Transfer the beer (not the foam) into 50ml Falcon tubes using a large pipette 
   
   - Make sure each tube gets the same quantity (to balance the centrifuge)
   - Put a lid on each tube but don't close them until the next step (CO2 needs to be evacuated)
   
4. Put the tubes (with the lids) in the centrifuge for 10 min at full-speed and 4℃
   
   This step separates the liquid phase and the solid phase (which contains yeast among other things)
   
5. Discard carefully the supernatant either by pipetting or by pouring the liquid phase. But anyway, be sure that the pellet remains in the Falcon.
6. Transfer 1ml of Tris-buffer to the Falcon. Mix by pipetting to resolve the pellet. Afterwards, no solid phase should be visible and the solution should turned into a brownish color.
7. Transfer the solution into a 1.5ml Eppendorf tube.
8. Put the tubes into the centrifuge one more time for about 5 min at full-speed
9. Discard the supernatant and add 200µl of lysis buffer. Mix carefully by pipetting up abd down (at least 10 times) to resolve the pellet.

### Break the cell membranes of the yeasts

1. Repeat 2 times
  a) Put the tubes into the ethanol bath (-80℃) for 2 min
  b) Put the tubes in boiling water (100℃) for 2 min
  c) Vortex the tubes for 30s
  
### Extract the DNA from the cell

Now we want to extract DNA from the tubes, which also contains buffer and cell
garbage (steps 17 to 22). 

Gist: we add SPRI beads in a buffer containing PEG and NaCl so that the DNA binds 
to the beads. We use a magnet to capture the beads with the DNA. Then, we wash and 
repeat pretty much the same step: that time, beads will attach to the tube and the 
liquid will contain our DNA. In our case, we used an addition kit for this second step.

1. Bind DNA to the magnetic beads
  1. Combine the content of the tubes into 2 50µl Eppendorf tubes
  2. Vortex the buffer with beads
  3. Compute the needed quantity of beads
  
   We need a certain ratio of beads given the DNA we have
   
  4. Add the needed quantity of beads
  5. Incubate for 5 min
  6. Vortex the two samples
  7. Use either a magnet or a magnetic rack to attach the beads for 1 min
2. Washing
  1. Remove carefully the liquid from the tubes using pipette
  2. Add µl of 70% Ethanol solution into each tube
  3. Put the tubes back to the magnetic rack
  4. Remove carefully the liquid, you can use a small centrifuge to help the process
3. Dry for 2 min
4. Check the purity with a spectrophotometer

To improve the purity, we a MinElute Reaction Kit 50 from Qiagen
1. Put the samples in a column
2. Centrifuge for 1 min at 17900G
3. Add 750µl Buffer PE
4. Centrifuge for 1 min at 17900G
5. Remove the liquid from the tube and put the column back
6. Centrifuge for 1 min to dry the column
7. Transfer the column out into a new tube
8. Add 11µl water
9. Centrifuge for 1 min to elude the DNA from the column
    
    The liquid into the tube now contains the DNA

10. Check the purity with a spectrophotometer
11. Freeze the DNA until library preparation






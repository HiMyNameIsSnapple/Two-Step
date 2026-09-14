---
title: "Two-Step"
author: "Lancelot Alcaraz"
description: "An ultra high-speed IDEX bedslinger"
created_at: "2026-08-30"
---

# September 6: Started CAD

Starting the CAD with the most involved. part, the X axis by importing an MGN12 rail and 2020 extrusion, 
and making a variable studio to keep everything as parametric as possible since the span of this X axis is 
likely to change once I decided on a build area and the width of the two tools. Little actual modeling, mostly just stuff in the assembly.

<img width="2896" height="1905" alt="image" src="https://github.com/user-attachments/assets/7a5585e7-f5c9-4d67-8ed9-bfa5beca040d" />

**Total time spent: 1 hour**

# September 6: Started locking in toolhead components

Added the second set of X motors, modeled a simple little belt coupler for the first toolhead and imported a bunch of stuff like the extruder, bed probe, hotend, and toolhead board. Had a bunch of random assemblies imported along with the thing do I spent a bit of time taking care of those since I want the CAD to be nice and organized. The first EBB36 model had some stuff missing (why were those holes so big??) so I imported another one, and the BTT EDDY for some reason isn't shaped like a nice rectangle so I spent the end fiddling with the mate connectors on that so it wouldn't mess up anything else when I align the center to the toolhead. Also changed some parts of the BOM, meaning likely 1 or 2 BTT EDDY's instead of Cartographer V4's, bringing down the cost somewhat but offset by the toolboard a little bit. Little by little the BOM will be more fleshed out.

<img width="2469" height="1622" alt="image" src="https://github.com/user-attachments/assets/fcb87284-3f3a-465b-9788-d00b57a37ba2" />

**Total time spent: 2.15 hours**

# September 7: Toolhead components done, fan duct on the way!

Locked in place all of the toolhead components I was going to use with mate connectors, including the fans and also put in all the hardware (that I know of.. hopefully..( for the toolhead. Got a bit distracted to go on aliexpress to find cheaper parts but found out that the first time buyer discount actually applies to the entire cart! So the BOM will have to be modified to reflect that, which I already did make a few changes to when finding linear rails and blower fans. Speaking of linear rails and blower fans, I realized I was using some random linear carriage that didn't have holes spaced 2 cm apart for some reason..? So I changed those, and got a bit frustrated with finding a 5015 blower fan model that actually reflects the blower fans I was buying (before the aliexpress thing btw), so I modeled one myself off a drawing from the amazon listing of the blower fans I was going to use, meaning those are locked in unless I somehow find the same supplier from aliexpress. After that, made the first version of the fan ducts and struggled with making a cavity from the assembly geometry to import into SimFlow, meaning that is a problem for tomorrow. Attempt at trying to turn it into an STL in a part studio attached.

<img width="2934" height="1827" alt="image" src="https://github.com/user-attachments/assets/9e9c4bb3-ce8a-4e40-ae38-ab998e8cf4e1" />

**Total time spent: 4.55 hours**

# September 13: Fan duct is on the way this time

Made a new branch and messed around with a center of mass optimized toolhead configuration based on the Dreadnaught toolhead, but abandoned that since belt routing would be a bit harder, and it wouldn't really make sense to optimize the center of mass when the belts are already pretty far from the center of mass too. I also reconfigured the toolhead to take one 5015 since I was told that a single Vindr 5015 was better than two generic 5015's, so reconfigured around that since I need these toolheads to be as thin as possible to make IDEX make sense. When cadding the new fan duct I was a bit stuck and really was just staring at references since I was lost on how to model the fan duct geometry, but that's now pushed to tomorrow I guess. Might need to find and import some more fan duct references. Lapse now attached to the Forge journal and deleted from all these github entries for security. 

<img width="3449" height="2003" alt="image" src="https://github.com/user-attachments/assets/29044b2d-b2db-4d3d-b947-10650b65bbb0" />

**Total time spent: 0 hours**

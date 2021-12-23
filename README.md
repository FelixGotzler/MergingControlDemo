Example on SUMO's zipper-type junction and why we are trying to build our own merging control for PRT. 
It works great under "normal" conditions, but when traffic volume is constantly close to the capacity limit (but not above), the zippers behave like real-world traffic with
human drivers and consequently congestion emerges (~ 40s in the video). However, we don't want this behaviour with PRT as all vehicles will be operated centrally.
Aditionally, we want to tweak the parameters of the merging control setup and find an optimum for a given system. Those parameters include for instance the V2I range or the inter
vehicle distance at the point of merging. Furthermore, we want to analyse different approaches (slot allocation vs. prioritization) and heuristics (occupancy, speed differences, 
subsequent vehicles, ...).

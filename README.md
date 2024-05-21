# STK-Project-Files
Simulation models and scripts for trajectory analysis of spacecraft using STK and Python/MATLAB integration

**STK Analysis Workbench:** Used a combination of STK Pro and STK's Analysis Workbench capability to create vectors, custom angles, calculations, time components and temporal constraints to determine when the sensor can safely track the satellite.
Task Completed: 
-Vector Geometry Tool 
-Time Tool
-Calculation Tool 

SnapFrame: 


![STK_Anaylsis_Workbench_SnapFrame](https://github.com/Jakayla-R/STK-Scenario-Files/assets/90592223/49a10b35-13ed-44c7-8e30-c4ea91be2a8b)

**STK Coverage:** In this simulation we use STK to model Earth observing payloads attached to sensors located in 3 different orbits. 
Task completed: 
-Comupted global coverage
-Computed coverage in designated areas
-Understand a coverage grid 
-Use constraints in a coverage grid 
-Determined coverage assets
-Chose which data providers supply answers
-Created color contours pertaining to the coverage analysis in the 2D and #D Graphics windows 

SnapFrame:



![STK_coverage_SnapFrame2](https://github.com/Jakayla-R/STK-Scenario-Files/assets/90592223/0113eb3e-43e8-434b-b286-ce1c4f351c21)


**STK Astrogator:** In this simulation I launch a vehicle that followed an ascent trajectory from a launch point to an orbit insertion point.
Task Completed: 
-Inserted a Satellite object, switched the propagator to Astrogator, and used a Follow Segment. This allowed the Satellite to follow the Launch Vehicle object, to separate from the Launch Vehicle at the end of its trajectory, and to place the Satellite object into a LEO.
-Used a Target sequence, a Maneuver segment, and a Propagate segment to place the Satellite orbit into a TOI.
-Finalized its orbit by creating another Target Sequence that placed the Satellite into a GEO.
-Used an MCS Segment Summary Report to determine maneuver times, required Delta-V, estimated burn duration, and estimated fuel usage.

SnapFrame: 


![STK_Astrogator_SnapFrame2](https://github.com/Jakayla-R/STK-Scenario-Files/assets/90592223/66a246b6-8964-4695-bdf3-2a14d1446b08)


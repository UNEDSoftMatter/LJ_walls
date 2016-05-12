# LJ_walls

lammps MD scripts to perform the simulation of a fluid between two walls when the temperature of the lower wall is increased.

The script has three parts: 
- In microcanonival ensemble, fluid and walls reach equilibrium with a langevin thermostat (T= 1.5)
- Once the system is equilibrated, the temperature of the lower wall is increased (T = 10). 
- Then, the system reaches again the equilibrium. 

The process is performed in the __microcanonical ensemble__. 



# The-simulation-of-INER-190821 #
## Estimating the cross-section of Carbon target from proton beam ##

1. Gate/Geant4 v9.0 application
2. ROOT
3. Origin v8.1

## Set-up ##

- Proton beams of energies 15 MeV, 30 MeV start at the beam pipe to the 1x10x10 mm^3 target at 45 degree.
- Collimators in front of the detector consist of 2 lead bricks which made a gap of 1.5 cm and one lead brick with a hole of about 3.5 cm. 
- The HPGe detector scores the emission of prompt gamma from the target. It is placed inside a 10x10x20 cm^3 lead shield and built by the "scanner" system. 

## Physics ##

- Physics list: QGSP_BIC_HP_EMY.
- Phase Space Actor: The information of particles was obtained at the target. 
- The "scanner" System: The information of particles at the HPGe detector.

## Output ##

- The particles entering the target and the secondary particles in the target is scored via Phase Space Actor to estimate the cross-section for the simulation.
- The calibration of HPGe detector is conducted for low energies and high energies to esitimate the efficiency of experimental data.
 

NMPC-CarSim
***********

 This project uses casadi in matlab to implement a NMPC controller for a vehicle in CarSim.
  https://youtu.be/6wHSdGmxydk 

  Paper: https://ieeexplore.ieee.org/abstract/document/9047783
**************

Steps to run model:

 1. Go to CarSim2017.1_Data\Extensions\Simulink and place the file "murad_nmpc.slx"(matlab 2019a).
 2. Go to CarSim2017.1_Data\ and place the file "casadi_block_presented.m".
 3. In CarSim go to File -> import parsfile and select the file "murad_nmpc.par".
 4. Install casadi from https://web.casadi.org/get/
 5. Edit the path to casadi folder in the "casadi_block_presented.m" in the "setupImpl" function.
 6. In CarSim select send to simulink (CarSim will load a Matlab instance)
 7. Once the Simulink model is loaded, click run to start the simulation.
 

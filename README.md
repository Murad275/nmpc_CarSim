Nmpc_CarSim

 1. Go to CarSim2017.1_Data\Extensions\Simulink and place the file "murad_nmpc.slx"(matlab 2019a).
 2. Go to CarSim2017.1_Data\ and place the file "casadi_block_presented.m".
 3. In CarSim go to File -> import parsfile and select the file "murad_nmpc.par".
 4. Install casadi from https://web.casadi.org/get/
 5. Edit the path to casadi folder in the "casadi_block_presented.m" in the "setupImpl" function.
 6. In CarSim select send to simulink (CarSim will load a Matlab instance)
 7. Once Simulink loads click run to run the model.
 

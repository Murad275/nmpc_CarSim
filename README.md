NMPC-CarSim
***********

 This project uses Casadi in Matlab to implement a NMPC controller for a vehicle in CarSim.
 
  https://youtu.be/6wHSdGmxydk
  
  https://ieeexplore.ieee.org/document/9047783

 If you use this project, give us the credit by citing this work:
 
 <pre><code>@inproceedings{dawood2020nonlinear,
  title={A nonlinear model predictive controller for autonomous driving},
  author={Dawood, Murad and Abdelaziz, Mohamed and Ghoneima, M and Hammad, S},
  booktitle={2020 International Conference on Innovative Trends in Communication and Computer Engineering (ITCE)},
  pages={151--157},
  year={2020},
  organization={IEEE}
}
</code></pre>
**************

Steps to run model:

 1. Go to CarSim2017.1_Data\Extensions\Simulink and place the file "murad_nmpc.slx"(matlab 2019a).
 2. Go to CarSim2017.1_Data\ and place the file "casadi_block_presented.m".
 3. In CarSim go to File -> import parsfile and select the file "murad_nmpc.par".
 4. Install casadi from https://web.casadi.org/get/
 5. Edit the path to casadi folder in the "casadi_block_presented.m" in the "setupImpl" function.
 6. In CarSim select send to simulink (CarSim will load a Matlab instance)
 7. Once the Simulink model is loaded, click run to start the simulation.
 

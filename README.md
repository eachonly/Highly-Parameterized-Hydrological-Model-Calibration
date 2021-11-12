# Dataset for SWAT model calibration
This repository contains the dataset for the manuscript "Can Gauss-Newton algorithms outperform stochastic optimization algorithms when calibrating a highly parameterized hydrological model? A case study using SWAT" be submitted to Water Resources Research by Youwei Qin and co-authors.

This repository includes the dataset used for the three plots in the manuscript. 

  - Figure1_RawData: includes the raw trajectories data of thirteen algorithm variants, where the trajectories for the single response scenario are stored in the sub-folder "Single_Response_Scenario" and the trajectories for the multiple response scenario are stored in the sub-folder "Single_Response_Scenario". In each sub-folder, it includes: 
       - RGN_Trajectories:   includes 100 trajectories corresponding to the 100 RGN invocations;
       - PEST1_Trajectories: includes 100 trajectories corresponding to the 100 PEST1 invocations;
       - PEST2_Trajectories: includes 100 trajectories corresponding to the 100 PEST2 invocations;
       - PEST3_Trajectories: includes 100 trajectories corresponding to the 100 PEST3 invocations;
       - SCE1_Trajectories:  includes 100 trajectories corresponding to the 100 SCE1 invocations;
       - SCE2_Trajectories:  includes 100 trajectories corresponding to the 100 SCE2 invocations;
       - SCE3_Trajectories:  includes 100 trajectories corresponding to the 100 SCE3 invocations;
       - DDS1_Trajectories:  includes 100 trajectories corresponding to the 100 DDS1 invocations;
       - DDS2_Trajectories:  includes 100 trajectories corresponding to the 100 DDS1 invocations;
       - DDS3_Trajectories:  includes 100 trajectories corresponding to the 100 DDS3 invocations;
       - DDS4_Trajectories:  includes 100 trajectories corresponding to the 100 DDS4 invocations;
       - DDS5_Trajectories:  includes 100 trajectories corresponding to the 100 DDS5 invocations;
       - DDS6_Trajectories:  includes 100 trajectories corresponding to the 100 DDS6 invocations;       

  - Figure2_ProcessedData: includes the algorithm performance data at fixed budget 200, 500, 1000, 2000, 3000 and 5000 for eight algorithm variants, where the algorithm performance for the single response scenario are stored in the sub-folder "Single_Response_Scenario" and the algorithm performance for the multiple response scenario are stored in the sub-folder "Single_Response_Scenario". In each sub-folder, for example sub-folder "budget200", it includes:
       - RGN.txt:   objective function values across 100 RGN invocations at fixed budget, for example fixed budget 200;
       - PEST1.txt: objective function values across 100 PEST1 invocations at fixed budget, for example fixed budget 200;
       - PEST2.txt: objective function values across 100 PEST2 invocations at fixed budget, for example fixed budget 200;
       - PEST3.txt: objective function values across 100 PEST3 invocations at fixed budget, for example fixed budget 200;
       - SCE1.txt:  objective function values across 100 SCE1 invocations at fixed budget, for example fixed budget 200;
       - SCE2.txt:  objective function values across 100 SCE2 invocations at fixed budget, for example fixed budget 200;
       - SCE3.txt:  objective function values across 100 SCE3 invocations at fixed budget, for example fixed budget 200;
       - DDS.txt:   objective function values across 100 DDS invocations at fixed budget, for example fixed budget 200;  

  - Figure3_ProcessedData: includes the data of algorithm performance over given target NSE for eight algorithm variants, where the trajectories for the single response scenario are stored in the sub-folder "Single_Response_Scenario" and the trajectories for the multiple response scenario are stored in the sub-folder "Single_Response_Scenario". In each sub-folder, it includes:
       - NSE00.txt: proportion of invocations each optimization algorithm variant achieves solution with NSE vaues above 0.0 at fixed budget 200, 500, 1000, 2000, 3000 and 5000;
       - NSE05.txt: proportion of invocations each optimization algorithm variant achieves solution with NSE vaues above 0.5 at fixed budget 200, 500, 1000, 2000, 3000 and 5000;
       - NSE07.txt: proportion of invocations each optimization algorithm variant achieves solution with NSE vaues above 0.7 at fixed budget 200, 500, 1000, 2000, 3000 and 5000;
       - NSE08.txt: proportion of invocations each optimization algorithm variant achieves solution with NSE vaues above 0.8 at fixed budget 200, 500, 1000, 2000, 3000 and 5000;
       - NSE09.txt: proportion of invocations each optimization algorithm variant achieves solution with NSE vaues above 0.9 at fixed budget 200, 500, 1000, 2000, 3000 and 5000; 

These files are recommended to be opened with Notepad++.
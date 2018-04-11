%% Network Deployment for Maximal Energy Efficiency in Uplink with Multislope Path Loss

% This is a code package is related to the follow scientific article:
%
% Andrea Pizzo, Daniel Verenzuela, Luca Sanguinetti and Emil Björnson, "Network Deployment for Maximal Energy Efficiency 
% in Uplink with Multislope Path Loss," IEEE Transactions on Green Communications and Networking, Submitted to.
% The package contains a simulation environment, based on Matlab, that reproduces all the 
% numerical results and figures in the article. We encourage you to also perform reproducible research!
% 
%
% Abstract of Article
% This work aims to design the uplink (UL) of a cellular network for maximal energy efficiency (EE).
% Each base station (BS) is randomly deployed within a given area and is equipped with M antennas to
% serve K user equipments (UEs). A multislope (distance-dependent) path loss model is considered and linear
% processing is used, under the assumption that channel state information is acquired by using pilot sequences
% (reused across the network). Within this setting, a lower bound on the UL spectral efficiency and a realistic
% circuit power consumption model are used to evaluate the network EE. Numerical results are first used to
% compute the optimal BS density and pilot reuse factor for a Massive MIMO network with three different
% detection schemes, namely, maximum ratio combining, zero-forcing (ZF) and multicell minimum meansquared
% error. The numerical analysis shows that the EE is a unimodal function of BS density and achieves
% its maximum for a relatively small BS densification, irrespective of the employed detection scheme. This
% is in contrast to the single-slope (distance-independent) path loss model, for which the EE is a monotonic
% non-decreasing function of BS densification. Then, we concentrate on ZF and use stochastic geometry to
% compute a new lower bound on the spectral efficiency, which is then used to optimize, for a given BS
% density, the pilot reuse factor, number of BS antennas and UEs. Closed-form expressions are computed
% from which valuable insights into the interplay between the optimization variables, hardware characteristics,
% and propagation environment can be obtained.
%
%
% Content of Code Package
% The package contains 3 folders which can be used to generate the 5 simulation figures as they appear in the article. 
% The folder "ComputeULAvgErgodicSE" compute the uplink average ergodic
% spectral efficiency as seen in Theorem 2 in the article. The results
% obtained by running the main script in this folder are then saved in another folder 
% called "SimulationResults". Finally, the scripts included in the folder "GenerateSimulationFigures" 
% generate the figures in the article by using the simulation results computed beforehand. 
%
% See each script and function for further documentation. 
%
%
% License and Referencing
% This code package is licensed under the GPLv2 license. 
% If you in any way use this code for research that results in publications, please cite our original article listed above.

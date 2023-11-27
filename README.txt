
%% AUTHOR: Cansu EREN 
%% @ Copyright Cansu EREN 
%% 18/10/2023

%% File List 
%% AnteriorPosterior: The simulated data is obtained regarding the anterior-posterior position of humans towards UWB radar. 
%% MedioLateral: The simulated data is obtained regarding the anterior-posterior position of humans towards UWB radar. 
%% Simulated Data Library: The data file location of simulated breath signals on MATLAB. 

%% Additional Documents 
%% GNU General Public License v3.0: The license type of this code is given in this file. 
%% ODC Open Database License(ODbL): The license type of this data is given in this file. 
%% Flowchart.png 

FOR ELECTROMAGNETIC ANALYSIS 
1) Select file location as AnteriorPosterior or MedioLateral. 
2) Open TissueConstants.m 
3) RUN and select main file which is C:\Users\...\...\UWB Radar Breath Simulator. 
4) Electromagnetic calculations are stored in the Tissue structure file and saved as TissueAnteriorPosterior.mat or Tissuelateral.mat. 

Functions of this analysis: AttenuationConstant.m, DeflatedLungParameters.m, Impedance.m, InflatedLungParameters.m, PropogationConstant.m, ReflectionCoefficient.m, ReflectionTransmission.m, VelocityCalculation.m, SkinDepthCalculation.m.  

FOR UWB BREATH SIMULATOR
1)  Select file location as AnteriorPosterior or MedioLateral. 
2) Open Main.m. 
3) RUN and select main file which is C:\Users\...\...\UWB Radar Breath Simulator. 

All of the generated data are stored in Simulated Data Library. 

Functions of this analysis: GaussPulseGenerator.m, PathLossCalculation.m, ReceivedSignals.m, SingleBreathCoefficientCalculation.m, TimeofFlightCalculation.m

FOR DRAW DATA! 
1) Select file location as Simulated Data Library. 
2) Open DataDraw.m 
2) RUN and select main file which is C:\Users\...\...\UWB Radar Breath Simulator. 
3) Select the data type you would like to draw. 
4) Run. 

ATTENTION: First generate simulated files based on your selection to store data in Simulated Data Library. 

%% THANKS FOR READING! 






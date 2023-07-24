# barrier_breach_data
 supplemental data for Nienhuis, Heijkers, Ruessink 2021 JGR-ES
 
 This github folder contains the data and code to reproduce the figures and findings of our study. MIT License
 
 The following files are important:
 
 ModelRun1
 This folder contains the Delft3D simulation setup files.
 
 run_series_of_models.m
 This function uses barrier and storm parameters as input and copies and edits ModelRun1. It then runs the Delft3D simulations. It stores the parameters also as a .mat file.  
 
 analyze_runs.m
 Opens the .mat file generated by run_series_of_models.m It then goes throught the completed Delft3D simulation files and further populates the .mat file with simulation output, such as overwash volumes. Examples are Width.mat, StormPeak.mat, vegdensity.met
 
 Fig3,4,5,etc.
 Matlab code that uses the .mat files generated by analyze_runs.m and creates the figures as shown in the paper.
 
 Nienhuis_BarrierBreach_tables.xslx
 xls file with reduced model data and sandy field data output for easy inspection.
 
 
 
 
 
 

# urban-octo-pancake

The tool(s) being considered are: 
--1. Drilling tip
--2. Cutting Chip

Three Datasets have been used for the same, for each there are 2 seperate operational execution blocks for Regression and optimisation.

The datasets considered are private and confidential, and can't be disclosed.

The feature(s) being used here are:
------Dataset(A): 
----------In-Dependent Feature(s): 
-----------------------Speed
-----------------------Feed
-----------------------Depth of Cut/ Drill
-----------------------Roughness of the Surface
----------Dependent Features:
-----------------------Tool Wear (Tw)
-----------------------Metal removal Rate (MRR)

------Dataset(B):
----------In-Dependent Feature(s): 
-----------------------Speed
-----------------------Feed
-----------------------Depth
-----------------------Tangential Force (Ft)
-----------------------Axial Force (Fa)
----------Dependent Feature(s): 
-----------------------Beta
-----------------------Roughness of Surface (Ra)
-----------------------Metal Removal Rate (MRR)

------Dataset(C):
----------In-Dependent Feature(s): 
-----------------------Speed
-----------------------Feed
-----------------------Depth
----------Dependent Feature(s): 
-----------------------Tool Life
-----------------------Tool Wear
-----------------------Temperature

The major categorical steps for accomplishment of the tasks were: 
1. Regression
2. Hyper-Parameter Optimization 

The entire feature representation (Dependent Features) have been carried using a single-row matrix (Or Coloumn-featured) using Numpy for ease.
Throughout the Datasets, since the values at certain points weren't specific to scale, hence the values have been scaled to a certain extent for ease of operation(using np.log function).

Using certain measurement techniques, the performance and outcomes of the system have been represented at the end of the entire execution body(in tabular format).

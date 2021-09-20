# urban-octo-pancake

The tool(s) being considered are: 
--1. Drilling tip
--2. Cutting Chip

Three Datasets have been used for the same, for each there are 2 seperate operational execution blocks for Regression and optimisation.

The datasets considered are private and confidential, and can't be disclosed.

The feature(s) being used here are:
**Dataset(A):**
A. *In-Dependent Feature(s):
1. Speed
2. Feed
3. Depth of Cut/ Drill
4. Roughness of the Surface
B. *Dependent Features:
1. Tool Wear (Tw)
2. Metal removal Rate (MRR)

**Dataset(B):**
A. *In-Dependent Feature(s): 
1. Speed
2. Feed
3. Depth
4. Tangential Force (Ft)
5. Axial Force (Fa)
B *Dependent Feature(s): 
1. Beta
2. Roughness of Surface (Ra)
3. Metal Removal Rate (MRR)

**Dataset(C):
A. *In-Dependent Feature(s): 
1. Speed
2. Feed
3. Depth
B. * Dependent Feature(s): 
1. Tool Life
2. Tool Wear
3. Temperature

The major categorical steps for accomplishment of the tasks were: 
1. Regression
2. Hyper-Parameter Optimization 

The entire feature representation (Dependent Features) have been carried using a single-row matrix (Or Coloumn-featured) using Numpy for ease.
Throughout the Datasets, since the values at certain points weren't specific to scale, hence the values have been scaled to a certain extent for ease of operation(using np.log function).

Using certain measurement techniques, the performance and outcomes of the system have been represented at the end of the entire execution body(in tabular format).

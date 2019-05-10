gluc_mm_mle readme

Maximum Likelihood Estimation (MLE) of the minimal model of glucose kinetics.
The glucose minimal model is used to investigate glucose metabolism from
IntraVenous Glucose Tolerance Test (IVGTT). Estimated parameters (can) provide a measure of insulin sensitivity.

The file 'gluc_mm_mle.m' is a Matlab function that can be run from the Matlab Command Window. It includes sub-functions for parameter estimation (using Levenberg-Marquardt optimization), simulation of differential equation model and plotting. A test dataset of an IVGTT is also included.
It uses 'lsqnonlin' from the Optimization Toolbox.

To correctly interpret the results, some understanding of MLE theory is required.

--
copyright Natal van Riel, Eindhoven University of Technology, 2003
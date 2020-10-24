# GLMNET64MATLAB
GLMNET for MATLAB 64bit large arrays

This is a modified version of GLMNET for MATLAB (original source code here:https://web.stanford.edu/~hastie/glmnet_matlab/)
The original code for MATLAB was not updated for a while, and as a result, the API for mex function connecting the FORTRAN code to matlab was outdated.
This made it impossible to load and use large arrays, which are only supported in 64-bit mex API for FORTRAN.
So I've updated the source FORTRAN code to 64-bit API following the guide from here : https://www.mathworks.com/help/matlab/matlab_external/upgrading-mex-files-to-use-64-bit-api.html

I've compiled the mex file in winodws and linux, but didn't compile one for mac because I don't have one.
But you should be able to compile it yourself.

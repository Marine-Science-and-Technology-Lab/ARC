MQS_Shallow_Water_Lib C++ Shared Library

1. Prerequisites for Deployment 

Verify that version 9.12 (R2022a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2022a 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler SDK documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Starting with R2018a, MATLAB Compiler SDK generates two types of C++ shared library 
 interfaces:
- legacy, using the mwArray interface
- generic, using the MATLAB Data API introduced in R2017b
MathWorks recommends the MATLAB Data API, which uses modern C++ features for efficient 
 execution and programming.
Files for the legacy interface have not been produced for this library.
Files for the generic interface can be found in the v2\generic_interface subdirectory.


Files to Package for the Generic Interface
(in the v2\generic_interface subdirectory)
==========================================
-MQS_Shallow_Water_Lib.ctf (component technology file) 
-MQS_Shallow_Water_Libv2.hpp
-readme.txt

3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.





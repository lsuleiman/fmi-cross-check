Model : 
Modelica library model 
FMUName=CoupledClutches 
 
FMI Type :  
ModelExchange  
 
Generation Tool : 
CATIA R2015x 
 
Available Platforms : 
win32 
 
Known Errors : 
Not all <ScalarVariables variability="constant"> have their start value printed in modeldescription.xml 
 
FMUChecker : 
FMUChecker Version 2.0b3 win32 
 
run command : 
set FMUName=CoupledClutches
fmuCheck.win32.exe -e %FMUName%_cc.log -o %FMUName%_cc.csv -h 1e0 -s 25 %FMUName%.fmu 

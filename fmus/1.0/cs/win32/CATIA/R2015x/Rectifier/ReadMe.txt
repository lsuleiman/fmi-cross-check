Model : 
Modelica library model 
FMUName=Rectifier 
 
FMI Type :  
CoSimulation  
 
Generation Tool : 
CATIA R2015x 
 
Available Platforms : 
win32 
 
Known Errors : 
Not all <ScalarVariables variability="constant"> have their start value printed in modeldescription.xml 
 
FMUChecker : 
FMUChecker Version 2.0b3 win32 
 
run command : 
set FMUName=Rectifier
fmuCheck.win32.exe -l 3 -e %FMUName%_cc.log -o %FMUName%_cc.csv -h 1e0 -s 25 %FMUName%.fmu 

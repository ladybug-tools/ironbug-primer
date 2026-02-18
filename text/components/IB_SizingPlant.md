## IB_SizingPlant

![](../../images/components/IB_SizingPlant.png)


The Sizing:Plant object contains the input needed for the program to calculate plant loop flow rates and equipment capacities when autosizing. This information is initially used by components that use water for heating or cooling such as hot or chilled water coils to calculate their maximum water flow rates. These flow rates are then summed for use in calculating the Plant Loop flow rates. The program will size any number of chilled water, hot water, condenser water and other plant loops. There should be one Sizing:Plant object for each plant loop that is to be autosized.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Sz
SizingPlant 
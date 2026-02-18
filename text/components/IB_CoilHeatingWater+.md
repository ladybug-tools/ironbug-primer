## IB_CoilHeatingWater+

![](../../images/components/IB_CoilHeatingWater+.png)


This simple heating coil model only does sensible heating of the air. The simple heating coil uses the Effectiveness-NTU algorithm and assumes a cross-flow heat exchanger.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### ctrl [Required]
add a customized controller here 
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Coil
connect to air loop's supply side or other water heated system. 
* ##### ToWaterLoop
connect to hot water loop's demand side via plantBranches 
## IB_FanSystemModel+

![](../../images/components/IB_FanSystemModel+.png)


This object models fans of various types using a relatively simple engineering model. This fan can be used in variable air volume, constant volume, on-off cycling, two-speed, or multi-speed applications.  It was designed as a replacement for {Fan:ConstantVolume}, {Fan:OnOff}, {Fan:VariableVolume}, and {FanPerformance:NightVentilation}. The electric power consumed by the fan can be directly input or autosized using one of three optional methods.  For fans that can vary the volume flow rate the performance can be described using a separate performance curve or table object. Or for fans with discrete speed control the power fraction at each speed can be input directly with no need for a performance curve.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### speeds 
A field set is pair of values for the flow fraction and electric power fraction at each speed. The sets should be arranged in increasing order so that the flow fractions become larger in subsequent field sets.  Typically the highest speed level will match the design maximum and have fractions of 1.0.  This object is extensible, so additional sets of the following two fields can be added to the end of this object.  Example: 0.33,0.12 0.66,0.51 1.0,1.0 
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Fan
FanSystemModel 
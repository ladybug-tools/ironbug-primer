## IB_FanOnOff

![](../../images/components/IB_FanOnOff.png)


This object models a constant air volume fan that is intended to cycle on and off in tandem with a cooling or heating system (i.e., AUTO fan control mode). The fan can also operate continuously like {Fan:ConstantVolume}. If modeling continuous operation and this object is used as part of a system that utilizes {Coil:Heating:Fuel}, {Coil:Cooling:DX:SingleSpeed} or {Coil:Heating:DX:SingleSpeed}, the user should confirm proper air flow rates (coil and fan max flows are equal) and that the coil part-load fraction correlation(s) are appropriate (e.g., part-load fraction is less than or equal to 1 for all values of coil part-load ratio). If modeling multi-speed fan operation, this object must be used as part of a compound object that allows multiple fan speeds (e.g., {AirLoopHVAC:Unitary:Furnace:HeatCool}, {ZoneHVAC:PackagedTerminalAirConditioner}, etc.). In this case, the ratio of the compound object air flow rate to the fan's maximum air flow rate is used to determine the power at alternat.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Fan
Todo.. 
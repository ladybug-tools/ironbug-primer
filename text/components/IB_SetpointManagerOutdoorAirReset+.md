## IB_SetpointManagerOutdoorAirReset+

![](../../images/components/IB_SetpointManagerOutdoorAirReset+.png)


The Outdoor Air Reset Setpoint Manager is used to place a setpoint temperature on a system node according to the outdoor air temperature using a reset rule. The reset rule is determined by 2 points: the setpoint temperature at the outdoor air high temperature (TSetAtOAHigh) and the setpoint temperature at the outdoor air low temperature (TSetAtOALow). If the outdoor air temperature is above the outdoor air high temperature limit, the setpoint temperature is set to TSetAtOAHigh. If the outdoor air temperature is below the outdoor air low temperature limit, the setpoint temperature is set to TSetAtOALow. If the outdoor air temperature is between the outdoor air high and outdoor air low temperatures limits, the setpoint temperature is linearly interpolated between TSetAtOAHigh and TSetAtOALow. The outdoor air temperature is obtained from the weather information during the simulation. This setpoint manager can be used to place a setpoint temperature on air loop and plant loop system nodes..... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### SPM
TODO:... 
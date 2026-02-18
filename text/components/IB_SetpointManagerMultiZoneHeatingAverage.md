## IB_SetpointManagerMultiZoneHeatingAverage

![](../../images/components/IB_SetpointManagerMultiZoneHeatingAverage.png)


This setpoint manager is used to establish a supply air temperature setpoint for a central forced air HVAC system (air loop) based on the predicted sensible heating loads and actual supply air mass flow rates for all zones served by the system. For all controlled zones in the air loop (i.e., zones with a thermostat object), the setpoint manager calculates an average supply air temperature that will meet the zone heating loads based on the actual zone supply air mass flow rates (lagged by one time step). The calculated setpoint temperature is subject to the minimum and maximum setpoint temperature constraints specified by the user. When compared to a fixed heating supply air temperature setpoint, this strategy may reduce central boiler energy consumption (if the hot water temperature is also reset or there are variable speed pumps) at the cost of possible increased fan energy (if there is variable volume control for the air system).  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### minT [Required]
The minimum allowed setpoint temperature in degrees C. If the calculated setpoint temperature is less than this minimum, the setpoint is set to the minimum. The default value is 20C.  Unit: C [IP: F]  Above content copyright © 1996-2023 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 
* ##### maxT [Required]
The maximum allowed setpoint temperature in degrees C. If the calculated setpoint temperature is greater than this value, the setpoint is set to this maximum value. The default value is 50C.  Unit: C [IP: F]  Above content copyright © 1996-2023 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Outputs
* ##### SPM
TODO:... 
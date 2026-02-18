## IB_SetpointManagerWarmest

![](../../images/components/IB_SetpointManagerWarmest.png)


The Warmest Setpoint Manager resets the cooling supply air temperature of a central forced air HVAC system according to the cooling demand of the warmest zone. For each zone in the system at each system timestep, the manager calculates a supply air temperature that will meet the zone cooling load at the maximum zone supply air flow rate. The lowest of the possible supply air temperatures becomes the new supply air temperature setpoint, subject to minimum and maximum supply air temperature constraints. The resulting temperature setpoint is the highest supply air temperature that will meet the cooling requirements of all the zones. When compared to a fixed cooling supply air temperature setpoint, this strategy minimizes zone reheat coil energy (or overcooling) and central chiller energy consumption (if the chilled water temperature is also reset) at the cost of possible increased fan energy.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### minT [Required]
The minimum allowed setpoint temperature in degrees C. If the calculated setpoint temperature is less than this minimum, the setpoint is set to the minimum.  Unit: C [IP: F]  Above content copyright © 1996-2023 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 
* ##### maxT [Required]
The maximum allowed setpoint temperature in degrees C. If the calculated setpoint is greater than this value the setpoint is set to the maximum. This value is also used as the setpoint temperature when none of the zones have a cooling load.  Unit: C [IP: F]  Above content copyright © 1996-2023 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Outputs
* ##### SPM
TODO:... 
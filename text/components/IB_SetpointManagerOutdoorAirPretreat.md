## IB_SetpointManagerOutdoorAirPretreat

![](../../images/components/IB_SetpointManagerOutdoorAirPretreat.png)


The OutdoorAir Pretreat Setpoint Manager is meant to be used in conjunction with an {OutdoorAir:Mixer} object. The Outdoor air Pretreat Setpoint Manager is used to establish a temperature or humidity ratio setpoint in the outdoor air stream flowing into the ``Outdoor Air Stream Node'' of an {OutdoorAir:Mixer} object. This setpoint manager determines the required setpoint in the outdoor air stream to produce the reference setpoint in the mixed air stream after mixing with return air. For example, if the temperature setpoint at the mixed air node is 15 °C, the return air temperature is 20 °C, and the outdoor air flow fraction is 0.5, the Outdoor Air Pretreat setpoint would be set to 10 °C. Of course any type of setpoint manager can be used to establish setpoints in the outdoor air stream, but this setpoint manager is likely to be the most useful for systems which precondition outdoor air with equipment such as a DX cooling coil or desiccant dehumidifier.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### SPM
TODO:... 
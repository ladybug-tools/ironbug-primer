## IB_SetpointManagerSingleZoneHumidityMinimum

![](../../images/components/IB_SetpointManagerSingleZoneHumidityMinimum.png)


The Single Zone Minimum Humidity Setpoint Manager allows the control of a single zone minimum humidity level. This setpoint manager detects the humidity level in a control zone and, using air and moisture mass balance, calculates the supply air humidity ratio needed to maintain the zone relative humidity at or above a given setpoint. The calculated supply air humidity ratio is then used as the setpoint for the designated setpoint node. A humidifier component placed upstream of the setpoint node can then use the humidity ratio setpoint to control its moisture addition rate. The use of this object requires that a {ZoneControl:Humidistat} object be specified with a humidifying relative humidity schedule for the controlling zone. The humidistat's controlling zone must correspond with the control zone air node name specified in this setpoint manager.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### Ctrlzone [Required]
The name of the zone node for the humidity control zone (as specified in the object {ZoneHVAC:EquipmentConnections}). An IDF example for this setpoint manager is shown below with the required humidistat: SetpointManager:SingleZone:Humidity:Minimum, Zone Min Set Point Manager,  !- Name Air Loop Outlet Node,        !- Setpoint Node or NodeList Name Zone 2 Node;                 !- Control Zone Air Node Name ZoneControl:Humidistat, Zone 2 Humidistat,           !- Name ZONE 2,                      !-Zone Name Min rel Hum Set Sch2;        !- Humidifying Relative Humidity Setpoint Schedule Name 

#### Outputs
* ##### SPM
TODO:... 
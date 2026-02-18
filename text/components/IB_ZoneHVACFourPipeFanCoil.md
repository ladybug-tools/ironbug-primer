## IB_ZoneHVACFourPipeFanCoil

![](../../images/components/IB_ZoneHVACFourPipeFanCoil.png)


What is a fan coil unit? Like many HVAC terms, ``fan coil unit'' is used rather loosely. Sometimes it is used for terminal units that would be better described as powered induction units. Carrier and others use the term for the room side of refrigerant-based split systems. Here we are modeling in-room forced-convection hydronic units. The hydronic heating coil may be replaced with an electric heating coil. Typically these units are small (200–1200 cfm) and self-contained. They are mostly used in exterior zones, usually in hotels, apartments, or offices. They may be connected to ducted outside air, or have a direct outside air vent, but they do not have outside air economizers. Units with outside air economizers are marketed (in the United States) as unit ventilators. Unit ventilators are typically bigger than fan coils and are widely used in classrooms or other applications where ventilation is a priority. If a zonal unit with an outside economizer is desired, {{ZoneHVAC:UnitVentilator.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### coilH 
Heating coil to provide heating source. Can be CoilHeatingWater or CoilHeatingElectric. 
* ##### coilC 
Cooling coil to provide cooling source. Must be CoilHeatingWater. 
* ##### fan 
Can be FanOnOff, FanConstantVolume or FanVariableVolume. 
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### FCU
Connect to zone's equipment 
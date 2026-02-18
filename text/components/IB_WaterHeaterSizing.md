## IB_WaterHeaterSizing

![](../../images/components/IB_WaterHeaterSizing.png)


The WaterHeater:Sizing object is used to provide additional input data needed for designing tank volume and/or heater capacity for either the Mixed or Stratified water heaters. This object is only needed if volume or capacity is being automatically sized. There are no output variable associated with this object – sizing results are reported to the EIO output file and some predefined summary reports. A source of design input data for use with this object can be found in the current ASHRAE Handbook HVAC Applications chapter on Service Water Heating.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Sz
WaterHeaterSizing 
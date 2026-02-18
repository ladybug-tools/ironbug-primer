## IB_CoilCoolingDXSingleSpeed

![](../../images/components/IB_CoilCoolingDXSingleSpeed.png)


This DX cooling coil input requires an availability schedule, the gross rated total cooling capacity, the gross rated SHR, the gross rated COP, and the rated air volume flow rate. The latter 4 inputs determine the coil performance at the rating point (air entering the cooling coil at 26.7°C drybulb/19.4°C wetbulb and air entering the outdoor condenser coil at 35°C drybulb/23.9°C wetbulb). The rated air volume flow rate should be between 0.00004027 m³/s and 0.00006041 m³/s per watt of gross rated total cooling capacity (300 to 450 cfm/ton). The rated volumetric air flow to total cooling capacity ratio for 100% dedicated outdoor air (DOAS) application DX cooling coils should be between 0.00001677 (m3/s)/W (125 cfm/ton) and 0.00003355 (m3/s)/W (250 cfm/ton). Pumped refrigerant economizer integrated with the single speed DX cooling coil model will use exactly the same model except that performance curves use lookup table to cover the pumped refrigerant economizer and the compressor opera.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Coil
CoilCoolingDXSingleSpeed 
## IB_PhotovoltaicPerformanceEquivalentOneDiode

![](../../images/components/IB_PhotovoltaicPerformanceEquivalentOneDiode.png)


This object describes the performance characteristics of Photovoltaic (PV) modules to be modeled using an equivalent one-diode circuit. This model is also known at the 4- or 5-parameter TRNSYS model for photovoltaics. The following table shows several sample PV array types with their input values. % table 33 Where: Shunt Resistance: the value of shunt resistance is finite only if the PV Module being modeled is a thin film variety. For all crystaline silicon modules the value is essentially infinite Shunt Resistance value: 1,000,000 W (ohms) Module Heat Loss Coefficient: this value is dependent more on the array configuration than on the module itself. Module Heat Loss Coefficient value: 30 W/m2-K Module Heat Capacity: this is a typical value for a silicon based sandwich construction framed PV panel. Module Heat Capacity Value: 50,000 J/m2-K Reference Temperature: 298K (25C) Insolation at Reference Conditions: 1000 W/m2 Ambient Temperature at NOCT conditions: 293K (20C) Ins.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### pvPerf
Connect to IB_GeneratorPhotovoltaic 
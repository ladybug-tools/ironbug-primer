## IB_EvaporativeCoolerDirectResearchSpecial

![](../../images/components/IB_EvaporativeCoolerDirectResearchSpecial.png)


This cooler is similar in principal to the {EvaporativeCooler:Direct:CelDekPad}. The model differs in that it gives the user a simple way of specify the cooler effectiveness. Using the ResearchSpecial input object also allows the cooler to control the amount of cooling based on node setpoints (controlled by SetpointManagers). This avoid problems from over cooling when conditions are such that loads are low and cooling power is high. The model allows to vary the effectiveness depending on the primary air flow rates. The design effectiveness is modified by multiplying with Effectiveness Flow Fraction Modifier Curve value. The flow fraction is the ratio of the current primary airflow rate to the design flow rate. The recirculating and spray water pump power is assumed to vary with the primary air flow. The design pump power is modified using user specified pump modifier curve value. The normalized pump power modifier curve is a function of primary air flow fraction as a independent varia.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### EvapCoolerDir
EvaporativeCoolerDirectResearchSpecial 
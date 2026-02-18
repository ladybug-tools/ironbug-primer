## IB_EvaporativeCoolerIndirectResearchSpecial

![](../../images/components/IB_EvaporativeCoolerIndirectResearchSpecial.png)


This cooler is similar in principal to the {EvaporativeCooler:Indirect:CelDekPad} and {EvaporativeCooler:Indirect:WetCoil} (see Figure{fig:secondary-air-process-indirect-dry-coil-evap}, Figure{fig:evaporative-cooler-indirect-wet-coil}, and Figure{fig:secondary-air-process-indirect-wet-coil-evap}). The model differs in that it gives the user more flexibility to specify the source of secondary air. The cooler effectiveness with respect to wetbulb depression is allowed to go beyond 1.0. Using the ResearchSpecial object also allows the cooler to control the amount of cooling based on node setpoints (controlled by SetpointManagers). This avoid problems from over cooling when conditions are such that loads are low and cooling power is high. Fan power is assumed to vary linearly when the cooler is operating at less than full capacity (includes air system cycling, if any). The indirect evaporative cooler research special calculation procedure allows accounting for dry and wet effectiveness va.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### EvapCoolerIndir
EvaporativeCoolerIndirectResearchSpecial 
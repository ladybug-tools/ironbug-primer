## IB_GroundHeatExchangerHorizontalTrench

![](../../images/components/IB_GroundHeatExchangerHorizontalTrench.png)


The horizontal trench ground heat exchanger object provides an alternate interface to the detailed PipingSystem:Underground:* objects. The same underlying simulation algorithm is utilized, providing a transient numerical simulation of soil with buried pipes and a detailed surface heat balance. The input syntax is much smaller and useful for simple applications. For full flexibility, use the PipingSystem:Underground:* objects to build a detailed simulation domain and piping circuit. For information regarding the simulation algorithms, see the engineering reference document section covering the buried piping system objects. {{Field: Name}} This alpha field is used as an identifying field for the ground heat exchanger. {{Field: Inlet Node Name}} This alpha field is the name of the inlet node of this component on a plant loop, and must match other topology definitions such as branch objects. {{Field: Outlet Node Name}} This alpha field is the name of the outlet node of this component.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### GroundHX
GroundHeatExchangerHorizontalTrench 
## IB_SetpointManagerSystemNodeResetHumidity

![](../../images/components/IB_SetpointManagerSystemNodeResetHumidity.png)


The System Node Reset Setpoint Manager is used to place a humidity ratio setpoint on a system node according to the reference humidity ratio (e.g., return air or outdoor air humidity ratio) of a system node using a linear interpolation between two user-specified reference values and two user-specified setpoint values. In general, the higher the reference humidity ratio, the lower the setpoint. During the simulation, the reference humidity ratio is obtained from the user-specified reference system node. The input consists of the setpoint manager name, the control variable, the name of the node or node list affected by the setpoint, the name of the reference node name, and the data for the reset rule: setpoints at low and high reference humidity ratios, and low and high reference humidity ratios.  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### probe [Required]
Add a IB_NodeProbe to a loop first, and then connect the probe to here for setpoint manager to use. 
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### SPM
TODO.. 
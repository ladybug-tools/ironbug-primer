## IB_CurveSigmoid

![](../../images/components/IB_CurveSigmoid.png)


Input for the sigmoid curve consists of the curve name, the five coefficients, and the maximum and minimum valid independent variable values. Optional inputs for the curve minimum and maximum may be used to limit the output of the performance curve (e.g., limit extrapolation). The equation is: y = {C_1} + {{C_2}}/{\left( {{{(1 + {e^{\left[ {{({C_3 - x)}/{{C_4}}} \right]}})}^{{C_5}}}} \right)}}  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### coeffs [Required]
A list of coefficients for a sigmoid curve from C1 to C5. 
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Curve
CurveSigmoid 
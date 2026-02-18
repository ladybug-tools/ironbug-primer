## IB_CurveQuartic

![](../../images/components/IB_CurveQuartic.png)


Input for a Quartic (fourth order polynomial) curve consists of the curve name, the five coefficients, and the maximum and minimum valid independent variable values. Optional inputs for curve minimum and maximum may be used to limit the output of the performance curve (e.g., limit extrapolation). The equation represented by the quartic curve is: y = {C_1} + {C_2}x + {C_3}{x^2} + {C_4}{x^3} + {C_5}{x^4}  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### coeffs [Required]
A list of coefficients for a quartic curve from C1 to C5. 
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### Curve
CurveQuartic 
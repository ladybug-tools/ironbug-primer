## IB_ZoneHVACEnergyRecoveryVentilator

![](../../images/components/IB_ZoneHVACEnergyRecoveryVentilator.png)


The ZoneHVAC:EnergyRecoveryVentilator - stand alone energy recovery ventilator (ERV) is a single-zone HVAC component used for exhaust air heat recovery (Figure{fig:zonehvac-energyrecoveryventilator-compound}). This compound object consists of 3 required components: a generic air-to-air heat exchanger (see object Heat Exchanger:Air to Air:Generic), a supply air fan, and an exhaust air fan (see object {Fan:OnOff}). An optional controller (see object {ZoneHVAC:EnergyRecoveryVentilator:Controller}) may be used to simulate economizer (free cooling) operation, modify air flow rates based on high indoor humidity, or simulate a ``push-button'' type economizer controller. This compound object models the basic operation of supply and exhaust air fans and an air-to-air heat exchanger. The stand alone ERV operates whenever the unit is scheduled to be available (Availability schedule). The stand alone ERV object can be used in conjunction with an economizer feature whereby heat exchange is suspen.... (Due to the length of content, documentation has been shown partially)  Above content copyright © 1996-2025 EnergyPlus, all contributors. All rights reserved. EnergyPlus is a trademark of the US Department of Energy. 

#### Inputs
* ##### HeatEx [Required]
Must be HeatExchangerAirToAirSensibleAndLatent. 
* ##### spFan [Required]
Fan:OnOff. 
* ##### exFan [Required]
Fan:OnOff. 
* ##### params 
Detail settings for this HVAC object. Use Ironbug_ObjParams to set input parameters, or use Ironbug_OutputParams to set output variables. 

#### Outputs
* ##### ZoneERV
Connect to zone's equipment 
# openHASP-Energy

Plate design revised 21-03-2023

Former three spinner objects was using all mcu ressources and from time to time actually crashed the plate. They've been replaced with arc objects instead.

Arc objects colouring determined by percentage of:
- Daily solar yield / Predicted daily yield
- Solar power own consumption / Grid import
- Export to grid / Import from grid

Entire config done in configurations - no automations
Configuration examples for 480 x480 res. devices
- [GS-T3E](https://github.com/HASwitchPlate/openHASP/discussions/383) or [WT32S3-86V](https://github.com/HASwitchPlate/openHASP/discussions/435) 
- [Sunton devices](https://www.openhasp.com/0.7.0/hardware/sunton/esp32-8048s0xx/) with 480x800 res. displays
openHASP Custom Component is mandatory

![T3E openHASP Energy plate 480x480 res.](https://github.com/htvekov/openHASP-Energy/blob/main/T3E_energy_plate.png)

![Sunton openHASP Energy plate 480x800 res.](https://github.com/htvekov/openHASP-Energy/blob/main/Sunton_energy_plate.png)


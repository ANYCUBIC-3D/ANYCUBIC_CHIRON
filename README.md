# ANYCUBIC_CHIRON
ANYCUBIC CHIRON V1.2.7 based on marlin 1.1.0

-> M1000   Manual leveling

-> M1001   Auto leveling

Creating a txt, input 

M140 S0

M104 S0

M1001

Save and rename it as "Auto_leveling.gcode",copy this file to SD card. Print it from 'PRINT' menu to active auto leveling function.
If need,manual leveling likes below:

M140 S0

M104 S0

M1000

So we can easy switch manual leveing or auto leveling by "Auto_leveling.gcode" and "Manual_leveling.gcode"

Otherwise, if manual leveling activated , auto leveling will unavailable, also the Z of home position will more lower than auto leveling.
If auto leveling activated, the default Z offset is -14, acutally the current Z offset is about -16.5~-17.5, just for make sure nozzle will not friction platform. So please be patient to adjust the Z offset. 

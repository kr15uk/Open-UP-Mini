# Open-UP-Mini

UP Mini is brilliant well tuned ABS machine and for most people this conversion will bring more pain than benefit.


Reasons behind the conversion:

1. I had 4x other machines running Marlin and my slicer of choice was Cura.

2. I've started experimenting with PC-ABS and PC and wasn't 100% satisfied due to low bed/chamber temperatures for these materials.

Bed reaches only 60degree C max hence it's not regulated (it has some kind of temp sensing cutout diode soldered underneath - not familiar with this technology)
If you want to install chamber heaters you will require to have separate controller etc - pain.

3. Due to declining availability of UP replacement nozzles I had a plan to potentially upgrade this machine to more generic E3D offerings (potentially Titan Aqua)


So far I have replaced electronics with AliExpress BIQU KFB 2.0 board (space for additional mosfet board if going chamber heater route), moded bed to go over 60degree C and added thermistor - the rest is kept as stock as possible.

So far I've been unsuccessful:

1. Sensing hotend thermistor, it's not regular thermistor nor PT100 - so save some troubleshooting time I've simply strapped with capton tape regular NTC onto the heater block (temporary solution, for almost a year now :) )

2. Find a use case for UP front button and LED so it's not wired

3. Design LCD mount

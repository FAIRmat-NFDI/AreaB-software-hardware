part 1
| priority | status | subsystem | type | current model | problem with current device | requirements/parameters | function | to do | possible options | comment | ports |
| -------- | ------ | --------- | ---- | ------------- | --------------------------- | ----------------------- | -------- | ----- | ---------------- | ------- | ----- |
| 1 | | prep chamber – sample heater | current source | Topward TPS4000 | no PC connectivity | DC 30V 3A | sample heating | replace | KORAD KD3005P / driver for CAMELS exists https://botland.store/laboratory-power-supply/5496-laboratory-power-supply-korad-kd3005p-0-30v-5a-usb-5907558240610.html | | serial, usb |
| 1 | | prep chamber – sample heater | thermometer | Testo 635 | no PC connectivity | unknown thermocouple installed | sample T readout | Calibration? Replace with multimeter? | replace with ADC with ethernet port: https://controlbyweb.com/x418/ | Almost certainly TE Type K thermocouple (NiCr-Ni) https://www.pyromation.com/downloads/data/emfk_c.pdf - not quite linear, dV/dT close to 41uV/deg
| 4 | | prep chamber – sample heater | ammeter | generic handheld | no PC connectivity  | DC 3A | heating current readout | not needed if source is good | ignore? |
| 2 | | prep chamber – safety | ammeter | generic handheld | no PC connectivity | DC 2mA limit | current to ground readout | replace | 1kOhm // 2 diods // ADC ? - ask if resistance is a problem|
| 4 | | prep chamber – pumping unit  | current source  | generic old  | no PC connectivity  | DC 30V 120mA  | SECUVAC valve  | doesn’t have to be controlled remotely  | ignore
| 1 | | prep chamber – pumping unit  | pressure gauge  | combivac IT23  | screen semi-broken  |   | prep ch pressure readout  | connect to PC (ethernet and serial port are present) | | | serial, ethernet |
| 3 | | --\\--\\--  |   |   |   |   |   | replace because of screen

part 2
| priority | status | subsystem | type | current model | problem with current device | requirements/parameters | function | to do | possible options | comment | ports |
| -------- | ------ | --------- | ---- | ------------- | --------------------------- | ----------------------- | -------- | ----- | ---------------- | ------- | ----- |
| 1 | | spm chamber – pumping unit  | pressure gauge  | Gamma vacuum 4/2/6/p  | ok  |   | stm ch pressure readout  | connect to PC (ethernet and serial port are present) | | might be useful for driver - not quite the right model though: https://www.tspi.at/2021/08/17/gammaionpumpcontrollerethernet.html#read-pressure-0x0b | serial, ethernet |
| 2 | | transfer chamber? – pumping unit  | pressure gauge  | center one  | ok  |   |   | connect to PC (ethernet and serial port are present) | | | serial, ethernet |
| 4 | | spm chamber – cryogenic unit  | LHe level meter  | CryoVac Helium Depth Indicator  | slow mode not used?  |   | LHe level meter  | connect to PC (serial port is present) | | | serial |
| 1 | | prep chamber – argon sputterer  | power source  | CHI-VAC ????  | no PC connectivity  | DCV 2kV and DCI 50mA and focus?  | sputterer control  | find manual. Replace? Talk to it somehow? | 2kV power source https://www.esdemc.com/products/hv-supply-solutions/2kv-high-voltage-supply-module/ . Replace 50mA with KORAD (see above). Keep using "Focus" from original - does not have to be controlled | no digital parts at all - either find a replacement (might be difficult) or replace controllers via pyboard/... - 2xpotentiometers + a few switches + milliammeter | 
| 1 | | prep chamber – argon sputterer  | valve  | mechanical valve  | manual only  | ??? needle valve  | let argon into prep ch  | replace with electric valve / find a way to control | the only motorized leak valve i have found so far https://www.vatvalve.com/series/ultra-high-vacuum-all-metal-variable-leak-valve/59024-GEGG - very expensive (7.5k + taxes, delivery, ..)| https://www.chi-vac.com/QW_Product/ENProductDetail?ProductId=28&FirstTypeId=3&flag=2
| 1 | | prep chamber – evaporator  | power source  | CHI-VAC ????  | no PC connectivity  | ???? with PID  | evaporation control  | find manual. Replace? Talk to it somehow? | Replace with KORAD + thermometry via ADC? | at least partially controllable via RS485 | RS485 (?) |
| 4 | | chamber separation  | valve  | mechanical valve  | manual only  | ???  | separation of the chambers  | replace with electric valve / find a way to control

part 3
| priority | status | subsystem | type | current model | problem with current device | requirements/parameters | function | to do | possible options | comment | ports |
| -------- | ------ | --------- | ---- | ------------- | --------------------------- | ----------------------- | -------- | ----- | ---------------- | ------- | ----- |
| 1 | | prep chamber – PEEM  | power source  | Emission microscope control  | software missing  | see manual  | main PEEM control unit  | talk to Florian first, then update the entry
| 1 | | prep chamber – PEEM  | camera  | PCO.pixelfly  | ok  | USB camera  | PEEM camera  | --\\--\\--
| 1 | | prep chamber – PEEM  | power source  | ebq 100 isolated  | no PC connectivity  | see manual  | UV light source  | --\\--\\--
| 3 | | spm chamber – spm  | control unit  | nanonis  | ok  | nanonis control unit  | 






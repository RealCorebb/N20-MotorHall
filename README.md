# N20-MotorHall

[![alt text]](https://github.com/RealCorebb/N20-MotorHall/blob/main/img/MotorHall.png?raw=true)

## Files:  
Gerber: MotorHall_Gerber.zip  
Schematic: MotorHall_Schematic.pdf  
BOMs: MotorHall_BOM.csv or InteractiveBOM_MotorHall.html  
EasyEDA Pro project: ProPrj_MotorHall.epro  

## Notes:
I designed it in EasyEDA Pro, this is for N20 motor used in LumenPnP's Feeder.  
The schematic is simple, you can easily recreated that in any others EDA because the EasyEDA only can exported to Altium Designer, no KiCad option.  
The hall sensor is special to match the magnet attached in the motor. (Magnet is D9.2 X 1 X 1.5, the magnetic ring has 14 poles, So the gap of pole is 9.2mm*3.14/14 == 2mm, so wee need the hall sensor designed for gap/2 == 1mm, The MT1450 is the one i found and tested).  
The Magnet I bought from here: https://item.taobao.com/item.htm?_u=s283hck43c64&id=578994140285&spm=a1z09.2.0.0.40eb2e8dQrc6jb
[![alt text]]([https://github.com/RealCorebb/N20-MotorHall/blob/main/img/MotorHall.png?raw=true](https://github.com/RealCorebb/N20-MotorHall/blob/main/img/Magnet.png?raw=true))

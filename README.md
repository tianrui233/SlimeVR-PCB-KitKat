# The origin of this name?
I named it KitKat because it is about the same length as KitKat chocolate and it is sandwiched in several layers 😋
![image](https://user-images.githubusercontent.com/37788769/178885236-a44fbf94-6cf0-4a6d-b5a6-ba542e8eb2f2.png)  
The gray part is QMC5883L, I don't want to build a 3D model, so just placeholders 
![image](https://user-images.githubusercontent.com/37788769/178885283-d346f2a5-4eba-4cd1-aaad-29af1c687d29.png)
![image](https://user-images.githubusercontent.com/37788769/178885352-01c546d3-8768-4004-9df5-16c20793556b.png)
![D6048EE55668597A6ACBBA9984D4E5E6](https://user-images.githubusercontent.com/37788769/178885613-d369f50b-8b04-4ab2-aa2a-734eaadf698d.jpg)
![C5005D37BCAB1A75606BB18F0E999D56](https://user-images.githubusercontent.com/37788769/178886018-02fb7d49-7153-47c8-bc46-024bf9eb8427.jpg)

![image](https://user-images.githubusercontent.com/37788769/178885948-58458c99-d47e-411e-9918-5720885067d8.png)


# What sensor does it work with?
It is a tracker composed of mpu6500/mpu6050 and QMC5883L. Compared with only mpu6500/6050, its actual experience is much better with QMC, and it is cheaper than 9250. 
 
Other than that it uses PH 2.00 as an aux to connect the secondary sensor (I think it's more suitable for just tracking the position of the instep, the cable doesn't need to be too long, and it will be light as there is no esp, battery, etc.  
![image](https://user-images.githubusercontent.com/37788769/178886179-bbffa2fd-43e0-4c54-a7f5-b98cdb325a7e.png)  
The gray part is QMC5883L, I don't want to build a 3D model, so just placeholders 
![image](https://user-images.githubusercontent.com/37788769/178886218-9cc602e3-199f-4c9a-b632-1e1cf6008806.png)
 
## The schematic is here, I only draw the part of QMC5883L, the others are from the official SlimeVR
![d1_Base](https://user-images.githubusercontent.com/37788769/176617009-52f5a3f2-49fa-4567-9284-6277648262da.png) 
The wiring of AUX is the same as the official MPU, only 4 wires are needed
 
# what's special about it?
It's just a PCB without any mouted device. Because it only has one side, it's great for those who don't have a soldering foundation diy SlimeVR tracker 
 
In addition, because people often buy broken sensors because of the merchants, it takes a lot of time to solder them down each time. In this way, the design only needs to solder the busbar to the pcb, and then solder the sensor to the pin header and plug it in. Just do it (it is recommended that one of the pcbs is soldered to the busbar only for testing, and the other pcbs are directly soldered to the pcb.
# Anything else to notice?
As official, the resistors and diodes in the PCB are optional. If you don't need battery detection, you can leave the resistor unsoldered; if you don't need to use slime while charging, you can connect the diode pad with tin
 
The reliability of this PCB should be no problem in theory, because the logistics is slow and my pcb has not received the goods 
 
I haven't designed the shell yet, I'm going to wrap it in a paper shell😂
 
## 1.5 UPDATE
Optimize lines and adjust spacing

# The origin of this name?
I named it KitKat because it is about the same length as KitKat chocolate and it is sandwiched in several layers 😋
![image](https://user-images.githubusercontent.com/37788769/175882212-b99b357b-c2cd-4852-9d7b-f4d07c635b1f.png) 
![image](https://user-images.githubusercontent.com/37788769/175882220-05b0c4bf-8bfd-457a-954f-60cb350c202b.png) 
![image](https://user-images.githubusercontent.com/37788769/175882564-236074f2-4ecf-44c6-ab9f-efa88afb0e19.png)
# What sensor does it work with?
It is a tracker composed of mpu6500/mpu6050 and QMC5883L. Compared with only mpu6500/6050, its actual experience is much better with QMC, and it is cheaper than 9250. 
 
Other than that it uses PH 2.00 as an aux to connect the secondary sensor (I think it's more suitable for just tracking the position of the instep, the cable doesn't need to be too long, and it will be light as there is no esp, battery, etc. 
![image](https://user-images.githubusercontent.com/37788769/175883807-7f8cc580-c149-4da2-8f6c-92ce801b5ae9.png)
![image](https://user-images.githubusercontent.com/37788769/175883836-a7ae1109-5f86-44c5-b5be-331b3c5cd3e3.png)
 
# what's special about it?
It's just a PCB without any mouted device. Because it only has one side, it's great for those who don't have a soldering foundation diy SlimeVR tracker 
 
In addition, because people often buy broken sensors because of the merchants, it takes a lot of time to solder them down each time. In this way, the design only needs to solder the busbar to the pcb, and then solder the sensor to the pin header and plug it in. Just do it (it is recommended that one of the pcbs is soldered to the busbar only for testing, and the other pcbs are directly soldered to the pcb.
# Anything else to notice?
As official, the resistors and diodes in the PCB are optional. If you don't need battery detection, you can leave the resistor unsoldered; if you don't need to use slime while charging, you can connect the diode pad with tin
 
The reliability of this PCB should be no problem in theory, because the logistics is slow and my pcb has not received the goods 
 
I haven't designed the shell yet, I'm going to wrap it in a paper shell😂

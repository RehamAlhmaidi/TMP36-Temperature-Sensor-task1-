# TMP36-Temperature-Sensor-task1-

This task turns an Arduino UNO into a simple thermometer using the TMP36 temperature sensor. 
The system detects temperature changes and provides a visual indication using 

three LEDs: 

🟡 Yellow LED → Low temperature (< 20°C)

🟢 Green LED → Medium temperature (20°C – 40°C)

🔵 Blue LED → High temperature (40°C – 85°C)


# The task 

design and pregaming of digital and along sensor

so can simulate the circuit in Tinkercad by adjusting the temperature sensor value and observing the LED behavior.



# Components Required

🟦 Arduino UNO

🌡 TMP36 Temperature Sensor

🟡 Yellow LED (Low Temperature)

🟢 Green LED (Medium Temperature)

🔵 Blue LED (High Temperature)

🔩 Resistors (100Ω – 1KΩ) (Three)

🔌 Breadboard & Jumper Wires




# Circuit Diagram
![Image](https://github.com/user-attachments/assets/c22d93da-8cee-4f98-b50d-8dd238f2f584)




# Code
 [📜 View the Arduino Code](Task1_Elec.ino)





# codeblocks

![Image](https://github.com/user-attachments/assets/1b6f60dd-05be-4236-b528-4b1f44dbbdcd)





# How It Works

The TMP36 sensor reads the temperature.

The Arduino processes the data and determines the temperature range.

One of the three LEDs lights up based on the detected temperature:
< 20°C → Yellow LED (Low)
20°C – 40°C → Green LED (Medium)
40°C – 85°C → Blue LED (High)




# test when Temperature = 105°C  , code only turns on the Blue LED

![Image](https://github.com/user-attachments/assets/9044b5c2-67ca-43dc-b559-9c13e172c62b)




# test when Temperature = -17°C   ,  ode turns on the Yellow LED

![Image](https://github.com/user-attachments/assets/2505a543-c91a-49eb-bd33-afbe868bb92a) 



# tinkercad link

https://www.tinkercad.com/things/llenL25HiUP-tmp36-temperature-sensor?sharecode=_1ZukUw_Z0XZAYo9RWjYSh7g1ltDq3cpsvh95iJIr9Q



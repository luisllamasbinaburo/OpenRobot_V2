# OpenRobot v2

<img src="https://github.com/luisllamasbinaburo/OpenRobot_V2/blob/main/Images/openrobot_v2.jpg" alt="header"/>

OpenRobot v2 is an Open Hardware PCB based on Arduino Nano, especially designed for teaching technology

Once assembled, you can use make multiple projects and robots without welding, just adding or removing components in the dupont headers.

<img src="https://github.com/luisllamasbinaburo/OpenRobot_V2/blob/main/Images/OpenRobot_V2_2.jpg" alt="Assembly" width="450"/>

OpenRobot v2 is based on a modular design. Just select your main MCU module (Arduino Nano, ESP32, M5Stack...), and the module your project needs (Motors, GPIOs expansion...). Check the Wiki for information about each module.


## What can I make with OpenRobot v2?
Almost any DIY project you can ever imagine! 

Some of them,
- DC Motors Robot, like obstacle avoider (ultrasonic or Sharp), line follower, self-balancing bot...
- Servo Motor Robot, like 2-DOF Tower, 6-DOF Arms...
- Mosfet output for high current proyects (LED, electromagnets, water pumps)
- Bluetooth projects (HC-05/HC-06), like Android or PC communication, beacons...
- WiFi projects (ESP01), like controlling from Web, MQTT datalogger...
- Temperature, pressure, humidity weather station with BME280
- Any other project, thanks to the multiple available outputs!


## Modules
More info about each module in Wiki

<img src="https://github.com/luisllamasbinaburo/OpenRobot_V2/blob/main/Images/OpenRobot_V2_1.jpg" alt="Assembly" width="450"/>

#### PowerSource
- DC Converter ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_PowerSource))

#### MCUs
- Arduino Nano ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_MCU_ArduinoNano))
- ESP32 Embed ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_MCU_ESP32Embed))
- M5StickC / M5Stack Atom ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_MCU_M5Stack))

#### Motors
- DC Motors ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_Motor_DC))
- Steppers ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_Motor_Stepper))
- I2C Servos ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_I2C_Servo))

#### Expansions
- I2C GPIO ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_I2C_GPIO))
- I2C TOF ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_I2C_TOF))
- Mosfet ([Wiki link](https://github.com/luisllamasbinaburo/OpenRobot_V2/wiki/Module_Expansion_Mosfet))

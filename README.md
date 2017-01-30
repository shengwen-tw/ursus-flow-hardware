#Ursus-flow

This is the hardware design of Ursus-flow, a computer vision board provide speed estimation for multi-rotor.

<img src="https://github.com/shengwen1997/ursus-flow-hardware/blob/master/materials/ursusflow.png?raw=true" width="610" height="350">

##Specification

**MCU**: STM32F745VETX

**Camera**: MT9v034 (I2C1 and DCMI)

**IMU**: MPU9250 (SPI1)

**Height sensor**: Lidar lite v2 (I2C2)

**USB**: Full Speed USB (USB2.0)

**EEPROM**: AT24C08 (I2C3)

UART2: Data output to flight control board

UART3 and SPI2: alternation

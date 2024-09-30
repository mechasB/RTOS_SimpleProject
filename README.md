# RTOS Simple Project

## Contents:
1. Discussion of the assumptions and goals of the project.
2. Hardware and development tool used
3. Electrical diagram
4. Project description

## 1. Main goal
The main goal of the project is to use in practice the skills related to RTOS on microcontrollers acquired during the course: "Kurs FreeRTOS na STM32 dla początkujących"

## 2. Tools
Software:
- STM32CubeIDE

Hardware:
- Nucleo STM32L476RG
- Oled display
- BMP280
- KY037

 ## 3. Electrical diagram
![Electrical diagram](https://github.com/mechasB/RTOS_SimpleProject/blob/master/Photos%20for%20ReadMe/Electrical_diagram.png)

 ## 4. Project description


Operation diagram:


![Electrical diagram](https://github.com/mechasB/RTOS_SimpleProject/blob/master/Photos%20for%20ReadMe/Operation_diagram.png)



Data collected from the BMP280 sensor is processed and displayed via UART and on the OLED display. At the same time, we collect samples from the microphone, calculate the Furier transform and present the processed data on the display. This project is ideal for practicing numerous RTOS mechanisms.



![putty](https://github.com/mechasB/RTOS_SimpleProject/blob/master/Photos%20for%20ReadMe/Putty.png)


![Circuit_on_desk](https://github.com/mechasB/RTOS_SimpleProject/blob/master/Photos%20for%20ReadMe/Circuit_on_desk.jpg)


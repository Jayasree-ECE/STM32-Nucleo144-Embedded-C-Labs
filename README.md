# 📘 Embedded C Programming Lab – STM32 (IIT Madras)

This repository contains the lab exercises completed as part of the **Embedded C Programming Lab** conducted during the lab sessions at **IIT Madras**.  
The experiments focus on embedded programming using STM32 microcontrollers, implemented using both **STM32CubeIDE (HAL)** and **Arduino IDE (stm32duino)**.

Each exercise follows the official lab manual provided by the mentors, and the corresponding source code has been organized into appropriately named folders.

---

## 🎯 Objectives of the Lab

- Understand STM32 microcontroller architecture and peripherals  
- Learn GPIO, timers, interrupts, and UART using STM32 HAL  
- Gain hands-on experience with STM32CubeIDE  
- Interface sensors using Arduino IDE with stm32duino  
- Implement real-time embedded applications  

---

## 🧰 Tools & Hardware Used

- **Board:** STM32 Nucleo (e.g., F767ZI / as provided in lab)  
- **IDE 1:** STM32CubeIDE  
- **IDE 2:** Arduino IDE with stm32duino core  
- **Programming Language:** Embedded C  
- **Debugger:** ST-LINK (SWD)  
- **Sensors:** HC-SR04, MCP9808, MPU-6050  

---

## 📂 Lab Exercises Covered

### Using STM32CubeIDE with STM32 HAL

1. **STM32CubeIDE – Getting Started and How-To’s**  
   - STM32CubeIDE installation and setup  
   - Board selection and project creation  
   - Code generation using STM32CubeMX  
   - Build, flash, and debug basics  
   📁 `01_CubeIDE_Getting_Started/`

2. **UART Serial Communication using STM32 HAL**  
   - UART peripheral configuration  
   - Transmitting and receiving data using HAL APIs  
   - Serial communication with PC terminal  
   📁 `02_UART_HAL/`

3. **3-bit LED Counter Using HAL Delay, Timer Interrupts, and Button Interrupt**  
   **Objective:** Implement a 3-bit binary counter using onboard LEDs with different approaches.  
   **Implemented Methods:**  
   - Blocking delay using `HAL_Delay()`  
   - Timer-based interrupt using hardware timers  
   - External interrupt using user button  
   📁 `03_3bit_LED_Counter_HAL/`

---

### Using Arduino IDE with stm32duino

4. **Arduino IDE – Getting Started and How-To’s**  
   - Installing STM32 board package  
   - Configuring Arduino IDE for STM32  
   - Uploading sketches using ST-LINK  
   📁 `04_Arduino_Getting_Started/`

5. **GPIO using STM32Duino**  
   - Digital input and output using Arduino APIs  
   - LED blinking and button interfacing  
   📁 `05_GPIO_STM32Duino/`

6. **Ultrasonic Sensor Distance Measurement – HC-SR04**  
   - Interfacing HC-SR04 ultrasonic sensor  
   - Measuring distance using trigger and echo pins  
   📁 `06_HCSR04_Distance/`

7. **Temperature Measurement using I2C – MCP9808**  
   - I2C communication using Arduino framework  
   - Reading temperature data from MCP9808  
   📁 `07_MCP9808_Temperature/`

8. **Accelerometer and Gyroscope – MPU-6050**  
   - Interfacing MPU-6050 using I2C  
   - Reading accelerometer and gyroscope values  
   📁 `08_MPU6050_IMU/`

---

## ✅ Notes

- The code structure strictly follows the lab manual guidelines  
- No changes were made to mentor-provided logic unless required for compilation  
- Each folder contains source files as implemented during lab sessions  

---

## 📜 Acknowledgement

This lab work was carried out as part of the **Embedded C Programming Lab** conducted at **IIT Madras**, under the guidance of the lab mentors and instructors.

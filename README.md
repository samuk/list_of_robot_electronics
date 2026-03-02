# Robot Electronics Open Hardware Resources

A list of resources, open hardware projects and products useful for robot electronics.
If you have additions, please open an issue or pull request.

---

## Table of Contents

- [Brushed Motor Drivers](#brushed-motor-drivers)
- [ESC / BLDC Motor Controllers](#esc--bldc-motor-controllers)
- [Actuators](#actuators)
- [Computer Vision](#computer-vision)
- [Battery Management](#battery-management)
- [FPGA Based](#fpga-based)
- [Bus Systems](#bus-systems)
- [Sensors](#sensors)
- [Open Source Projects](#open-source-projects)
- [Robot Competitions](#robot-competitions)
- [University Projects](#university-projects)

---

## Brushed Motor Drivers

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [SparkFun Easy Driver](https://github.com/sparkfun/Easy_Driver) ![GitHub Repo stars](https://img.shields.io/github/stars/sparkfun/Easy_Driver?style=social) | EasyDriver stepper motor driver | ![GitHub last commit](https://img.shields.io/github/last-commit/sparkfun/Easy_Driver?style=for-the-badge) |
| [SparkFun Pi Servo Hat](https://github.com/sparkfun/Pi_Servo_Hat) ![GitHub Repo stars](https://img.shields.io/github/stars/sparkfun/Pi_Servo_Hat?style=social) | Raspberry Pi servo HAT controlling up to 16 servos | ![GitHub last commit](https://img.shields.io/github/last-commit/sparkfun/Pi_Servo_Hat?style=for-the-badge) |
| [Adafruit DC Stepper Motor HAT](https://github.com/adafruit/Adafruit-DC-Stepper-Motor-HAT-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-DC-Stepper-Motor-HAT-PCB?style=social) | PCB files for the Adafruit DC Stepper Motor HAT and Bonnet | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-DC-Stepper-Motor-HAT-PCB?style=for-the-badge) |
| [SparkFun TMC6300 Three-Phase Driver](https://github.com/sparkfun/SparkFun_Three_Phase_Motor_Driver-TMC6300) ![GitHub Repo stars](https://img.shields.io/github/stars/sparkfun/SparkFun_Three_Phase_Motor_Driver-TMC6300?style=social) | Hardware for TMC6300 three-phase motor driver breakout | ![GitHub last commit](https://img.shields.io/github/last-commit/sparkfun/SparkFun_Three_Phase_Motor_Driver-TMC6300?style=for-the-badge) |
| [Adafruit DRV2605 Haptic Driver](https://github.com/adafruit/Adafruit-DRV2605-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-DRV2605-PCB?style=social) | PCB files for Adafruit DRV2605 Haptic Motor Driver | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-DRV2605-PCB?style=for-the-badge) |
| [Adafruit TMC2209 Breakout](https://github.com/adafruit/Adafruit-TMC2209-Breakout-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-TMC2209-Breakout-PCB?style=social) | PCB files for the Adafruit TMC2209 Stepper Motor Driver Breakout Board | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-TMC2209-Breakout-PCB?style=for-the-badge) |
| [Adafruit A4988 Breakout](https://github.com/adafruit/Adafruit-A4988-Breakout-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-A4988-Breakout-PCB?style=social) | PCB files for the Adafruit A4988 Stepper Motor Driver Breakout Board | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-A4988-Breakout-PCB?style=for-the-badge) |
| [Adafruit STSPIN220 Breakout](https://github.com/adafruit/Adafruit-STSPIN220-Stepper-Motor-Driver-Breakout-Board-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-STSPIN220-Stepper-Motor-Driver-Breakout-Board-PCB?style=social) | PCB files for the Adafruit STSPIN220 Stepper Motor Driver Breakout Board | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-STSPIN220-Stepper-Motor-Driver-Breakout-Board-PCB?style=for-the-badge) |
| [24to12 Brushed Motor Driver](https://github.com/X-Green/24to12-BrushedMotorDriverPCB) ![GitHub Repo stars](https://img.shields.io/github/stars/X-Green/24to12-BrushedMotorDriverPCB?style=social) | DRV8801-based driver for 12V 1A BDC motors | ![GitHub last commit](https://img.shields.io/github/last-commit/X-Green/24to12-BrushedMotorDriverPCB?style=for-the-badge) |
| [CACKLE DRV8213 Driver](https://github.com/techy-robot/CACKLE-Driver-DRV8213_brushed_Motor_Driver) ![GitHub Repo stars](https://img.shields.io/github/stars/techy-robot/CACKLE-Driver-DRV8213_brushed_Motor_Driver?style=social) | Modular DRV8213 brushed motor driver PCB | ![GitHub last commit](https://img.shields.io/github/last-commit/techy-robot/CACKLE-Driver-DRV8213_brushed_Motor_Driver?style=for-the-badge) |
| [STM32 DC Brushed Motor Driver](https://github.com/a2821313427/DC-Brushed-Motor-Driver-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/a2821313427/DC-Brushed-Motor-Driver-PCB?style=social) | STM32-based DC motor driver; schematic, PCB layout, soldering/debugging | ![GitHub last commit](https://img.shields.io/github/last-commit/a2821313427/DC-Brushed-Motor-Driver-PCB?style=for-the-badge) |

---

## ESC / BLDC Motor Controllers

> Note: OSHWLab/OSHWHub projects do not support GitHub badge URLs. Star counts for those are noted inline; last-commit badges only work for GitHub-hosted repos.

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [SimpleFOCShield](https://oshwlab.com/the.skuric/simplefocshield) ⭐ 17k | Classic SimpleFOCShield design (MIT licensed) for Arduino/FOC applications | 2022-01 |
| [MicroSpora SimpleFOC](https://oshwlab.com/rambros/nano-8316-motor-driver) ⭐ 6.6k | STM32G431CBU6 + DRV8316 for high-performance SimpleFOC; CAN, USB, encoder interfaces | 2025-05 |
| [VESC bldc-hardware](https://github.com/vedderb/bldc-hardware) ![GitHub Repo stars](https://img.shields.io/github/stars/vedderb/bldc-hardware?style=social) | Brushless DC motor controller hardware for VESC ecosystem; widely used in electric skateboards/robots | ![GitHub last commit](https://img.shields.io/github/last-commit/vedderb/bldc-hardware?style=for-the-badge) |
| [SimpleFOC42B](https://oshwlab.com/diekerker/simplefoc42b) ⭐ 828 | STM32F103-based stepper/BLDC driver board with magnetic encoder for SimpleFOC | 2023-06 |
| [SimpleFOC StepMini](https://oshwlab.com/the.skuric/simplefocmini_copy) ⭐ 767 | SimpleFOC StepMini driver board variant (public domain) derived from SimpleFOCMini project | 2024-05 |
| [BLDC FOC Driver IR2103](https://oshwlab.com/alperaydin0105/esc-ir2103) ⭐ 729 | BLDC FOC motor driver 12–80V; IR2103 gate drive front end; SimpleFOC-tagged | 2024-01 |
| [SimpleFOC Stepstick](https://oshwlab.com/dekutree64/SimpleFOC-Stepstick) ⭐ 690 | STM32G431 + DRV8955 3-phase/stepper driver; tune parameters per motor/encoder | 2024-08 |
| [ODrive-inspired BLDC PCB](https://github.com/azmat-bilal/bldc_motor_controller_pcb) ![GitHub Repo stars](https://img.shields.io/github/stars/azmat-bilal/bldc_motor_controller_pcb?style=social) | ODrive-inspired single-channel BLDC motor controller PCB | ![GitHub last commit](https://img.shields.io/github/last-commit/azmat-bilal/bldc_motor_controller_pcb?style=for-the-badge) |
| [Cheap FOCer 2](https://github.com/shamansystems/Cheap-FOCer-2) ![GitHub Repo stars](https://img.shields.io/github/stars/shamansystems/Cheap-FOCer-2?style=social) | Low-cost VESC-6-based FOC BLDC controller | ![GitHub last commit](https://img.shields.io/github/last-commit/shamansystems/Cheap-FOCer-2?style=for-the-badge) |
| [Dagor Brushless Controller](https://github.com/byDagor/Dagor-Brushless-Controller) ![GitHub Repo stars](https://img.shields.io/github/stars/byDagor/Dagor-Brushless-Controller?style=social) | ESP32-based BLDC controller with encoder feedback | ![GitHub last commit](https://img.shields.io/github/last-commit/byDagor/Dagor-Brushless-Controller?style=for-the-badge) |
| [IDMIL Moteus](https://github.com/IDMIL/Moteus) ![GitHub Repo stars](https://img.shields.io/github/stars/IDMIL/Moteus?style=social) | High-performance brushless servo controller platform with advanced FOC and trajectory handling | ![GitHub last commit](https://img.shields.io/github/last-commit/IDMIL/Moteus?style=for-the-badge) |
| [stmbl](https://github.com/rene-dev/stmbl) ![GitHub Repo stars](https://img.shields.io/github/stars/rene-dev/stmbl?style=social) | High-voltage AC servo/BLDC driver framework | ![GitHub last commit](https://img.shields.io/github/last-commit/rene-dev/stmbl?style=for-the-badge) |
| [X_driver ODrive](https://github.com/dj140/X_driver) ![GitHub Repo stars](https://img.shields.io/github/stars/dj140/X_driver?style=social) | Single-axis BLDC controller running ODrive firmware v0.5.6; FOC, position/velocity control | ![GitHub last commit](https://img.shields.io/github/last-commit/dj140/X_driver?style=for-the-badge) |
| [RP2040 Motor Controller](https://github.com/Twisted-Fields/rp2040-motor-controller) ![GitHub Repo stars](https://img.shields.io/github/stars/Twisted-Fields/rp2040-motor-controller?style=social) | RP2040-based SimpleFOC-compatible motor controller | ![GitHub last commit](https://img.shields.io/github/last-commit/Twisted-Fields/rp2040-motor-controller?style=for-the-badge) |
| [xESC](https://github.com/ClemensElflein/xESC) ![GitHub Repo stars](https://img.shields.io/github/stars/ClemensElflein/xESC?style=social) | Low-cost sensored BLDC ESC with PCB layouts | ![GitHub last commit](https://img.shields.io/github/last-commit/ClemensElflein/xESC?style=for-the-badge) |
| [µMotor](https://github.com/roboterclubaachen/micro-motor) ![GitHub Repo stars](https://img.shields.io/github/stars/roboterclubaachen/micro-motor?style=social) | µMotor controller for BLDC/DC motors | ![GitHub last commit](https://img.shields.io/github/last-commit/roboterclubaachen/micro-motor?style=for-the-badge) |
| [BlueESC](https://github.com/bluerobotics/BlueESC) ![GitHub Repo stars](https://img.shields.io/github/stars/bluerobotics/BlueESC?style=social) | Open-source ESC for three-phase brushless motors | ![GitHub last commit](https://img.shields.io/github/last-commit/bluerobotics/BlueESC?style=for-the-badge) |
| [HighPower Mechaduino](https://github.com/pointhi/HighPower-Mechaduino) ![GitHub Repo stars](https://img.shields.io/github/stars/pointhi/HighPower-Mechaduino?style=social) | Closed-loop stepper/servo controller reference | ![GitHub last commit](https://img.shields.io/github/last-commit/pointhi/HighPower-Mechaduino?style=for-the-badge) |
| [BLDC Motor PCBs](https://github.com/brenocq/bldc-motor) ![GitHub Repo stars](https://img.shields.io/github/stars/brenocq/bldc-motor?style=social) | High-precision BLDC controller PCBs and firmware | ![GitHub last commit](https://img.shields.io/github/last-commit/brenocq/bldc-motor?style=for-the-badge) |
| [OpenESC](https://github.com/sidharthmohannair/OpenESC) ![GitHub Repo stars](https://img.shields.io/github/stars/sidharthmohannair/OpenESC?style=social) | Open-source ESC hardware/firmware baseline | ![GitHub last commit](https://img.shields.io/github/last-commit/sidharthmohannair/OpenESC?style=for-the-badge) |
| [STM_MotorController](https://github.com/open-rdc/STM_MotorController) ![GitHub Repo stars](https://img.shields.io/github/stars/open-rdc/STM_MotorController?style=social) | Generic STM32-based motor controller framework | ![GitHub last commit](https://img.shields.io/github/last-commit/open-rdc/STM_MotorController?style=for-the-badge) |
| [mbldc](https://github.com/maakbaas/mbldc) ![GitHub Repo stars](https://img.shields.io/github/stars/maakbaas/mbldc?style=social) | Sensorless BLDC controller PCB and firmware | ![GitHub last commit](https://img.shields.io/github/last-commit/maakbaas/mbldc?style=for-the-badge) |
| [OtterControl](https://github.com/NiklasFauth/ottercontrol) ![GitHub Repo stars](https://img.shields.io/github/stars/NiklasFauth/ottercontrol?style=social) | OtterControl BLDC controller; legacy design | ![GitHub last commit](https://img.shields.io/github/last-commit/NiklasFauth/ottercontrol?style=for-the-badge) |
| [asac-esc](https://github.com/victorhook/asac-esc) ![GitHub Repo stars](https://img.shields.io/github/stars/victorhook/asac-esc?style=social) | Open-source ESC hardware and firmware | ![GitHub last commit](https://img.shields.io/github/last-commit/victorhook/asac-esc?style=for-the-badge) |
| [Tarocco](https://github.com/ottoragam/Tarocco) ![GitHub Repo stars](https://img.shields.io/github/stars/ottoragam/Tarocco?style=social) | Closed-loop Step/Dir motor controller | ![GitHub last commit](https://img.shields.io/github/last-commit/ottoragam/Tarocco?style=for-the-badge) |
| [STM32G4 BLDC Driver](https://oshwhub.com/tslong/stm32g4_-ying-jian-hu-bu-qu-dong) | STM32G431RBT6 BLDC/PMSM driver, 3-phase H-bridge, 12–60V, Hall/encoder, current sense | 2025-09 |
| [6-Step BLDC Driver STM32F051](https://oshwhub.com/zz8976/stm32f051_6step_bldc) | Sensorless BLDC driver based on STM32F051K8U6 with FD6288Q; six-step commutation | 2025-11 |
| [SimpleFOCShield v3 Redesigned](https://oshwhub.com/wszq/simplefocshield-v3) | Arduino-compatible SimpleFOCShield v3.2 with current sensing and encoder interfaces | 2024-10 |
| [SimpleFOC_X Integrated Driver](https://oshwhub.com/yourallo/simplefoc_x) | ESP32 + DRV8313 integrated BLDC driver; current/velocity/position loop support | 2024-03 |
| [SimpleFOC DRV8313 Driver](https://oshwhub.com/flowersauce/simplefoc4008) | Three-phase BLDC driver with DRV8313 and optional INA240 current sensing | 2024-04 |
| [SimpleFOC CAN Driver STM32](https://oshwhub.com/skythinker/simplefoc103) | STM32-based SimpleFOC FOC driver board with CAN communication support | 2023-07 |
| [SimpleFOC ESP32 Tank](https://oshwhub.com/zxp1107/simplefoc0414_copy_copy_copy_copy) | ESP32 + L6234 + AS5600 dual BLDC tracked vehicle controller | 2022-04 |

---

## Actuators

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [open_robot_actuator_hardware](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware) ![GitHub Repo stars](https://img.shields.io/github/stars/open-dynamic-robot-initiative/open_robot_actuator_hardware?style=social) | Open robot actuator platform (electronics + mechanics) | ![GitHub last commit](https://img.shields.io/github/last-commit/open-dynamic-robot-initiative/open_robot_actuator_hardware?style=for-the-badge) |
| [mjbots moteus](https://github.com/mjbots/moteus) ![GitHub Repo stars](https://img.shields.io/github/stars/mjbots/moteus?style=social) | Brushless servo actuator controller hardware + firmware; actively maintained into 2025 | ![GitHub last commit](https://img.shields.io/github/last-commit/mjbots/moteus?style=for-the-badge) |
| [OpenTorque Actuator](https://github.com/G-Levine/OpenTorque-Actuator) ![GitHub Repo stars](https://img.shields.io/github/stars/G-Levine/OpenTorque-Actuator?style=social) | Compliant actuator for legged robotics | ![GitHub last commit](https://img.shields.io/github/last-commit/G-Levine/OpenTorque-Actuator?style=for-the-badge) |
| [robot-actuator-esp32-v8](https://github.com/chilipeppr/robot-actuator-esp32-v8) ![GitHub Repo stars](https://img.shields.io/github/stars/chilipeppr/robot-actuator-esp32-v8?style=social) | ESP32-based robot arm actuator with PCB, firmware, and CAD files | ![GitHub last commit](https://img.shields.io/github/last-commit/chilipeppr/robot-actuator-esp32-v8?style=for-the-badge) |
| [ServoProject](https://github.com/adamb314/ServoProject) ![GitHub Repo stars](https://img.shields.io/github/stars/adamb314/ServoProject?style=social) | RC-servo encoder retrofit for closed-loop control | ![GitHub last commit](https://img.shields.io/github/last-commit/adamb314/ServoProject?style=for-the-badge) |
| [NautilusController](https://github.com/JorgeMaker/NautilusController) ![GitHub Repo stars](https://img.shields.io/github/stars/JorgeMaker/NautilusController?style=social) | SimpleFOC-based brushless actuator controller PCB | ![GitHub last commit](https://img.shields.io/github/last-commit/JorgeMaker/NautilusController?style=for-the-badge) |
| [Daisy Driver 2.0](https://github.com/MarginallyClever/Daisy-Driver-2.0-firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/MarginallyClever/Daisy-Driver-2.0-firmware?style=social) | Firmware for actuator driver PCB | ![GitHub last commit](https://img.shields.io/github/last-commit/MarginallyClever/Daisy-Driver-2.0-firmware?style=for-the-badge) |
| [DirectServo](https://github.com/DizzyRobot/DirectServo) ![GitHub Repo stars](https://img.shields.io/github/stars/DizzyRobot/DirectServo?style=social) | Robotic joint controller with BLDC + encoder | ![GitHub last commit](https://img.shields.io/github/last-commit/DizzyRobot/DirectServo?style=for-the-badge) |
| [TitanLegs](https://github.com/SRA-VJTI/TitanLegs) ![GitHub Repo stars](https://img.shields.io/github/stars/SRA-VJTI/TitanLegs?style=social) | Robot leg actuator design with PCB | ![GitHub last commit](https://img.shields.io/github/last-commit/SRA-VJTI/TitanLegs?style=for-the-badge) |

---

## Computer Vision

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [OpenMV](https://github.com/openmv/openmv) ![GitHub Repo stars](https://img.shields.io/github/stars/openmv/openmv?style=social) | Open-source machine vision platform; Python-programmable on STM32H7/N6 MCUs with firmware + IDE | ![GitHub last commit](https://img.shields.io/github/last-commit/openmv/openmv?style=for-the-badge) |
| [USB-C Industrial Camera FPGA USB3](https://github.com/circuitvalley/USB_C_Industrial_Camera_FPGA_USB3) ![GitHub Repo stars](https://img.shields.io/github/stars/circuitvalley/USB_C_Industrial_Camera_FPGA_USB3?style=social) | Open USB-C industrial camera; Verilog FPGA ISP pipeline (MIPI-CSI to USB3); up to 8K/30 FPS | ![GitHub last commit](https://img.shields.io/github/last-commit/circuitvalley/USB_C_Industrial_Camera_FPGA_USB3?style=for-the-badge) |
| [Adafruit MLX90640 IR Camera](https://github.com/adafruit/Adafruit-MLX90640-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-MLX90640-PCB?style=social) | PCB files for Adafruit MLX90640 IR thermal camera breakout | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-MLX90640-PCB?style=for-the-badge) |
| [Adafruit MEMENTO Camera](https://github.com/adafruit/Adafruit-MEMENTO-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-MEMENTO-PCB?style=social) | PCB files for the Adafruit MEMENTO multi-purpose camera breakout | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-MEMENTO-PCB?style=for-the-badge) |
| [Adafruit OV5640 Camera Breakout](https://github.com/adafruit/Adafruit-OV5640-Camera-Breakout-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-OV5640-Camera-Breakout-PCB?style=social) | PCB files for Adafruit OV5640 5 MP sensor breakout | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-OV5640-Camera-Breakout-PCB?style=for-the-badge) |
| [Adafruit PiCowbell Camera Breakout](https://github.com/adafruit/Adafruit-PiCowbell-Camera-Breakout-PCB) ![GitHub Repo stars](https://img.shields.io/github/stars/adafruit/Adafruit-PiCowbell-Camera-Breakout-PCB?style=social) | PCB files for Adafruit PiCowbell camera breakout board | ![GitHub last commit](https://img.shields.io/github/last-commit/adafruit/Adafruit-PiCowbell-Camera-Breakout-PCB?style=for-the-badge) |
| [ESP32-P4 + C5 Camera Platform](https://github.com/Camemake/CM_ESP_P4_C5-Open-Hardware-Platform) ![GitHub Repo stars](https://img.shields.io/github/stars/Camemake/CM_ESP_P4_C5-Open-Hardware-Platform?style=social) | Open hardware ESP32-P4 + ESP32-C5 camera/HMI dev kit; Wi-Fi 6/BLE/Thread | ![GitHub last commit](https://img.shields.io/github/last-commit/Camemake/CM_ESP_P4_C5-Open-Hardware-Platform?style=for-the-badge) |
| [Tokay Lite ESP32-S3 Camera](https://github.com/maxlab-io/tokay-lite-pcb) ![GitHub Repo stars](https://img.shields.io/github/stars/maxlab-io/tokay-lite-pcb?style=social) | ESP32-S3-based edge AI camera; OV2640, TFLite, motion/light sensors, RTC, low-power design | ![GitHub last commit](https://img.shields.io/github/last-commit/maxlab-io/tokay-lite-pcb?style=for-the-badge) |
| [SparkFun Red Vision HM01B0](https://github.com/sparkfun/SparkFun_Red_Vision_Camera_Board_HM01B0) ![GitHub Repo stars](https://img.shields.io/github/stars/sparkfun/SparkFun_Red_Vision_Camera_Board_HM01B0?style=social) | Himax HM01B0 320×320 colour camera module breakout | ![GitHub last commit](https://img.shields.io/github/last-commit/sparkfun/SparkFun_Red_Vision_Camera_Board_HM01B0?style=for-the-badge) |
| [OpenCamera Hardware](https://github.com/kuku-199/OpenCamera-Hardware) ![GitHub Repo stars](https://img.shields.io/github/stars/kuku-199/OpenCamera-Hardware?style=social) | Open-source hardware platform for custom camera boards | ![GitHub last commit](https://img.shields.io/github/last-commit/kuku-199/OpenCamera-Hardware?style=for-the-badge) |

---

## Battery Management

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [foxBMS](https://github.com/foxBMS/foxbms) ![GitHub Repo stars](https://img.shields.io/github/stars/foxBMS/foxbms?style=social) | Modular BMS supporting many chemistries and cell configurations — [foxbms.org](https://foxbms.org/) | ![GitHub last commit](https://img.shields.io/github/last-commit/foxBMS/foxbms?style=for-the-badge) |
| [ENNOID BMS](https://github.com/EnnoidMe/ENNOID-BMS) ![GitHub Repo stars](https://img.shields.io/github/stars/EnnoidMe/ENNOID-BMS?style=social) | Modular LTC68XX + STM32 BMS for up to 400V EV packs — also [firmware](https://github.com/EnnoidMe/ENNOID-BMS-Firmware) / [GUI](https://github.com/EnnoidMe/ENNOID-BMS-Tool) | ![GitHub last commit](https://img.shields.io/github/last-commit/EnnoidMe/ENNOID-BMS?style=for-the-badge) |
| [DieBieMS](https://github.com/DieBieEngineering/DieBieMS) ![GitHub Repo stars](https://img.shields.io/github/stars/DieBieEngineering/DieBieMS?style=social) | 3–12S LiIon BMS, 100A | ![GitHub last commit](https://img.shields.io/github/last-commit/DieBieEngineering/DieBieMS?style=for-the-badge) |
| [Green BMS](https://github.com/Green-bms/SmartBMS) ![GitHub Repo stars](https://img.shields.io/github/stars/Green-bms/SmartBMS?style=social) | Modular BMS supporting many chemistries | ![GitHub last commit](https://img.shields.io/github/last-commit/Green-bms/SmartBMS?style=for-the-badge) |
| [LibreSolar BMS 48V](https://github.com/LibreSolar/BMS48V) ![GitHub Repo stars](https://img.shields.io/github/stars/LibreSolar/BMS48V?style=social) | Li-Ion 48V BMS | ![GitHub last commit](https://img.shields.io/github/last-commit/LibreSolar/BMS48V?style=for-the-badge) |
| [LibreSolar BMS 5S](https://github.com/LibreSolar/BMS-5s) ![GitHub Repo stars](https://img.shields.io/github/stars/LibreSolar/BMS-5s?style=social) | Li-Ion 5S BMS | ![GitHub last commit](https://img.shields.io/github/last-commit/LibreSolar/BMS-5s?style=for-the-badge) |
| [Battman BMS](https://github.com/raphaelchang/battman-hardware) ![GitHub Repo stars](https://img.shields.io/github/stars/raphaelchang/battman-hardware?style=social) | Li-Ion BMS based on LTC6803 | ![GitHub last commit](https://img.shields.io/github/last-commit/raphaelchang/battman-hardware?style=for-the-badge) |
| [Ceech BQ76920 BMS](https://github.com/ceech/BQ76920-BMS) ![GitHub Repo stars](https://img.shields.io/github/stars/ceech/BQ76920-BMS?style=social) | Arduino-based 5S BMS (BQ76920) | ![GitHub last commit](https://img.shields.io/github/last-commit/ceech/BQ76920-BMS?style=for-the-badge) |

---

## FPGA Based

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [LOA](https://github.com/loa-org) | Framework for building specialised IO subsystems | — |
| [flink](https://github.com/flink-project) | Universal FPGA interface with robotics IP-cores | — |
| [Snickerdoodle](http://krtkl.com/) | Zynq-based System-on-Module | — |
| [Logi-Bone](http://valentfx.com/logi-bone/) | FPGA + BeagleBone board with [VHDL robotics modules](https://github.com/fpga-logi/logi-hard) | — |

---

## Bus Systems

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [CANopenNode](https://github.com/CANopenNode/CANopenNode) ![GitHub Repo stars](https://img.shields.io/github/stars/CANopenNode/CANopenNode?style=social) | Open-source CANopen stack | ![GitHub last commit](https://img.shields.io/github/last-commit/CANopenNode/CANopenNode?style=for-the-badge) |
| [ros_canopen](https://github.com/ros-industrial/ros_canopen) ![GitHub Repo stars](https://img.shields.io/github/stars/ros-industrial/ros_canopen?style=social) | CANopen driver framework / ROS bridge | ![GitHub last commit](https://img.shields.io/github/last-commit/ros-industrial/ros_canopen?style=for-the-badge) |
| [UC4H: UAVCAN for Hobbyists](https://github.com/olliw42/uavcan4hobbyists) ![GitHub Repo stars](https://img.shields.io/github/stars/olliw42/uavcan4hobbyists?style=social) | UAVCAN applied to multirotor platforms | ![GitHub last commit](https://img.shields.io/github/last-commit/olliw42/uavcan4hobbyists?style=for-the-badge) |
| [OpenCyphal](https://opencyphal.org/) | Formerly UAVCAN — protocol on CAN Bus for robotics and aerospace control | — |
| [Lely CANopen](https://opensource.lely.com/canopen/) | Open-source CANopen stack | — |
| [KaCanOpen](https://kitmedical.github.io/kacanopen/) | Easy-to-use CANopen stack for ROS | — |
| [SAB / modm.io](https://modm.io/reference/module/modm-communication-sab/) | Sensor Actuator Bus | — |
| [Simple Robot EtherCAT](http://www.simplerobot.net/) | RPi4 + EtherCAT platform | — |

---

## Sensors

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [OpenSimpleLidar](https://github.com/iliasam/OpenSimpleLidar) ![GitHub Repo stars](https://img.shields.io/github/stars/iliasam/OpenSimpleLidar?style=social) | Open hardware scanning laser rangefinder | ![GitHub last commit](https://img.shields.io/github/last-commit/iliasam/OpenSimpleLidar?style=for-the-badge) |
| [Xaxxon OpenLIDAR](http://www.xaxxon.com/xaxxon/openlidar) | DIY scanning LiDAR | — |
| [OSLRF-01](https://www.documents.lightware.co.za/OSLRF-01%20-%20Laser%20Rangefinder%20Manual%20-%20Rev%200.pdf) | Open-source time-of-flight laser range sensor | — |

---

## Open Source Projects

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [Open Dynamic Robot Initiative](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware) ![GitHub Repo stars](https://img.shields.io/github/stars/open-dynamic-robot-initiative/open_robot_actuator_hardware?style=social) | 8/12-DoF walker; fast multi-axis force control, BLDC drivers | ![GitHub last commit](https://img.shields.io/github/last-commit/open-dynamic-robot-initiative/open_robot_actuator_hardware?style=for-the-badge) |
| [StanfordDoggoProject](https://github.com/Nate711/StanfordDoggoProject) ![GitHub Repo stars](https://img.shields.io/github/stars/Nate711/StanfordDoggoProject?style=social) | 8-DoF quadruped robot | ![GitHub last commit](https://img.shields.io/github/last-commit/Nate711/StanfordDoggoProject?style=for-the-badge) |
| [Hoverboard ROS Driver](https://github.com/alex-makarov/hoverboard-driver) ![GitHub Repo stars](https://img.shields.io/github/stars/alex-makarov/hoverboard-driver?style=social) | ROS support for modified hoverboard differential drive platform; uses [bipropellant firmware](https://github.com/bipropellant/bipropellant-hoverboard-firmware) | ![GitHub last commit](https://img.shields.io/github/last-commit/alex-makarov/hoverboard-driver?style=for-the-badge) |
| [nanosaur](https://github.com/rnanosaur/nanosaur) ![GitHub Repo stars](https://img.shields.io/github/stars/rnanosaur/nanosaur?style=social) | 🦕 Small tracked ROS 2 robot for NVIDIA Jetson Nano | ![GitHub last commit](https://img.shields.io/github/last-commit/rnanosaur/nanosaur?style=for-the-badge) |
| [Linorobot](https://github.com/linorobot/linorobot) ![GitHub Repo stars](https://img.shields.io/github/stars/linorobot/linorobot?style=social) | Suite of open-source ROS-compatible robots | ![GitHub last commit](https://img.shields.io/github/last-commit/linorobot/linorobot?style=for-the-badge) |
| [MORPH](https://github.com/roaldlemmens/morph) ![GitHub Repo stars](https://img.shields.io/github/stars/roaldlemmens/morph?style=social) | Modular open robotics platform supporting ROS and VESC | ![GitHub last commit](https://img.shields.io/github/last-commit/roaldlemmens/morph?style=for-the-badge) |
| [Octanis Rover](https://github.com/Octanis1/Octanis1-Electronics) ![GitHub Repo stars](https://img.shields.io/github/stars/Octanis1/Octanis1-Electronics?style=social) | Octanis Rover project electronics | ![GitHub last commit](https://img.shields.io/github/last-commit/Octanis1/Octanis1-Electronics?style=for-the-badge) |
| [Hello Robot](https://github.com/hello-robot) | Mobile robot with manipulation capabilities — [hello-robot.com](http://hello-robot.com/) | — |
| [Reachy](https://www.pollen-robotics.com/) | Humanoid robot with VR teleoperation | — |
| [Evezor](https://hackaday.io/project/20416-evezor-robotic-arm) | Open-source SCARA robotic manufacturing platform | — |
| [Bobble-Bot](https://hackaday.io/project/164992-bobble-bot) | Demo robot for real-time control using RPi, RT Linux, and ROS | — |
| [OAP](http://oap.sourceforge.net/) | Open Automaton Project — source repo inactive since 2008 | — |

---

## Robot Competitions

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [CVRA](https://github.com/cvra) | CVRA GitHub repositories (Eurobot team) | — |
| [RCA](https://github.com/roboterclubaachen) | RCA GitHub repositories (Eurobot team) | — |
| [APBTeam](http://apbteam.org/) | Eurobot team with open-source robot design | — |

---

## University Projects

| Project Name | Description | Last Updated |
| :--- | :--- | :---: |
| [Litter Bot](https://github.com/Nurgak/Litter-collecting-robot) ![GitHub Repo stars](https://img.shields.io/github/stars/Nurgak/Litter-collecting-robot?style=social) | Autonomous litter-collecting robot using OpenCV, RPi, and AVR | ![GitHub last commit](https://img.shields.io/github/last-commit/Nurgak/Litter-collecting-robot?style=for-the-badge) |
| [Zynq + OV7670](https://github.com/laurivosandi/hdl) ![GitHub Repo stars](https://img.shields.io/github/stars/laurivosandi/hdl?style=social) | Student project using Zynq FPGA and OV7670 image sensor | ![GitHub last commit](https://img.shields.io/github/last-commit/laurivosandi/hdl?style=for-the-badge) |

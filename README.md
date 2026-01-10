# A list of resources, open hardware projects and products useful for robot electronics
If you have additions, please open an issue or pull request.

# Brushed motor Drivers

| Repository                                                                                                                                                    | Description                                                              | Stars | Last Commit |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ----- | ----------- |
| [a2821313427/DC-Brushed-Motor-Driver-PCB](https://github.com/a2821313427/DC-Brushed-Motor-Driver-PCB)                                                         | STM32-based DC motor driver; schematic, PCB layout, soldering/debugging  | 0     | 2025-12     |
| [techy-robot/CACKLE-Driver-DRV8213_brushed_Motor_Driver](https://github.com/techy-robot/CACKLE-Driver-DRV8213_brushed_Motor_Driver)                           | Modular DRV8213 brushed motor driver PCB                                 | 0     | 2025-11     |
| [adafruit/Adafruit-STSPIN220-Stepper-Motor-Driver-Breakout-Board-PCB](https://github.com/adafruit/Adafruit-STSPIN220-Stepper-Motor-Driver-Breakout-Board-PCB) | PCB files for the Adafruit STSPIN220 Stepper Motor Driver Breakout Board | 0     | 2025-06     |
| [adafruit/Adafruit-TMC2209-Breakout-PCB](https://github.com/adafruit/Adafruit-TMC2209-Breakout-PCB)                                                           | PCB files for the Adafruit TMC2209 Stepper Motor Driver Breakout Board   | 4     | 2025-01     |
| [sparkfun/SparkFun_Three_Phase_Motor_Driver-TMC6300](https://github.com/sparkfun/SparkFun_Three_Phase_Motor_Driver-TMC6300)                                   | Hardware for TMC6300 three-phase motor driver breakout                   | 8     | 2025-02     |
| [adafruit/Adafruit-A4988-Breakout-PCB](https://github.com/adafruit/Adafruit-A4988-Breakout-PCB)                                                               | PCB files for the Adafruit A4988 Stepper Motor Driver Breakout Board     | 2     | 2024-12     |
| [X-Green/24to12-BrushedMotorDriverPCB](https://github.com/X-Green/24to12-BrushedMotorDriverPCB)                                                               | Use DRV8801 to drive 12V 1A BDC Motor                                    | 0     | 2023-05     |
| [adafruit/Adafruit-DRV2605-PCB](https://github.com/adafruit/Adafruit-DRV2605-PCB)                                                                             | PCB files for Adafruit DRV2605 Haptic Motor Driver                       | 8     | 2022-07     |
| [adafruit/Adafruit-DC-Stepper-Motor-HAT-PCB](https://github.com/adafruit/Adafruit-DC-Stepper-Motor-HAT-PCB)                                                   | PCB files for the Adafruit DC Stepper Motor HAT and Bonnet               | 14    | 2022-06     |
| [sparkfun/Easy_Driver](https://github.com/sparkfun/Easy_Driver)                                                                                               | EasyDriver stepper motor driver                                          | 30    | 2020-10     |
| [sparkfun/Pi_Servo_Hat](https://github.com/sparkfun/Pi_Servo_Hat)                                                                                             | Raspberry Pi servo HAT controlling up to 16 servos                       | 21    | 2020-07     |



## ESC / BLDC Motor Controller Projects
| Repository                                                                                                 | Description                                                                                                                                                                         | Stars   | Last Commit  |
| ---------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ------------ |
| [6-Step BLDC Driver (stm32f051k8u6)](https://oshwhub.com/zz8976/stm32f051_6step_bldc)                      | Sensorless BLDC driver based on STM32F051K8U6 with FD6288Q; six-step commutation support                                                                                            | —       | 2025-11      |
| [rambros/MicroSpora-SimpleFOC](https://oshwlab.com/rambros/nano-8316-motor-driver)                         | MicroSpora drive board with STM32G431CBU6 + DRV8316 for high-performance SimpleFOC control; includes CAN, USB, encoder interfaces; firmware on GitHub.                              | 6.6k    | 2025-05-31   |
| [STM32G4+ BLDC Driver](https://oshwhub.com/tslong/stm32g4_-ying-jian-hu-bu-qu-dong?utm_source=chatgpt.com) | STM32G431RBT6 BLDC/PMSM driver board, 3-phase H-bridge, wide supply range 12-60 V, supports Hall/encoder, current sense and hardware protections                                    | —       | 2025-09      |
| [SimpleFOCShield v3-Redesigned](https://oshwhub.com/wszq/simplefocshield-v3)                               | Arduino-compatible SimpleFOCShield v3.2 driver board redesigned for use with the SimpleFOC Arduino library. Supports current sensing and encoder interfaces; low-cost FOC platform. | —       | 2024-10-10   |
| [IDMIL/Moteus](https://github.com/IDMIL/Moteus)                                                            | High-performance brushless servo controller platform with advanced field-oriented control (FOC) and trajectory handling                                                             | unknown | 2024-11      |
| [vedderb/bldc-hardware](https://github.com/vedderb/bldc-hardware)                                          | Brushless DC Motor controller hardware for VESC ecosystem, widely used in electric skateboards/robots; robust design with power stages, gate drivers, connectors                    | ~1.3k   | 2024-11      |
| [dj140/X_driver](https://github.com/dj140/X_driver)                                                        | Single-axis BLDC controller board designed to run ODrive firmware v0.5.6; supports FOC, position/velocity control, and ODrive API commands                                          | unknown | 2024         |
| [dekutree64/SimpleFOC-Stepstick](https://oshwlab.com/dekutree64/SimpleFOC-Stepstick)                       | SimpleFOC Stepstick driver for 3-phase motors & steppers; STM32G431 + DRV8955; tune parameters per motor/encoder                                                                    | 690     | 2024-08-08   |
| [SimpleFOC_X无刷电机驱控一体板](https://oshwhub.com/yourallo/simplefoc_x)                                           | SimpleFOC_X integrated BLDC driver/controller with ESP32 and DRV8313 driver, supports current/velocity/position loops.                                                              | —       | 2024-03-28   |
| [SimpleFOC驱动板](https://oshwhub.com/flowersauce/simplefoc4008)                                              | SimpleFOC three-phase BLDC motor driver board with DRV8313 and optional INA240 current sensing.                                                                                     | —       | 2024-04-03   |
| [the.skuric/SimpleFOC StepMini](https://oshwlab.com/the.skuric/simplefocmini_copy)                         | SimpleFOC StepMini driver board variant (public domain) derived from SimpleFOCMini project.                                                                                         | 767     | 2024-05-04   |
| [shamansystems/Cheap-FOCer-2](https://github.com/shamansystems/Cheap-FOCer-2)                              | Low-cost VESC-6-based field-oriented control (FOC) BLDC controller                                                                                                                  | unknown | 2024-03      |
| [alperaydin0105/BLDC-FOC-Motor-Driver-IR2103](https://oshwlab.com/alperaydin0105/esc-ir2103)               | BLDC FOC motor driver (12-80V) project tagged SimpleFOC; basic IR2103 front end with firmware approach linked.                                                                      | 729     | 2024-01-16   |
| [byDagor/Dagor-Brushless-Controller](https://github.com/byDagor/Dagor-Brushless-Controller)                | ESP32-based BLDC controller with encoder feedback                                                                                                                                   | unknown | 2024-02      |
| [rene-dev/stmbl](https://github.com/rene-dev/stmbl)                                                        | High-voltage AC servo/BLDC driver framework                                                                                                                                         | unknown | 2024-01      |
| [the.skuric/SimpleFOCShield](https://oshwlab.com/the.skuric/simplefocshield)                               | Classic SimpleFOCShield design (MIT licensed) for Arduino/FOC applications.                                                                                                         | 17k     | 2022-01-20   |
| [Twisted-Fields/rp2040-motor-controller](https://github.com/Twisted-Fields/rp2040-motor-controller)        | RP2040-based motor controller project; SimpleFOC-compatible firmware available                                                                                                      | unknown | 2023-04      |
| [diekerker/SimpleFOC42B](https://oshwlab.com/diekerker/simplefoc42b)                                       | SimpleFOC42B stepper/BLDC driver board with STM32F103 and magnetic encoder for SimpleFOC usage.                                                                                     | 828     | 2023-06-27   |
| [ClemensElflein/xESC](https://github.com/ClemensElflein/xESC)                                              | Low-cost sensored BLDC ESC with PCB layouts                                                                                                                                         | unknown | 2023-06      |
| [支持CAN通信的SimpleFOC无刷驱动](https://oshwhub.com/skythinker/simplefoc103)                                       | STM32-based SimpleFOC FOC driver board with CAN communication support.                                                                                                              | —       | 2023-07-17   |
| [simplefoc-小坦克](https://oshwhub.com/zxp1107/simplefoc0414_copy_copy_copy_copy)                             | ESP32-based SimpleFOC tracked vehicle controller; uses ESP32, L6234 driver, AS5600 encoder for dual BLDC motors.                                                                    | —       | 2022-04-18   |
| [roboterclubaachen/micro-motor](https://github.com/roboterclubaachen/micro-motor)                          | µMotor controller for BLDC/DC motors                                                                                                                                                | unknown | 2022-05      |
| [bluerobotics/BlueESC](https://github.com/bluerobotics/BlueESC)                                            | Open-source ESC for three-phase brushless motors                                                                                                                                    | unknown | 2022-08      |
| [brenocq/bldc-motor](https://github.com/brenocq/bldc-motor)                                                | High-precision BLDC controller PCBs and firmware                                                                                                                                    | unknown | 2022-02      |
| [maakbaas/mbldc](https://github.com/maakbaas/mbldc)                                                        | Sensorless BLDC controller PCB and firmware                                                                                                                                         | unknown | 2021-01      |
| [pointhi/HighPower-Mechaduino](https://github.com/pointhi/HighPower-Mechaduino)                            | Closed-loop stepper/servo controller reference                                                                                                                                      | unknown | 2021-12      |
| [open-rdc/STM_MotorController](https://github.com/open-rdc/STM_MotorController)                            | Generic STM32-based motor controller framework supporting BLDC and other motors                                                                                                     | unknown | 2021-09      |
| [NiklasFauth/ottercontrol](https://github.com/NiklasFauth/ottercontrol)                                    | OtterControl BLDC controller project; legacy design                                                                                                                                 | unknown | 2020-07      |
| [sidharthmohannair/OpenESC](https://github.com/sidharthmohannair/OpenESC)                                  | Open-source ESC hardware/firmware baseline                                                                                                                                          | unknown | 2020-10      |
| [victorhook/asac-esc](https://github.com/victorhook/asac-esc)                                              | Open-source ESC hardware and firmware; older implementation                                                                                                                         | unknown | 2020-06      |
| [ottoragam/Tarocco](https://github.com/ottoragam/Tarocco)                                                  | Closed-loop Step/Dir motor controller; not BLDC-centric                                                                                                                             | unknown | 2020-03      |
| [azmat-bilal/bldc_motor_controller_pcb](https://github.com/azmat-bilal/bldc_motor_controller_pcb)          | ODrive-inspired single-channel BLDC motor controller PCB                                                                                                                            | ~103    | 2020-release |

## Actuators
| Repository | Description | Stars | Last Commit |
|------------|-------------|-------|-------------|
| [robot‑actuator‑esp32‑v8](https://github.com/chilipeppr/robot-actuator-esp32-v8) | ESP32‑based robot arm actuator with PCB, firmware, and CAD files | 233 stars | Latest commit present in history (exact date not on UI) |
| [OpenTorque‑Actuator](https://github.com/G-Levine/OpenTorque-Actuator) | Compliant actuator for legged robotics | 390 stars | Last visible commit ~2019 (no recent commit history shown) |
| [open‑dynamic‑robot‑initiative/open_robot_actuator_hardware](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware) | Open robot actuator platform (electronics + mechanics) | ~1.3k stars | Last visible commit ~4 years ago (around 2022) |
| [mjbots/moteus](https://github.com/mjbots/moteus) | Brushless servo actuator controller hardware + firmware | ~1k+ stars | Active recent commit history into 2025 (per GitHub “Activity” and releases, exact date via releases page) |
| [JorgeMaker/NautilusController](https://github.com/JorgeMaker/NautilusController) | SimpleFOC‑based brushless actuator controller PCB | unknown | *commit history not shown in search UI* |
| [SRA‑VJTI/TitanLegs](https://github.com/SRA-VJTI/TitanLegs) | Robot leg actuator design with PCB | 1 star | *commit history not shown in search UI* |
| [MarginallyClever/Daisy‑Driver‑2.0‑firmware](https://github.com/MarginallyClever/Daisy-Driver-2.0-firmware) | Firmware for actuator driver PCB | unknown | *commit history not shown in search UI* |
| [DirectServo](https://github.com/DizzyRobot/DirectServo) | Robotic joint controller with BLDC + encoder | unknown | *commit history not shown in search UI* |
| [ServoProject](https://github.com/adamb314/ServoProject) | RC‑Servo electrode retrofit | unknown | *commit history not shown in search UI* |


### Computer Vision
| Repository                                                                                                                                 | Description                                                                                                                                                                                                         | Stars  | Last Commit             |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ | ----------------------- |
| [https://github.com/adafruit/Adafruit-PiCowbell-Camera-Breakout-PCB](https://github.com/adafruit/Adafruit-PiCowbell-Camera-Breakout-PCB)   | PCB files for Adafruit PiCowbell camera breakout board.                                                                                                                                                             | 2      | May 3 2024              |
| [https://github.com/maxlab-io/tokay-lite-pcb](https://github.com/maxlab-io/tokay-lite-pcb)                                                 | Tokay Lite open PCB files for ESP32‑S3‑based edge AI camera dev board; uses ESP32‑S3 SoC with TensorFlow Lite support, OV2640 2 MP camera, motion/light sensors, night vision, RTC power control, low‑power design. | N/A    | 2024 (recent)           |
| [https://github.com/adafruit/Adafruit-MEMENTO-PCB](https://github.com/adafruit/Adafruit-MEMENTO-PCB)                                       | PCB files for the Adafruit MEMENTO camera board (multi‑purpose camera breakout).                                                                                                                                    | 8      | Dec 21 2023             |
| [https://github.com/circuitvalley/USB_C_Industrial_Camera_FPGA_USB3](https://github.com/circuitvalley/USB_C_Industrial_Camera_FPGA_USB3)   | Open USB‑C industrial camera project; PCB, Verilog FPGA ISP pipeline (MIPI‑CSI to USB3), Cypress FX3 USB controller firmware; targets Lattice FPGA + MIPI sensors (up to 8K/30 FPS or high‑FPS lanes).              | ~1.1k  | Oct 22 2023             |
| [https://github.com/adafruit/Adafruit-OV5640-Camera-Breakout-PCB](https://github.com/adafruit/Adafruit-OV5640-Camera-Breakout-PCB)         | PCB files for Adafruit OV5640 camera breakout (OmniVision OV5640 5 MP sensor).                                                                                                                                      | 7      | Feb 8 2023              |
| [https://github.com/openmv/openmv](https://github.com/openmv/openmv)                                                                       | OpenMV open‑source machine vision platform; firmware + IDE for Python‑programmable vision modules; supports ARM Cortex‑M/N series (e.g., STM32H7/STM32N6 MCUs with camera interfaces).                              | ~3,299 | 2025 (actively updated) |
| [https://github.com/Camemake/CM_ESP_P4_C5-Open-Hardware-Platform](https://github.com/Camemake/CM_ESP_P4_C5-Open-Hardware-Platform)         | Open hardware ESP32‑P4 + ESP32‑C5 camera/HMI dev kit; uses Espressif RISC‑V ESP32‑P4 for vision/edge processing and ESP32‑C5 for wireless (Wi‑Fi 6/BLE/Thread).                                                     | ~5     | 2025 (updated)          |
| [https://github.com/sparkfun/SparkFun_Red_Vision_Camera_Board_HM01B0](https://github.com/sparkfun/SparkFun_Red_Vision_Camera_Board_HM01B0) | SparkFun Red Vision Camera Board breakout for Himax HM01B0 320×320 color camera module (multiple FPS modes).                                                                                                        | 0      | 2025 (recent)           |
| [https://github.com/kuku-199/OpenCamera-Hardware](https://github.com/kuku-199/OpenCamera-Hardware)                                         | Open‑source hardware platform for camera modules (hardware design files for custom camera boards).                                                                                                                  | N/A    | unknown                 |
| [https://github.com/adafruit/Adafruit-MLX90640-PCB](https://github.com/adafruit/Adafruit-MLX90640-PCB)                                     | PCB files for Adafruit MLX90640 IR thermal camera breakout (MLX90640 thermal sensor).                                                                                                                               | 8      | Jan 24 2020             |

### Battery Management ###
- [DieBieMS](https://github.com/DieBieEngineering/DieBieMS) - DieBieMS (3-12S LiIon-based, 100A)
- [LibreSolar Project](https://github.com/LibreSolar) - with different sized BMS [BMS Li-Ion 5S](https://github.com/LibreSolar/BMS-5s), [BMS Li-Ion 48V](https://github.com/LibreSolar/BMS48V)
- [Ceech's BMS](https://github.com/ceech/BQ76920-BMS) - Arduino-based 5S BMS (BQ76920)
- [Battman BMS](https://github.com/raphaelchang/battman-hardware) - Li-Ion BMS (LTC6803)
- [ENNOID - BMS](https://github.com/EnnoidMe/ENNOID-BMS) [FW](https://github.com/EnnoidMe/ENNOID-BMS-Firmware) [GUI](https://github.com/EnnoidMe/ENNOID-BMS-Tool) - Modular BMS based on LTC68XX & STM32 MCU for up to 400V EV battery pack
- [foxBMS (Github)](https://github.com/foxBMS/foxbms) - Modular BMS (many chemistries, many cells)  [foxbms.org](https://foxbms.org/)
- [Green BMS](https://github.com/Green-bms/SmartBMS) - Modular BMS, for many chemistries 

### FPGA based
- [LOA](https://github.com/loa-org) - Loa is a framework designed to build specialized IO subsystems.
- [Snickerdoodle](http://krtkl.com/) - Snickerdoodle is a Zynq based System-on-Module
- [Logi-Bone](http://valentfx.com/logi-bone/) - FPGA & Beaglebone, also [some VHDL modules](https://github.com/fpga-logi/logi-hard) relevant to robotics available
- [flink](https://github.com/flink-project) - Universal interface to FPGA's. Includes some IP-Cores for robotics.

### Bus Systems
- [SAB](https://modm.io/reference/module/modm-communication-sab/) - Sensor Actuator Bus (SAB), also in [modm.io](https://modm.io/)
- [OpenCyphal](https://opencyphal.org/) - (formerly UAVCAN) Protocol on top of CAN Bus, suited for robotics and aerospace control applications
- [UC4H: UAVCAN for Hobbyists](http://www.olliw.eu/2017/uavcan-for-hobbyists/)  [(on GitHub)](https://github.com/olliw42/uavcan4hobbyists) - UAVCAN applied to a multirotor plattform.
- [Simple Robot](http://www.simplerobot.net/) - RPI4 & EtherCAT
- [Lely CANopen](https://opensource.lely.com/canopen/) - Open Source CANopen Stack
- [CANopenNode](https://github.com/CANopenNode/CANopenNode) - Another Open Source CANopen Stack
- [CANopen driver framework for ROS](https://github.com/ros-industrial/ros_canopen) - CANOpen ROS bridge
- [KaCanOpen](https://kitmedical.github.io/kacanopen/) - an easy-to-use CANopen stack for ROS

### Sensors
- [OpenSimpleLidar](https://github.com/iliasam/OpenSimpleLidar) - Open Hardware scanning laser rangefinder
- [OSLRF-01](https://www.documents.lightware.co.za/OSLRF-01%20-%20Laser%20Rangefinder%20Manual%20-%20Rev%200.pdf) - An open source laser range sensor using time-of-flight
- [Xaxxon OpenLIDAR](http://www.xaxxon.com/xaxxon/openlidar) - DIY Scanning Lidar 

## Projects with open and reuseable designs

### Open Source Project
- [Reachy](https://www.pollen-robotics.com/)  humanoid robot, remote teleoperation using virtual reality.
- [MORPH](https://hackaday.io/project/25730-morph-modular-open-robotics-platform-for-hackers) [on GitHub](https://github.com/roaldlemmens/morph) - Modular platform for open robotics development. Supports ROS and uses VESC.
- [Evezor](https://hackaday.io/project/20416-evezor-robotic-arm) - Evezor is an open source SCARA class robotic manufacturing platform
- [Octanis Rover](https://github.com/Octanis1/Octanis1-Electronics) - Octanis Rover Projects Electronics
- [OAP](http://oap.sourceforge.net/) - Open Automaton Project (Source Repo inactive since 2008)
- [Linorobot](https://linorobot.org/) - A suite of Open Source ROS compatible robots [GIT](https://github.com/linorobot/linorobot)
- [Bobble-Bot](https://hackaday.io/project/164992-bobble-bot) - Demo robot for real-time control using Rpi, RT Linux, and ROS.
- [StanfordDoggoProject](https://github.com/Nate711/StanfordDoggoProject) - 8-DoF quadruped robot
- [Open Dynamic Robot Initiative](https://github.com/open-dynamic-robot-initiative) - 8/12-Dof Walker, fast multi-axis force control, bldc-drivers
- [Hoverboard + ROS](https://github.com/alex-makarov/hoverboard-driver) - Provides ROS support for modified hoverboard, to provide a differential drive plattform. Uses this [modified firmware](https://github.com/bipropellant/bipropellant-hoverboard-firmware).
- [Hello Robot](http://hello-robot.com/) - Mobile robot mit manipulation capabilities, also: [Github](https://github.com/hello-robot).
- [nanosaur](https://github.com/rnanosaur) - 🦕 nanosaur is a little tracked robot ROS2 enabled, made for an NVIDIA Jetson Nano


### Robot Competitions
- [CVRA](https://github.com/cvra) - CVRA's Github repositories (Eurobot Team)
- [RCA](https://github.com/roboterclubaachen) - RCA Github repositories (Eurobot Team)
- [APBTeam](http://apbteam.org/) - A Eurobot Team with opensource robot design

### University Projects, Thesis work, etc.
- [Litter Bot](https://github.com/Nurgak/Litter-collecting-robot) - Autonomous litter collecting robot (using OpenCV, Rpi and AVR)
- [Zynq + OV7670](https://github.com/laurivosandi/hdl) - Student project using Zynq and image sensor (OV7670)

| Libraries/SDK                      | Explanation/Explanation                           | FEETECH Serail servo  | Surroundings/Surroundings                     |
| ---------------------------------- | --------------- --------------------------------- | --------------------- | --------------------------------------------- |
| SCServoCL_keil_f103_220106.7z      | SCSCL servo SDK/SCSCL servo SDK                   | SCS                   | Support STM32F103 Chip/support STM32F103 Chip |
| SCServoCL_keil_f405_220330.7z      | SCSCL servo SDK/SCSCL servo SDK                   | SCS                   | support STM32F405 chip/support STM32F405 chip |
| SMServoBCL_keil_f103_220329.7z     | SMS/STS serial servo SDK/SMS/STS serial servo SDK | SMSBL/SMSCL/STS       | support STM32F103 chip/support STM32F103 chip |
| SMServoBCL_keil_f405_220329.7z     | SMS/STS serial servo SDK/SMS/STS serial servo SDK | SMSBL/SMSCL/STS       | support STM32F405 chip/support STM32F405 chip |
| SMServoBCL_keil_f405_hal_220330.7z | SMS/STS serial servo hal library SDK              | SMSBL/SMSCL/STS       | support STM32F405 chip                        |
| SCServo_Linux_220329.7z            | Linux servo SDK/Linux servoSDK                    | SCSCL/SMSBL/SMSCL/STS | Linux                                         |
| SCServoDemo_vs_2008_200724.7z      | vs2008(VC++) servo SDK/vs2008(VC++) servo SDK     | SCSCL/SMSBL/SMSCL/STS | VC++                                          |
| SCServo_Python_220415.7z           | Python servo SDK/Python servo SDK                 | SCSCL/SMSBL/SMSCL/STS | Python                                        |
| SCServo_Arduino_220524.7z          | Arduino servo SDK/Arduino servo SDK               | SCSCL/SMSBL/SMSCL/STS | Arduino                                       |
| ModbusRtu_Arduino_211016.7z        | Modbus rtu servo SDK/Modbus rtu servo SDK         | SMSBLMD/SMSCLMD       | Arduino                                       |

SCServoCL_keil_f103_220106.7z  
1. STM32F103 Keil SDK increases bus switching delay  
2. SDK read timeout uses instruction counting method to replace system timer (does not occupy system timer)   

SCServoCL_keil_f405_220330.7z  
1. STM32F405 Keil SDK increases bus switching delay  
2. SDK read timeout uses instruction counting method to replace system timer (does not occupy system timer)    

SMServoBCL_keil_f103_220329.7z  
1. Add synchronous read function to stm32f103 keil sdk  
2. STM32F103 Keil SDK increases bus switching delay

SMServoBCL_keil_f405_220329.7z  
1. Add synchronous read function to stm32f405 keil sdk  
2. STM32F405 Keil SDK increases bus switching delay  
3. SDK read timeout uses instruction counting method to replace system timer (does not occupy system timer)

SMServoBCL_keil_f405_hal_220330.7z  
1. Add synchronous read function to stm32f405 keil hal sdk  
2. STM32F405 Keil HAL SDK increases bus switching delay

SCServo_Linux_220329.7z  
1. Linux SDK adds synchronous reading function  
2. Added SMS_STS class, compatible with two series of servos  
3. Example: Change SMSBL and SMSCL classes to SMS_STS class application examples  
4. Correct the debug output information format and errors  

SCServo_Arduino_220524.7z  
1. Add synchronous reading function to Arduino SDK  
2. Add the function of restoring the default parameters of the servo  
3. Fixed the communication timeout and instability issue  

SCServo_Python_220415.7z  
1. Added sms_sts class (SMS/STS servos) and scscl class (SCS servos)  
2. Optimize synchronous reading stability  

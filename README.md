| 库/SDK                             | 解释/Explanation                                             | FEETECH Serail servo | 环境/Surroundings                        |
| ---------------------------------- | ------------------------------------------------------------ | -------------------- | ---------------------------------------- |
| SCServoCL_keil_f103_220106.7z      | SCSCL舵机SDK/SCSCL servo SDK                                 | SCS                  | 支持STM32F103芯片/support STM32F103 Chip |
| SCServoCL_keil_f405_200521.7z      | SCSCL舵机SDK/SCSCL servo SDK                                 | SCS                  | 支持STM32F405芯片/support STM32F405 chip |
| SMServoBCL_keil_f103_220106.7z     | SMS/STS系列舵机SDK/SMS/STS serial servo SDK                  | SMSBL/SMSCL/STS      | 支持STM32F103芯片/support STM32F103 chip |
| SMServoBCL_keil_f405_220225.7z     | SMS/STS系列舵机SDK/SMS/STS serial servo SDK                  | SMSBL/SMSCL/STS      | 支持STM32F405芯片/support STM32F405 chip |
| SMServoBCL_keil_f405_hal_220225.7z | SMS/STS系列舵机hal库SDK/SMS/STS serial servo hal library SDK | SMSBL/SMSCL/STS      | 支持STM32F405芯片/support STM32F405 chip |
| SCServo_Linux_211209.7z            | Linux舵机SDK/Linux servoSDK                                  | SMSBL/SMSCL/STS      | Linux                                    |
| SCServoDemo_vs_2008_200724.7z      | vs2008(VC++)舵机SDK/vs2008(VC++) servo SDK                   | SMSBL/SMSCL/STS      | VC++                                     |
| SCServo_Python_200831.7z           | Python舵机SDK/Python servo SDK                               | SMSBL/SMSCL/STS      | Python                                   |
| SCServo_Arduino_210311.7z          | Arduino舵机SDK/Arduino servo SDK                             | SMSBL/SMSCL/STS      | Arduino                                  |
| ModbusRtu_Arduino_211016.7z        | Modbus rtu舵机SDK/Modbus rtu servo SDK                       | SMSBLMD/SMSCLMD      | Arduino                                  |

|   FEETECH 串行系列舵机：SCS系列/STS系列/SMCL系列/SMBL系列    |
| :----------------------------------------------------------: |
| Feed serial port servo is divided into SCS series / STS series / smcl series / SMBL series |
| SCS:SCS009/SCS2332/SCS45/SCS15/SCS125/SCS115/SCS215/SCS25/SCS40/SCS40-DS/SCS46/SCS6560 |
|            STS:STS3032/STS3215/STS3046/SCS20-360T            |
|                SMCL:SM60CL/SM85CL/SM100/SM150                |
|  SMBL:SM29BL/SM30BL/SM40BL/SM45BL/SM8512BL/SM8524BL/SM120BL  |

SMServoBCL_keil_f103_220106.7z  
1、stm32f103 keil sdk增加同步读功能  
2、stm32f103 keil sdk增加总线切换延时  

SCServoCL_keil_f103_220106.7z  
1、stm32f103 keil sdk增加总线切换延时  
2、SDK读超时使用指令计数方法替换系统定时器(不占用系统定时器)    

SMServoBCL_keil_f405_220225.7z  
1、stm32f405 keil sdk增加同步读功能  
2、stm32f405 keil sdk增加总线切换延时  
3、SDK读超时使用指令计数方法替换系统定时器(不占用系统定时器)

SCServo_Linux_211209.7z  
1、linux sdk增加同步读功能  
2、增加SMS_STS类，同时兼容两个系列舵机  
3、example例子SMSBL与SMSCL类改成SMS_STS类应用实例  
4、修正调试输出信息格式与错误

SMServoBCL_keil_f405_hal_220225.7z  
1、stm32f405 keil hal sdk增加同步读功能  
2、stm32f405 keil hal sdk增加总线切换延时  
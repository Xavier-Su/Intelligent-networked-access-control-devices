# Intelligent-networked-access-control-devices
(STM32F103C8T6)Intelligent networked access control devices
该文件夹中是STM32F103C8T6版本，下面的文件夹是Arduino nano版本
(Arduino nano)Intelligent networked access control devices

1.使用门禁控制端核心模块代码.txt，将该程序录入 Arduino nano 或者uno 等控制器。

2.使用门禁控制端网络模块代码.txt，将该程序录入控制端电路上的esp8266控制器。

3.使用远程遥控端代码.txt，将该程序录入远程遥控端上的esp8266控制器。

按照电路原理图将各个模块进行连接，

所用模块有：
门禁控制端：Arduino nano 、esp8266 、nrf24L01、RC522、180度舵机、重启按钮。

远程遥控端：esp8266、nrf24L01、0.96OLED屏幕、DS18B20、开关按钮。

连接好后，上电启动，开始工作。

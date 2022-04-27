# USB转串口小工具硬件
发现大多数TB的USB串口工具老出各种意外,于是自己画了一版.
* 主控芯片使用CP2104,通讯速率最大可达2Mbps.
* 集成了功率开关-BD2243G-GTR(限流500mA)
* 集成电源和过功率指示灯、接收发送指示灯.
* USB口添加ESD保护-BDFN1710A054U.
* 添加3.3V线性稳压器，支持3V3逻辑电平.
* 添加DTR流控制，支持Arduino自动下载.

## 仿真图
* TOP  
  ![TOP](https://github.com/Cube-Line/USBtoTTL/blob/main/USBtoTTL_HW/image/top.png)
* BOTTOM  
  ![BOTTOM](https://github.com/Cube-Line/USBtoTTL/blob/main/USBtoTTL_HW/image/bottom.png)


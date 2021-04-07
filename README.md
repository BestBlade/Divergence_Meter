## Divergence_Meter世界线变动仪
### 1.方案/Design
  * 1.采用八根辉光管作为主体
  * 1.Eight nixel tubes are used as the main body
  * 2.使用stm32配合译码芯片静态驱动
  * 2.Static driver using stm32 microcontroller with decoder chip
  * 3.外接时钟模块保证断电后正常计时
  * 3.External clock module ensures normal timing after power failure
  * 4.采用蓝牙模块与手机连接，使用手机APP控制灯的模式
  * 4.The use of Bluetooth module and cell phone connection, the use of cell phone APP control light mode
  * 5.使用升压模块驱动辉光管
  * 5.Using a booster module to drive the nixel tubes
### 2.选材/Material Selection
  * 1.辉光管/Nixel Tubes:NL-5441A
  * 2.单片机/Microcontroller:STM32F103ZET6
  * 3.时钟模块/Time module:DS3231
  * 4.蓝牙模块/Bluetooth module:HC08
  * 5.升压模块/Booster module:NCH6300HV
  * 6.顶部装饰电容1：瓷片电容104，容量随意
  * 6.Top Layer Decorative Capacitor 1：Ceramic chip capacitors,Capacity at will
  * 7.顶部装饰电容2：RwbyCon电解电容，YXF10V100uF，直径D = 5.0mm，高度H = 11.0mm，引脚间距F = 2.0mm,可以使用其他5x11尺寸电容替代
  * 7.Top Layer Decorative Capacitor 2：RwbyCon Electrolytic Capacitor,YXF10V100uF,Diameter D = 5.0mm, Height H = 11.0mm, Pin spacing F = 2.0mm,Other 5x11 size capacitors can be used instead
  * 8.顶部装饰电容3：PowerStor法拉电容，C-TYPE0.22f，直径D = 13.0mm，引脚间距F = 5.0mm
  * 8.Top Layer Decorative Capacitor 3：PowerStor Faraday capacitor, C-TYPE,0.22f, Diameter D = 13.0mm, Pin spacing F = 5.0mm
  * 9.顶部装饰电容4：RXEF090自恢复保险丝，并不是电容
  * 9.Top Layer Decorative Capacitor 4：RXEF090 self-recovery fuse, not a capacitor
  * 10.顶部装饰电阻1：KOA1/4W金属膜电阻，阻值随意
  * 10.Top Layer Decorative Resistor 1:KOA1/4W metal film resistor, resistance value at will
  * 11.顶部装饰电阻2：KOA1/4W碳膜电阻，阻值随意
  * 11.Top Layer Decorative Resistor 1:KOA1/4W carbon film resistor, resistance value at will
  * 12.顶部装饰IC1：DIP-4
  * 12.Top Layer Decoration IC1: DIP-4
  * 13.顶部装饰IC2：DIP-8
  * 12.Top Layer Decoration IC2: DIP-8
  * 14.顶部装饰六角金属柱：M2.5，H = 7.0mm
  * 14.Top Layer Decorative Hexagonal Metal Column: M2.5, H = 7.0mm
### 3.电路设计
  * Info of NL-5441A：http://www.swissnixie.com/tubes/NL5441A/ \
---等待更新---

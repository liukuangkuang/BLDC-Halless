# BLDC-Halless

单片机: 基于JMT18F003Plus(51内核) </br>
开发平台：VScode + EIDE + Keil C51编译器 </br>
过零点检测：***纯ADC检测*** </br>
必要资源：  三路ADC(过零点检测)，六路PWM(驱动MOS管) </br>
可选资源：两路ADC(电压,电流检测)，PWM输入捕获(速度调节)，两个定时器(速度计算和换相延时，堵转保护)，CMP比较器(过流保护) </br>


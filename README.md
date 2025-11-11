# STM32_FAN_PWM_FG
使用STM32F103C8T6最小系统板来驱动四线散热风扇，可以通过PWM改变转速，可以读取FG信号并发送到串口。
开发软件使用STM32CubeIDE。
程序由AI生成，仅做个人测试和记录。
开发版：详情见文件资料
风扇规格：5V 0.2A
线序：VCC GND FG（黄） PWM（蓝）
硬件连接：PWM引脚接PA8，FG引脚接PA0。

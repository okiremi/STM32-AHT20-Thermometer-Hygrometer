# STM32-AHT20-Thermometer-Hygrometer
这是一个基于STM32F103C8T6微控制器和AHT20温湿度传感器制成的电子温湿度计项目，项目采用了OLED屏，通过I2C接口收集传感器采集到的数据并进行显示。
注意：该开源项目只包含与微控制器和外设有关的核心源代码，主要为aht20.c、font.c、i2c.c、main.c、以及oled.c，不包含其他复杂的配置文件。
最后的ioc文件为stm32cubemx配置文件，仅供参考。

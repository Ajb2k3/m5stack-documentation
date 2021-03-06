# Unit ADC

## 描述 DESCRIPTION

这是带自校准功能的16位模拟数字转换unit，相比ESP32芯片自带的ADC（12位）功能分辨率高了不少，意味着你可以测量更小幅值的电压等模拟量，也就是能测量更细微一倍的模拟量，比如采集心电电压做心电监护项目、做血压监测项目、高精度电压监控项目等等。unit集成的ADC芯片通过I2C接口与M5的主控通讯，可以设置成单周期转换和连续转换方式。

## 特性 FEATURES

-  ADC有16位分辨率，可以设置每秒采样8、16、32、128次以进行A/D转换
-  ADC芯片内部可以产生高达8倍的放大，从而可以采集幅值更小的模拟信号
-  能测量0~12V的电压输入
-  乐高孔接口

## 应用 APPLICATION

-  心电信号采集
-  血压测量
-  测力计

## 文档 DOCUMENTS

-  GitHub

   - [Arduino](https://github.com/m5stack/M5Stack)

-  Datasheet

   - [ADS1100](http://pdf1.alldatasheet.com/datasheet-pdf/view/619024/TI1/ADS1100.html)

-  [Purchase]()

<figure>
    <img src="assets/img/product_pics/units/M5GO_Unit_adc.png" height="300" width="300">
</figure>

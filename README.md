# ESP32-S2 市电功率计量

## 介绍

PZEM-004T是交流电参数通讯模块，本来想直接用Tasmota固件来接入openHAB。但是购买到的模块使用的是Modbus-RTU通讯协议(mandulaj/PZEM-004T-v30)，而Tasmota默认支持的是另一种协议(olehs/PZEM004T)。

MQTT通过Wifi将数据传输到MQTT代理再由openHAB订阅

## 其他硬件

DS18B20用于环境温度检测

## 开发环境

VSCode + platformio插件
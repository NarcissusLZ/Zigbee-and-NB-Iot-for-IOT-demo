# Zigbee-and-NB-Iot-for-IOT-demo
​		一个基于Zigbee和NB-Iot作为主要通信方式的物联网平台设计，其中还涉及到了AndroidAPP和物联网云平台的使用。仅做最低程度的展示，但是底层的连接方式之类不变，后续拓展成实际应用，可直接更改应用层的内容。

​		所使用的zigbee节点由本人在开源节点的设计上修改而来，已上传到GitHub上，采用14500的锂电池供电给cc2530芯片，亦或者使用usb供电，接口为mini-usb接口，电压5V，电流1A，通过AMS1117-3.3V降压为3.3V给cc2530供电。同时，在usb供电口，接线到了外围的一个排母，可供某些传感器节点使用5V电压，但是使用14500锂电池供电之时，或许会出现电压不足的现象，这点还请注意。

​		PCB板子由嘉立创打板并且SMT贴片，5片板子实际花费在300元左右。
        2022/4/19，上传安卓APP源码，该安卓APP仅作演示之用，请输入自己的onenetAPIKey后编译使用，功能简单，仅可展示数据。
        2022/4/25,上传zigbee节点的源码

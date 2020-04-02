# OpenMVX
a customized openmv camera,based on the openmv camera.
now only STM32H743+OV7725 FPC version (openMV4)
# OpenMVX is licensed under the GNU General Public Licence (GPL)V3.0
# 注意，此repository下开源的所有文件使用GPL V3.0协议，如果你用了这里的文件，那么你也要开源你的设计（也必须使用GPL协议）
根据微信公众号： 飞觞醉月    资料修改制作而成

（使用原版openmv二次修改而来，已包含原版openmv的license文件：master/openmv LICENSE.txt）
## 高频问题解答：  
## 为什么MCU两颗LDO供电？习惯而已，一颗也行，OV7725也可以公用，整个PCB就一个3.3V的LDO也行，只要电流够用。    
## DFU烧录固件卡在66%？这不是个例，我用的是硬件版本Y的芯片烧录固件完全正常，硬件版本V的芯片出现此问题，原因尚不清楚。
## 引出排针有个空脚？那是外部帧同步信号，BGA的OV7725有，FPC的OV7725没有这个引脚，为了与OpenMV官方版引脚兼容，此引脚悬空。



# The Drone Swarm Project

Firmware and specs: https://github.com/silver13/h8mini-acro 
-or- https://github.com/silver13/h8mini-dual
       -       https://www.rcgroups.com/forums/showthread.php?2512604-Eachine-H8-mini-acro-firmware 
 Wiki: http://sirdomsen.diskstation.me/dokuwiki/doku.php?id=docs:readme 
Pid: http://sirdomsen.diskstation.me/dokuwiki/doku.php?id=pid_silverxxx 

Open micro?:http://sirdomsen.diskstation.me/dokuwiki/doku.php?id=openmicro 

Blog: https://www.rcgroups.com/forums/member.php?u=524557 


Processor: GigaDevice GD32F130G6 cortex M3 32k flash 48Mhz CPU: 
https://www.keil.com/dd2/gigadevice/gd32f130g6/ 

Pin layout: https://upverter.com/parts/GigaDevice/GD32F130G6/ 

Hardware datasheet: https://app.box.com/s/3zi661iffmit1rwda499wu8vycv03biv 

Software datasheet: https://app.box.com/s/pehsanvluc40qu8k2036sbjk5ti08y2m 

Invensense gyro + accelerometer, MPU-6050 compatible mostly ( responds 0x78 to who am I): 
https://store.invensense.com/ProductDetail/MPU6050-InvenSense/422200/ 

XN297 transceiver:
https://opendevices.ru/wp-content/uploads/2017/03/XN297-Low-Power-2.4GHz-GFSK-Transceiver.pdf 

RC Protocol (10.21 Bayang): https://www.deviationtx.com/manuals/html-devo10/ch_protocols.html 
Flashing/ software tutorial: https://dronegarageblog.wordpress.com/2016/01/06/eachine-h8-open-source-firmware-with-acro-mode/ 

CMSIS
Cortex Microcontroller Software Interface Standard 


Youtube Tutorials: https://www.youtube.com/watch?v=X8vRhYHKWGk 
Makes dealing with assembly less necessary
Core: Basic c api functions for general use. (clks to interrupts)
Driver: used by middleware to connect other devices to the processor
DSP: Digital signal processing library w/ over 60 funtions
RTOS API:
SVD, DAP: both used for debuging

CMSIS is much faster to code in and better for most situations than  assembly

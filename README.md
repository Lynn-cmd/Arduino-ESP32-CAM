# Arduino-ESP32-CAM

ESP32-CAM 上传代码按键流程/ESP32 CAM CodeUpload Button Process
上传代码： 点击Arduino 上传按钮 ---》 然后依次按住开发板上的IO0 和RST ---》等出现connecting 时，依次放开 RST和 IO0.

CodeUpload：Click 'Code upload' on Arduino IDE -->Press and Hold the button  IO0 & RST on development board 
---->when the 'Connecting .......' message shows up in Arduino IDE ,then release 'RST' & 'IOT' by sequence.

https://gitee.com/xv-shuai/ESP32-CAM-Arduino-IDE/tree/master

Tips:
1).If u have problem with microSD read/write, try to change another one with better quality.

2).ESP32-CAM Troubleshooting Guide: Most Common Problems Fixed

https://randomnerdtutorials.com/esp32-cam-troubleshooting-guide/
Most common errors:
Failed to connect to ESP32: Timed out waiting for packet header

Camera init failed with error 0x20001 or similar

Brownout detector or Guru meditation error
If it reports:  Brownout detector or Guru meditation error,
 **try to change another better quality USB cable ,or change to a better 5v USB power supplier.** 

Sketch too big error – Wrong partition scheme selected

Board at COMX is not available – COM Port Not Selected

Psram error: GPIO isr service is not installed

Weak Wi-Fi Signal

No IP Address in Arduino IDE Serial Monitor

Can’t open web server

The image lags/shows lots of latency

esp_camera_fb_get(): Failed to get the frame on time!


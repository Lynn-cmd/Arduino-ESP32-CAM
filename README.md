# Arduino-ESP32-CAM

ESP32-CAM 上传代码按键流程/ESP32 CAM CodeUpload Button Process
上传代码： 点击Arduino 上传按钮 ---》 然后依次按住开发板上的IO0 和RST ---》等出现connecting 时，依次放开 RST和 IO0.

CodeUpload：Click 'Code upload' on Arduino IDE -->Press and Hold the button  IO0 & RST on development board 
---->when the 'Connecting .......' message shows up in Arduino IDE ,then release 'RST' & 'IOT' by sequence.

https://gitee.com/xv-shuai/ESP32-CAM-Arduino-IDE/tree/master

Tips:
1.If u have problem with microSD read/write, try to change another one with better quality.

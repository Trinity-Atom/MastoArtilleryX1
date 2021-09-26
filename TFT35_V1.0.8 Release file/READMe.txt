1、根据需要更新的内容把以下对应文件拷贝到SD卡：

 (1)、更新配置文件：mks_config.txt
 (2)、更新图片：    mks_pic
 (3)、更新字库：    mks_font
 (4)、更新TFT固件： mkstft35.bin
 (5)、更新Wifi固件：MksWifi.bin

2、使用SD卡更新配置文件时，需要把配置文件名修改为：mks_config.txt

3、可以参考Example文件夹中的例程

4、TFT35_V1.0.6修改内容：
（1）、修复回零界面“关闭电机”不工作问题
（2）、修复网络打印有时不转发数据的问题
（3）、双喷头打印中“变速”后“返回”喷头挤出不对
（4）、添加bootloader翻转功能
（5）、修改读卡错误打印停止问题
（6）、修复5次rend重定行出错问题

5、TFT70_V1.0.3修改内容：
（1）、修复自动调平按钮字体不显示问题。
（2）、修复状态按钮颜色不可配置问题。

6、TFT70_V1.0.4修改内容：
（1）、“操作”界面增加babystep调节按钮。
（2）、“更多”界面开放校准功能。

7、TF35_V1.0.5修改内容：
（1）、修正babystep调节数值过大问题
（2）、修正屏幕校准值不保存的问题

8、TF35_V1.0.6修改内容：	
（1）添加wifi扫描模式
    
（2）添加在线配置配置文件中的大部分配置参数
    
（3）添加马林固件在线参数调节功能，可配置脉冲、TMC驱动电流、加速度，探针偏移等基本参数
    
（4）添加Gcode控制台显示

9、TF35_V1.0.7修改内容：
（1）添加对UPS断电检测模块的支持
（2）修复预览显示异常的bug
（3）修复wifi传输异常以及带文件名带中文gcode的传输异常的漏洞
（4）增加wifi密码设置长度


10、TF35_V1.0.8修改内容：
（1）修复cura读取不到sd卡文件的问题
（2）修复断料检测对话框显示问题
（3）修复断料时蜂鸣器响应问题

//////////////////////////////////////////////////////////////

1,According to the content that needs to be updated, copy the following file to the SD card:

 (1)、update the config file：mks_config.txt
 (2)、update images：         mks_pic
 (3)、update font：           mks_font
 (4)、update TFT firmware：   mkstft70.bin
 (5)、update Wifi firmware：  MksWifi.bin

2,When using the SD card to update the configuration file, you need to change the configuration file name to: mks_config.txt

3, You can refer to the Example folder's routines.

4, The firmware of V_1.0.2 modified content :
(1)、Fix the bug that "zero" interface "turn off the motor" does not work.
(2)、Fix the bug that network printing does not transfer data sometimes.
(3)、Fix the bug that extrusion is error after change print speed and return in the double nozzle printing.
(4)、Added the ablity to display rotation of bootloader.
(5)、Fix the bug that print stop due to card reading error.
(6)、Fix the bug that define line number error after 5 times resend.

5，The firmware of V_1.0.3 modified content:
(1) Modify the font of the auto-leveling button is not displayed.
(2) Modify the status color can not be configured.

6，The firmware of V_1.0.4 modified content :
(1) The "operation" interface adds a babystep adjustment button.
(2) The "More" interface opens the calibration function.

7，The firmware of V_1.0.5 modified content :
(1) Fix the problem that the babystep adjustment value is too large.
(2) Fix the problem that the screen calibration value is not saved.

8, TF35_V1.0.6 modified content:
(1) Add wifi scan mode
(2) Add most of the configuration parameters in the online configuration configuration file
(3) Add Marin firmware online parameter adjustment function, can configure basic parameters such as pulse, TMC drive current, acceleration, probe offset, etc.
(4) Add Gcode console display

10, Modified content of TF35_V1.0.8:
(1) Fix the problem that cura cannot read SD card files
(2) Fix the display problem of the material break detection dialog box
(3) Fix the buzzer response problem when the material is interrupted


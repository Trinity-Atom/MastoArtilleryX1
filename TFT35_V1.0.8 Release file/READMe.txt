1��������Ҫ���µ����ݰ����¶�Ӧ�ļ�������SD����

 (1)�����������ļ���mks_config.txt
 (2)������ͼƬ��    mks_pic
 (3)�������ֿ⣺    mks_font
 (4)������TFT�̼��� mkstft35.bin
 (5)������Wifi�̼���MksWifi.bin

2��ʹ��SD�����������ļ�ʱ����Ҫ�������ļ����޸�Ϊ��mks_config.txt

3�����Բο�Example�ļ����е�����

4��TFT35_V1.0.6�޸����ݣ�
��1�����޸�������桰�رյ��������������
��2�����޸������ӡ��ʱ��ת�����ݵ�����
��3����˫��ͷ��ӡ�С����١��󡰷��ء���ͷ��������
��4�������bootloader��ת����
��5�����޸Ķ��������ӡֹͣ����
��6�����޸�5��rend�ض��г�������

5��TFT70_V1.0.3�޸����ݣ�
��1�����޸��Զ���ƽ��ť���岻��ʾ���⡣
��2�����޸�״̬��ť��ɫ�����������⡣

6��TFT70_V1.0.4�޸����ݣ�
��1��������������������babystep���ڰ�ť��
��2���������ࡱ���濪��У׼���ܡ�

7��TF35_V1.0.5�޸����ݣ�
��1��������babystep������ֵ��������
��2����������ĻУ׼ֵ�����������

8��TF35_V1.0.6�޸����ݣ�	
��1�����wifiɨ��ģʽ
    
��2������������������ļ��еĴ󲿷����ò���
    
��3��������ֹ̼����߲������ڹ��ܣ����������塢TMC�������������ٶȣ�̽��ƫ�ƵȻ�������
    
��4�����Gcode����̨��ʾ

9��TF35_V1.0.7�޸����ݣ�
��1����Ӷ�UPS�ϵ���ģ���֧��
��2���޸�Ԥ����ʾ�쳣��bug
��3���޸�wifi�����쳣�Լ����ļ���������gcode�Ĵ����쳣��©��
��4������wifi�������ó���


10��TF35_V1.0.8�޸����ݣ�
��1���޸�cura��ȡ����sd���ļ�������
��2���޸����ϼ��Ի�����ʾ����
��3���޸�����ʱ��������Ӧ����

//////////////////////////////////////////////////////////////

1,According to the content that needs to be updated, copy the following file to the SD card:

 (1)��update the config file��mks_config.txt
 (2)��update images��         mks_pic
 (3)��update font��           mks_font
 (4)��update TFT firmware��   mkstft70.bin
 (5)��update Wifi firmware��  MksWifi.bin

2,When using the SD card to update the configuration file, you need to change the configuration file name to: mks_config.txt

3, You can refer to the Example folder's routines.

4, The firmware of V_1.0.2 modified content :
(1)��Fix the bug that "zero" interface "turn off the motor" does not work.
(2)��Fix the bug that network printing does not transfer data sometimes.
(3)��Fix the bug that extrusion is error after change print speed and return in the double nozzle printing.
(4)��Added the ablity to display rotation of bootloader.
(5)��Fix the bug that print stop due to card reading error.
(6)��Fix the bug that define line number error after 5 times resend.

5��The firmware of V_1.0.3 modified content:
(1) Modify the font of the auto-leveling button is not displayed.
(2) Modify the status color can not be configured.

6��The firmware of V_1.0.4 modified content :
(1) The "operation" interface adds a babystep adjustment button.
(2) The "More" interface opens the calibration function.

7��The firmware of V_1.0.5 modified content :
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


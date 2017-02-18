# ��� �� ThinkPad

![](https://i.imgur.com/U9fUcGd.gif "��� �� ����")

***
 
## ��� �����������/��� ������?

����� ������ �������� �����. � ������������ ����������� � ������� ������. � ��������� ����� ����� �������� ���� �������� ����. ���� ���:
> They are especially harmful in models with LED backlight because the colors of the emitted light are not as inert as the colors of the CCFL backlight and so they reach high amplitudes and rapid luminance changes.

������ ������ ����� ����������. ��������� ���������� ��� �������� �� ������� � ��� � �� ��������� �����������, ����� ��� �� ������������� �������� ��� ��� ��������� ���������. �������� ����������� ������� � ������� ����� �������. ���� ���� ��������� ��� �������������.

�������, ��� �� 2��� ������ �� ����������� �������, �� ���� ���� ������. �� �������� ����������� �� ������� � �������, ���������, ��������, ������, ���� ������.

���� �� ���� �������� �� ���� ��������� ����� ������ �� �����. �� ����� ��������� ����, ��������� �������� � ��� ����� � �������������. � ��� ������ �������� � ������. �� ��� ������ ��� ������� ��� ���� ���� �������� ��������. ������ **�������������**.
 
**��� ��� ������ ����� � ��� ��������� ���� �����?**
- [http://brinservice.com/bolyat-glaza-ot-komputera-monitora.html](http://brinservice.com/bolyat-glaza-ot-komputera-monitora.html)
 
***

## �������� ��������� "�������":

**��� Windows**

- �������� �������� ������� IntelPWMControl ( ��������� [http://pastebin.com/6iirMbfc](http://pastebin.com/6iirMbfc)) [https://youtu.be/ycKzTDnTYTQ](https://youtu.be/ycKzTDnTYTQ) (�������� ������ �� X220 � T520 (����������� ����, � ������ 500-��))
 
**��� Linux**

- [https://devbraindom.blogspot.ru/2013/03/eliminate-led-screen-flicker-with-intel.html
](https://devbraindom.blogspot.ru/2013/03/eliminate-led-screen-flicker-with-intel.html)
- [https://wiki.archlinux.org/index.php/Backlight_(�������)#Backlight_PWM_modulation_frequency_.28Intel_i915_only.29](https://wiki.archlinux.org/index.php/Backlight_(�������)#Backlight_PWM_modulation_frequency_.28Intel_i915_only.29)
- �������� ��������� ������ ��� ����! � Added "intel_reg_write 0xc8254 0x07a107a1" to /etc/rc.local to get 500 Hz PWM on Toshiba C850 (default is 200 Hz).
 
��� ��������� ������ ���������:
- Intel ���� [https://01.org/linuxgraphics/documentation/driver-documentation-prms](https://01.org/linuxgraphics/documentation/driver-documentation-prms)
- Intel ���� �� sandy Brige [https://01.org/linuxgraphics/sites/default/files/documentation/snb_ihd_os_vol3_part3.pdf](https://01.org/linuxgraphics/sites/default/files/documentation/snb_ihd_os_vol3_part3.pdf)
 
������ � �����:
- Eliminate LED screen flicker with Intel i915
- backlight control in Linux
 
## �������� ����������� "�������":

- ��� X220/X230 �������� ������ ������� �� FHD. ��. ���� ����� ��� ���� �������;
- ������� ���� ����� �������/������� �� ��������. ���� ��������. 
 
***

## �������� Thinkpad'��:

**X1 Carbon GEN3 (FHD).** FAIL : ��� �����, ��� ������� ������ ��������� ������� �� ���� � ���� ������. ������ ����� �� ���� ����������, ����� ������� ������ �� ���������, ���� � ����.

**X1 Carbon GEN4 (FHD).** OK : �������� �������� �� ���������, ���� ������������� � ��������� 1/8000. x1 � g710 �� ���� [[����]](https://cloud.mail.ru/public/9qq8/jQEMwoKsz)
 
**X41t**
. OK : ��������� ������ � ������� ������������ � ��������� 1/8000 �������.
 
**60-��**

- T60. FAIL : [[����]](https://youtu.be/NKJhHK0bjpw)
- X60t. FAIL : 1024�768 ������� ����, ������ ��� �������� ����� � �������� ������������
 
**200-��**

- X201. FAIL: ����� �� ��� �201 ����������� ������ �� ������� �������. �� ����������� ����� �������. �� ������������ ��� ������ �� �������.
- X220 (IPS). FAIL: ����������� ���� ����� � ��������� ������ �������� ������� ��� �� ������� ���� 2/3. "������ ���� � ����������� �� 100 % ��������, ��� ��� ��� ����";
- X220 (IPS). FAIL: ��� �� �������������� ����� �� ����� [[����1]](https://youtu.be/apLyrzH-qNA) [[����2]](https://youtu.be/SpDdy9jSx7Y); ��� ������ ����� �� 9�30��� [[����3]](https://youtu.be/kOd0KFouWJY); 
- X220/X230. �������� �����������: ���������� ������� ����������� � ������� ������� �� FHD IPS. [[����]](https://www.youtube.com/watch?v=9b_dJzbXf7A) ���� �������: 4800 ��� (�������) + 3500 (����� ��� �����������). ����������� [[�����]](http://forum.thinkpads.com/viewtopic.php?f=43&p=792251);
- X230i (TN) : � ������� ������� �������� ������� �� 1000Hz, ����� �� �����. �������� ���������� � �������. ������ �� ���������� [[����]](https://devbraindom.blogspot.ru/2013/03/eliminate-led-screen-flicker-with-intel.html)
 
**400-��**

- T410. FAIL : [[����]](https://youtu.be/ycKzTDnTYTQ);
- T420. FAIL: 1366�768. ��������� �������������: �� 1/320 ���. ��� ���������� ������ �������, �� 1/400 ���. ��� ���� ������
- T430. FAIL : (����� �� 11:20) [[����]](https://youtu.be/8LtMuZ4DQjQ);
- T430. FAIL : ���� ���� [�����](https://cloud.mail.ru/public/EGvg/k7U5NPKRa);
- T440. OK : [[����]](https://cloud.mail.ru/public/M97n/UKD1boDuW)
- T460. OK :
  - ���� ���� [�����](https://cloud.mail.ru/public/12ju/iEPyUtv2s) (�� ����� ������� � ��������� �� �������� ������ - ������� ���������, ��������, ��-�� ������������� ������� � ������ ��������, �� ������� ��� ��������� );
  - ��������� �� [notebookcheck.net](http://www.notebookcheck.net/Lenovo-ThinkPad-T460p-Notebook-Review.160923.0.html)
- L450. FAIL : ��� �� ���� ��������� �������, ����� ������������� (����������� ����)
 
**500-��**

- L510 (TN). FAIL : [�������� �����](https://cloud.mail.ru/public/CfK2/Qqe94qjUs) � ������� ������������ (�������� 1/800). ������� ������ �������;
- T520. FAIL (������� ���������� � ������� intelPWNcontrol): [[����]](https://cloud.mail.ru/public/6Mj2/zbYVTp5UD);
- T530. FAIL. � ����������� ���� ���� ���. ���� �������� �������������. �� ������� ������� ��� ��� ���� ��� �� �������.
 
***

## ������ ������ ������:

- ��� ���� ������ �� ����� � ���-���� ��������. �������� ����������� ������� �� 13 �� 15, ��� ������ �������� �� ���. ����� ���� � TN, �� ����� ������� ����� ���� ������� ��� ����.
- � ������ ��� (Flicker Fri) �� �������� ���������� ���-����������� �������. � �������� ��������� ��������� ��� �� ���. ��� ������� ������ ��������������, ����� ������ ������������� �����.
- ���� x201 (������� ��� � ����.������) ��� ����, ������� �� 13 ����� � ���� ������ ��� ���� ���, ����������� ���. ���������� ���������� ���� �� (seriously)
- � ���� ����� �� ������� �������� ������ (~200) ��� ������ � ������� ������ ��������� ���� ��������� ��������, ��� �������� �������� � ������
- �������, ��� �� 2��� ������ �� ����������� �������, �� ���� ���� ������. �� �������� ����������� �� ������� � ������� ��������� �������� ������ ���� ������, ����� � ��� �������.
 
������ �� �����: http://pastebin.com/ZRxfz3Ax
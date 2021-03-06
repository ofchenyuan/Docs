MicroPython X IDE
====================

软件安装
-----------

目前最新版本为0.2.4，支持Windows 7/8/10、Windows XP、Macos、树莓派、虚谷号： 

http://static.steamaker.cn/files/MicroPythonXSetup0.2.4.exe
(Win 7 / 8 / 10)

http://static.steamaker.cn/files/MicroPythonXSetup0.2.4_XP.exe
(Win XP)

http://static.steamaker.cn/files/MicroPythonx-0.2.4-mac.zip
(Mac OS)

http://static.steamaker.cn/files/MicroPythonx-0.2.4-arm.tar.gz
(树莓派)

http://static.steamaker.cn/files/MicroPythonx-0.2.4-arm64.tar.gz
(虚谷号，待测试)

附：板子的Mac驱动

https://www.silabs.com/documents/public/software/Mac_OSX_VCP_Driver.zip

.. Hint::
  
  安装过程有可能被杀毒软件误报病毒，需要选择“允许程序所有操作”。


安装软件的最后一步，会自动安装CP210x的驱动，如果先前安装过则可以忽略。

.. image:: /images/software/software_2.png



接入硬件
-----------

点击桌面快捷方式MicroPythonX，打开软件主界面。

.. image:: /images/software/MicroPythonX/MicroPythonX_1.png


用USB线接入板子。正确识别后，“连接串口”处会出现COM口，如下图：

.. image:: /images/software/MicroPythonX/MicroPythonX_2.png



上述顺序可以颠倒，即：可以先接入掌控，再打开软件。


图形编辑区
-----------

保存
````````

“保存代码”只保存程序对应的代码，后缀为py：

.. image:: /images/software/MicroPythonX/MicroPythonX_3.png

点击“本机读取”，加载保存的py文件：

.. image:: /images/software/MicroPythonX/MicroPythonX_5.png

读取效果如图：

.. image:: /images/software/MicroPythonX/MicroPythonX_4.png

“保存模块”保存程序对应的代码及图形化模块，后缀为xml：

.. image:: /images/software/MicroPythonX/MicroPythonX_6.png

点击“本机读取”，加载保存的xml文件，读取效果如图：

.. image:: /images/software/MicroPythonX/MicroPythonX_7.png

模块提示
````````
鼠标停留在模块上会有提示：

.. image:: /images/software/MicroPythonX/MicroPythonX_8.png

帮助文档
````````
在模块上，点击鼠标右键：

.. image:: /images/software/MicroPythonX/MicroPythonX_9.png

点击帮助，即可跳转至帮助文档：

.. image:: /images/software/MicroPythonX/MicroPythonX_10.png

切换图形/代码模式
````````

点击“代码模式”/“图形模式”，即可实现对应切换：

.. image:: /images/software/MicroPythonX/MicroPythonX_11.png

.. image:: /images/software/MicroPythonX/MicroPythonX_12.png

改变图形区/代码区大小
````````

鼠标停留在圈红的灰色三角上，按住左键左右拖动即可：

.. image:: /images/software/MicroPythonX/MicroPythonX_13.png


代码编辑区
-----------

代码联想：

.. image:: /images/software/MicroPythonX/MicroPythonX_14.png


运行/刷入
-----------

运行/刷入
````````

运行/刷入两种模式皆可实现程序效果。

点击“连接串口”，按钮字样变成“断开连接”，即可开始运行/刷入：

.. image:: /images/software/MicroPythonX/MicroPythonX_15.png

.. Note::

  “运行”的代码脱机后即失效，“刷入”的代码脱机后再次连接电源仍有效

代码查错
````````

圈红处是反馈的信息，包括硬件信息、代码报错信息等：

.. image:: /images/software/MicroPythonX/MicroPythonX_16.png

比如，红字为代码报错信息：

.. image:: /images/software/MicroPythonX/MicroPythonX_17.png

读出上一次刷入的代码
````````

点击“从掌控读出”即可读出上一次刷入的代码。


恢复固件
-----------

点击“恢复固件”，按照提示操作：

.. image:: /images/software/MicroPythonX/MicroPythonX_18.png

.. Hint::
  
  如果恢复固件失败（或超过30秒仍然一直在恢复），请先尝试关闭杀毒软件，或者选择信任esptool。





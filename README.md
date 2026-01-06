# hackintosh
Kang-Maxsun-B760i-efi

参考自https://github.com/rbongIO/rbongIO-MaxSun-B760ITX-EFI.git

更新了kext与oc（版本1.06），在sequoia 15.6系统上可以正常驱动

重新配置了wifi与蓝牙，WiFi配合heliport使用

电脑配置

主板：B760i 铭瑄 D4 

CPU：Q0L5 13700es 

内存：金百达 16g*2 3600mhz（运行在3200mhz）

显卡：迪兰6800xt 16g

硬盘：SN750 500G

网卡：AX211

之前测试rbongio的efi可以驱动12400，但是用Q0L5会卡启动，重新升级了内核，就可以启动了。

蓝牙配置的帖子参考于这个，https://www.reddit.com/r/hackintosh/comments/1fsvhsj/finally_i_made_my_bluetooth_work_in_sequoia/?tl=zh-hans

这个是重新设计的蓝牙固件与修复器，如果不能驱动再找方案，本人电脑测试过，是找到的唯一方法。

本efi已经关闭了sip与amfi，如需恢复，请自行在boot中设置参数。

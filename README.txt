﻿openwrt-wrt1x00ac-patchs
=================================================


简述:
    这是我购买WRT1200AC后，为其编译基于OpenWrt的固
    件时，对源码所做更改的补丁集，会陆续把补丁放上
    来。打补丁时从OpenWrt源码的根目录开始打即可。

文件概述:
    [1] luci_marvell_switch.patch
        针对marvell交换机在luci的交换机页面添加端口
        状态显示。
    [2] openwrt_marvell_switch.patch
        修改OpenWrt的默认设置以在luci中显示交换机页
        面。
    [3] 5GHZ_NAS_BrokenFix.patch
        修正系统保留内存过少导致5GHZ读写NAS时中断的
        问题。
    [4] luci_processes_status_Fix.patch
        修正luci状态页面不显示系统进程的问题


测试环境:
    在 OpenWRT 15.05.1 上开发


依赖关系:
    无


作者:
    穿越蓝天 (animefans_xj / 穿越蓝天)
    你可以在这里找到我:
        数码之家 bbs.mydigit.cn
        恩山论坛 www.right.com.cn
    也可以通过电邮反馈:
        af_xj@hotmail.cn
        xujun@smm.cn


授权:
    此程序的当前版本采用GNU GPL V3协议授权，请务
必保持分支版本的代码公开。
    你可以在 http://www.gnu.org/licenses/licenses.html
取得授权协议的副本。


发布:
    除上述站点外，所有资源也通过github以及以下站
点发布:
      http://pan.baidu.com/s/1qYms3fu#path=%252FSoftware%252FRouter

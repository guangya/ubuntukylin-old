---
title: Windows 7安装虚拟机VMware Workstation Player 15.5.7
---

## Windows 7安装虚拟机VMware Workstation Player 15.5.7

> VMware Workstation Player前身为VMware Player，是一款桌面虚拟化应用软件，用户无需重新启动物理主机即可在同一计算机上运行一个甚至是多个操作系统。VMware Workstation Player具有简单的用户界面、丰富的操作系统支持，用户可以比以往更轻松地处理多系统环境的工作，提高工作效率。

### 系统要求

Windows 7 64位系统

32位的Windows 7系统可以安装VMware Player 12。由于32位Windows使用比较少，本篇教程暂时不涉及。

### 下载

方法一：阿里云盘下载

[阿里云盘分享](https://www.aliyundrive.com/s/xKU1fGUqRnq)

方法二：官网下载（官网下载不稳定，推荐使用阿里云盘下载）

打开链接

[VMware Maintenance](https://my.vmware.com/en/web/vmware/downloads/details?downloadGroup=WKST-PLAYER-1612&productId=1039&rPId=66621)

![img](https://pic3.zhimg.com/v2-e6dfc60c509c2c966d286e711ef785e6_b.png)

VMware Player 16已经不再支持Windows 7系统，我们需要点击上图红色框中下拉菜单，切换的版本15

![img](https://pic2.zhimg.com/v2-2302f65626bdd7b3bd9c5109d20fb3d9_b.png)

点击按钮“转至下载“，进入下载页面

![img](https://pic2.zhimg.com/v2-72e0aa511820f964fa0cdc9c2b551cc1_b.png)

整理这篇文章时，版本15下的最新子版本为15.5.7，不用修改，直接点击“立即下载”按钮，浏览器会自动开始下载，下载时间取决于网络状态和带宽，请耐心等待。

### 安装

![img](https://pic4.zhimg.com/v2-e2583c6bbab2c0fb12fd2310c7ccef1b_b.png)

文件下载完成后，在我的电脑中找到刚才下载的安装包，双击启动安装程序

![img](https://pic2.zhimg.com/v2-62bae9e4131f1cee5d90924e043ca081_b.png)

弹出上面的窗口后，直接点击下一步

![img](https://pic4.zhimg.com/v2-740c177045d3cb10d6171caf1a99423f_b.png)

勾选“我接受许可协议的条款(A)“后，点击下一步按钮

![img](https://pic4.zhimg.com/v2-be0605d5cc192fadff3e254956ced123_b.png)

这里你可以选择安装位置，如果C盘空间足够，可以保持不变。另外，如果你使用的是机械硬盘，建议安装在C盘以提高运行效率。这个不会影响后面创建虚拟机的位置，你依然可以把创建的虚拟机放在任意盘中。由于我的C盘空间不足，选择安装在D盘。

![img](https://pic1.zhimg.com/v2-24be8b45749bdcbe5558aabc0ac6f120_b.png)

修改完成后，点击下一步

![img](https://pic1.zhimg.com/v2-ca9ff743dee8f8f6d95448a026a37718_b.png)

建议勾选“启动时检查产品更新”，取消勾选“加入VMware客户体验提升计划”，这个选项会在软件崩溃时向VMware发送软件的使用日志，减慢恢复过程。设置好后，点击下一步

![img](https://pic4.zhimg.com/v2-db374248606815ddf8fbcba8ec88ab0f_b.png)

可以选择在桌面和开始菜单程序文件夹中创建快捷方式，为了方便使用，这里我全部勾选了。

![img](https://pic1.zhimg.com/v2-48bd33ca845b38d03f805a5fc34bb958_b.png)

进入到这一步，我们需要设置的内容已经结束了，点击“安装”按钮后，就会进入具体的安装和文件复制流程，如果你此时反悔，点击“取消”或者关掉窗口后，软件不会对你的电脑进行任何修改。很明显，本教程必须点击“安装”

![img](https://pic3.zhimg.com/v2-d80a97b2610e253c4e3b323f742a960e_b.png)

![img](https://pic2.zhimg.com/v2-c90dbb9fb664b8b7ad1f8885bfaa745d_b.png)

![img](https://pic2.zhimg.com/v2-42057d68297ac390594dcb53d38b3afd_b.png)

![img](https://pic3.zhimg.com/v2-c2e7621ad71d4e4df0496c0a00f92dd2_b.png)

![img](https://pic3.zhimg.com/v2-b424eee555c710f79680ba0b711c7cce_b.png)

当进入到上面这个界面时，表示安装已经完成。如果您有购买过正版的授权，可以点击“许可证”进行授权码的输入验证。或者，也可以直接点击“完成”按钮，这并不影响基础功能的使用。

![img](https://pic2.zhimg.com/v2-6ccdbea1d879e3eaf23b1f682203572d_b.png)

如果在上一步中您没有输入许可证号，在软件第一次启动时，会提示输入许可证密钥或者在非商业用途中免费使用，只需要选择免费使用即可。

![img](https://pic2.zhimg.com/v2-f8384f8332c440ac4b9dede35b15f6a5_b.png)

![img](https://pic1.zhimg.com/v2-dda3c77c23c2642e72ae6f021eb862f0_b.png)

### 结束语

到这里，VMware Workstation Player已经安装完成，后续作者会整理更多相关的使用教程，欢迎关注个人专栏。

本文最后更新于2021.07.21，内容具有时效性，如您发现文中存在错误、遗漏、不当或过时的章节，欢迎在评论区留言指正，让我们一起进步。
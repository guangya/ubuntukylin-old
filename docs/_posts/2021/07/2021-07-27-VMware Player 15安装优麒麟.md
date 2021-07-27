## 虚拟机安装优麒麟Ubuntu Kylin 20.04 LTS Pro：Windows 7 + VMware Player 15

### 系统要求

Windows 7 64位

VMware Player 15虚拟机软件（已更名为VMware Workstation Player）

如果您还未安装VMware Player ，可以参考这篇教程进行安装：

[神经蛙：Windows 7安装虚拟机VMware Workstation Player 15.5.7](https://zhuanlan.zhihu.com/p/391728223)

### 下载系统镜像

方法一：阿里云盘下载

阿里云盘暂时不支持iso文件的分享，下载链接待阿里云盘开放后再做补充。

方法二：官网下载

优麒麟开源操作系统镜像下载www.ubuntukylin.com

![img](https://pic3.zhimg.com/v2-6f4c330c8f70ce003d42d89eea0d6f92_b.png)

官网打开后，根据你的需要，可以选择下载64位版本或者x86版本（按钮旁边的小字，凸显了官方推荐你下载64位版本的强烈意愿）。

![img](https://pic4.zhimg.com/v2-437b769ef293ada69fad92c13cb9aa47_b.png)

### 系统安装

首先，打开VMware Player 15

![img](https://pic4.zhimg.com/v2-e302f3983ba55e828d3a46f4aa16d91f_b.png)

点击上图中的“创建新虚拟机”

![img](https://pic1.zhimg.com/v2-4b80d942d86f0730b2ff0838cfcf4a24_b.png)

这里选择“稍后安装操作系统”，方便对新虚拟机的硬件进行配置

![img](https://pic2.zhimg.com/v2-b7204c457411d4ebf1396818b74d65c9_b.png)

选择客户机操作系统选择：Linux，版本选择：Unbutu 64位。这里解释一下，客户机操作系统，指的是我们将要安装的操作系统，VMware Player所在的计算机系统称为宿主机操作系统。选择完成后，点击下一步

![img](https://pic3.zhimg.com/v2-95b6a436bff6ac9bbdfa7f699201e41a_b.png)

这里可以修改虚拟机的名称和安装位置，由于作者的C盘空间不足，需要安装在D盘或者其他任意磁盘

![img](https://pic1.zhimg.com/v2-d0b89f5a0c92219e5c6b5cbf639d9f10_b.png)

虚拟机的名字你也可以使用简单一点的，只要是能区分就行了。编辑完成后，点击下一步

![img](https://pic2.zhimg.com/v2-3f0dc50d6b2307e8e8193c59b6e1b2c1_b.png)

这里是位虚拟机分配的总磁盘大小，官方建议不小于20GB的磁盘空间。虚拟机创建后，不会立即占满分配给它的空间，读者可以根据自己磁盘空闲空间的大小自由决定，这里以60GB为例。

![img](https://pic1.zhimg.com/v2-67f1f08ecd4acb83ef128c40da41bb1c_b.png)

关于拆分还是单个文件的问题，如果你不明白其中的区别，直接选择默认就可以了

![img](https://pic4.zhimg.com/v2-fefbf81a5d9971568c2dc2bab376c2bf_b.png)

点击“自定义硬件”打开虚拟机设置窗口

![img](https://pic4.zhimg.com/v2-2b7a14fb27727d576ab380c0da44335f_b.png)

虽然官方建议内存大小为1GB（1024MB），但如果你的电脑内存是16GB的，不妨分配4～8GB给虚拟机以提升使用体验。这里以2GB为例。

![img](https://pic4.zhimg.com/v2-604a7b4f4bbd7e9151a762fecc2164bf_b.png)

点击左侧的处理器，可以修改处理器的核心数量，根据你的CPU性能也可以选择增加或者减少核心数。

![img](https://pic4.zhimg.com/v2-739110b9fea0fbab61100b1ed4df8ac7_b.png)

点击浏览按钮，选择我们下载好的Ubuntu Kylin镜像文件（扩展名.iso）

![img](https://pic4.zhimg.com/v2-7279671eddb8e0071b33d0200d0fcc37_b.png)

点击打开按钮

![img](https://pic2.zhimg.com/v2-3c83fbcfb34e0b936f6f596fbb1fb5fd_b.png)

网络适配器和其他配置项可以保持默认，系统安装完成后还可以做修改，不需要担心。点击关闭按钮，关掉硬件设置窗口

![img](https://pic3.zhimg.com/v2-b15e7261688d7bbdb4fc06ceef13e932_b.png)

回到新建虚拟机向导窗口后，点击完成按钮

![img](https://pic2.zhimg.com/v2-24da4c1ea53cf476d1fd73530be6832d_b.png)

点击“播放虚拟机”

![img](https://pic4.zhimg.com/v2-3192f53bed3a3ca32dcfa6beacdb9337_b.png)

![img](https://pic2.zhimg.com/v2-06848961b9aef39c49bfbb3d04f7e2e1_b.png)

第一次打开时，会提示安装Vmware Tools for Linux，点击“以后提醒我”，我们等系统完成后再进行安装。

![img](https://pic2.zhimg.com/v2-dfa6609197f8ee74a8059c7dcab4a629_b.png)

下面的提示栏也点击“以后提醒我”

![img](https://pic1.zhimg.com/v2-3670a1fbdf51c5252b6f92ab44044084_b.png)

这里可以按下组合键Ctrl + C取消硬件检测，建议不要执行任何动作，等待检测完成

![img](https://pic3.zhimg.com/v2-deb00d3c2fcc96273677423416b60516_b.png)

点击安装 Ubuntu Kylin

![img](https://pic1.zhimg.com/v2-68f70a2aa29149a9ee658fb53e401f24_b.png)

选择键盘的布局，一般不需要修改，点击“继续”按钮进入下一步

![img](https://pic2.zhimg.com/v2-395732986ee97735c43ccf2252f66241_b.png)

重要：为确保安装顺利进行，并减少安装的等待时间，这个选项一定要取消勾选。

如果是在物理机安装，请勾选“为图形或无线硬件，以及其他媒体格式安装第三方软件”，以避免可能存在的兼容性问题。在虚拟机中一般不需要勾选

点击“继续”按钮，进入下一步

![img](https://pic3.zhimg.com/v2-4e030dd2313fd037ace73869c21d57da_b.png)

选择“清除整个磁盘并安装Ubuntu Kylin“，整个磁盘指的是我们分配给虚拟机的虚拟磁盘，不会对物理磁盘和分区造成损坏。如果你对linux的分区比较熟悉，也可以选择“其他选项“来手动设置分区。本篇教程面向初学者，这里选择自动创建。

点击“现在安装”按钮，开始Unbunt Kylin的安装

![img](https://pic4.zhimg.com/v2-7b88eb118d0371fe0a8fe8465ffefe0b_b.png)

点击“继续”按钮，进入下一步

![img](https://pic2.zhimg.com/v2-9a22bb66699d8646ca4b6e0f463d8861_b.png)

根据提示，完整填写下图中需要填写的内容。为方便使用，我选择“自动登录”，在虚拟机启动时，就不用输入用户名、密码进行登录了。输入完成后，点击“继续”进入下一步

![img](https://pic3.zhimg.com/v2-5a461a43c12c092279c2a1aa6fe907be_b.png)

漫长的安装过程

![img](https://pic4.zhimg.com/v2-63630f7c57d31ce8cd42efcf3e8ac457_b.png)

![img](https://pic1.zhimg.com/v2-9edb843b6de811af2b95f87570ed8a14_b.png)

我们选择的是LTS版，官方提供5年的系统支持和更新。

![img](https://pic4.zhimg.com/v2-f346525f9eaab6d11b728bb910b94e77_b.png)

当出现下面这个界面的时候，恭喜你，安装已经完成了。点击“现在重启”即可启动系统

![img](https://pic2.zhimg.com/v2-9782d28628fd644cddf957bcef22f391_b.png)

系统重启中

![img](https://pic3.zhimg.com/v2-57e42801d406da38939d90723ea9146a_b.png)

当出现下面这个界面时，我们需要按下回车键（Enter）

少了关键的一张图，重新走一遍流程后补充

系统启动中

![img](https://pic3.zhimg.com/v2-a4c636f3e89ced15b5703f2314251696_b.png)

![img](https://pic4.zhimg.com/v2-598a392ba3477efb7110fe10805243a7_b.png)

由于安装过程中选择了自动登录，系统启动后，不会打开系统登录窗口，直接进入了桌面

![img](https://pic1.zhimg.com/v2-d4f00c3bc55445c613bd37007360b3b0_b.png)

恭喜你，Ubuntu Kylin安装完成，系统提供了很多有用的功能，马上开始尝试吧。

![img](https://pic4.zhimg.com/v2-fb542071025a2693c867cf2e69b00f1f_b.png)

本文最后更新于2021.07.22，内容具有时效性，如您发现文中存在错误、遗漏、不当或过时的章节，欢迎在评论区留言指正，让我们一起进步。
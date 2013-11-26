# 云存储项目Seafile与ownCloud的比较 #

  组名：OpenSource1108  张德军，david1108
 
&emsp;&emsp;云存储是在云计算(cloud computing)概念上延伸和发展出来的一个新的概念，
是指通过集群应用、网格技术或分布式文件系统等功能，将网络中大量各种不同类型的存储设备通过应用软件集合起来协同工作，
共同对外提供数据存储和业务访问功能的一个系统。 当云计算系统运算和处理的核心是大量数据的存储和管理时，
云计算系统中就需要配置大量的存储设备，
那么云计算系统就转变成为一个云存储系统，所以云存储是一个以数据存储和管理为核心的云计算系统。

&emsp;&emsp;    Seafile 和  ownCloud 是两个常用的云存储的开源项目，本文主要介绍这两个项目，并对这两个项目进行分析和比较。

## 1、项目介绍
## Seafile ##
&emsp;&emsp;Seafile 是北京海文互知网络技术有限公司开发的一款开源的云存储平台，Seafile 的目标是打造一个创新、高质量的云存储平台，以解决企业和团队的文件管理难题
是一个专业可靠的企业云存储平台，可比喻为企业的文档中心，能极大的提高企业的办公效率。
本项目提供
文件共享和同步
在线协作
移动办公
三种主要功能
Seafile 包含个人空间、群组空间和企业公共空间。用户可以在私人间、群组中或公司范围内创建和共享资料库。一个资料库可以看成是一个顶层目录，可以单独的共享、同步。

&emsp;&emsp;在线协作方面，用户可以在线查看文档，对文档进行讨论。群组讨论和私人讨论功能让用户的协作交流变得很便利。此外，文件的版本管理功能，历史版本恢复功能使得多人修改变得更加的安全可靠。

&emsp;&emsp;移动办公方面，Seafile 有 iOS/Android 移动客户端。用户可以在移动设备上查看最新改动、访问文件资料、进行群组讨论等等，方便的实现移动办公。

&emsp;&emsp;设计说明
&emsp;&emsp;Seafile 设计中包含了互联网软件的开放参与 (openness, participation) 的思想。我们鼓励用户来自发的创建群组、进行协作，而不是自上而下的由管理员设置好固定的群组、固定的文件分类。

Seafile 的另一个设计思想是简洁易用、去繁存简。比如，Seafile 中没有复杂的权限设置，每个资料库在共享的时候可以选择只读或读写权限，配合群组功能，这已经能满足基本所有的使用场合。



## ownCloud ##

&emsp;&emsp;Owncloud：自由软件，由KDE社区开发的私有云服务器。目前功能包括文件管理、音乐存储、日历、联系人等等。Owncloud可以运行在本地或服务器上。
*支持音乐流
*可将日历和联系人与Thunderbird邮件客户端、Kontact或Evolution有效结合；
*一键分享文件
*支持WebDAV，可通过Nautilus或Dolphin等文件浏览器插件文件，支持iOS和Android（需借助第三方应用）

目前，该工具功能尚不完全，缺少加密、桌面同步客户端。还有在线文本编辑器、任务管理器、加密、桌面同步客户端等处于开发中。同时，版本控制、恢复功能也在计划之中。

提示，牛人也可以自己个性化应用。
针对个人的云存储服务Dropbox如今人见人爱，已经拥有超过5000万用户。但对于企业IT部门来说，
Dropbox让人头疼的问题也恰恰在于其面向个人的产品属性。那么是否有一种产品既能够满足企业用户的数据安全要求，同
时又能够提供类似Dropbox讨用户喜欢的漂亮界面呢？基于Linux的开源云计算项目——OwnCloud也许就是IT经理们苦苦寻找的企业版Dropbox解决方案。

ownCloud 2012的商业和企业版本目前已经发布，最新版本能够满足上述IT经理们的诉求——即使他们没有自己的存储云，OwnCloud 2012让IT经理们很容易就能将数据中心的数据转移到任意一个公共云里，无论是亚马逊、谷歌还是微软的云，通过浏览器或WebDAV进行管理。OwnCloud的另外一个亮点是拥有类似Dropbox那样易用的UI，而且最终用户可以通过PC或者移动设备访问数据。

OwnCloud 2012支持Linux、Windows、Mac电脑以及运行Android和iOS的移动设备。（目前还不支持Blackberry黑莓、Windows和Symbian手机）

OwnCloud的首席执行官Markus Rex（前Novell SUSE LInux业务部门高级副总裁）表示：OwnCloud的软件运行于企业的数据中心，IT部门可以通过它来上传和管理任意公共云的企业数据。

OwnCloud出身于开源，过去也一直是一个免费产品，OwnCloud 2012 是迄今发布的第一个商业版本。

在ownCloud上传和下载的数据都通过HTTPS加密，甚至还能进行操作系统级别的加密。企业终于能放心将OwnCloud服务器放到公有云而无需担心安全性问题，企业还能将运行OwnCloud的服务器与入侵侦测等安全工具进行集成。

Rex坦承Dropbox刺激了企业级云存储市场的迅速发展：”我们在模仿Dropbox的用户体验。Dropbox开创了全新的市场，此前企业级IT产品和服务提供商对这个市场一无所知。我们希望OwnCloud在拥有Dropbox的优秀用户体验的同时，又能够应用在企业自身的数据中心和安全模式。“

OwnCloud 商业版的起步价是999美元/年，最大支持50个用户，企业版的基础价格是1.5万美元/年，最大支持250个用户。

ownCloud此前得到了General Catalyst的资金支持。



## 2、功能比较 ##

##&emsp;&emsp;Seafile##
<table border=1>
  <tr>
    <td width="68" valign="center" ><p >类别 </p></td>
    <td width="141" valign="center" ><p >功能 </p></td>
    <td width="286" valign="center" ><p >说明 </p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >共享和同步 </p></td>
    <td width="141" valign="center" ><p >全平台支持 </p></td>
    <td width="286" valign="center" ><p >客户端还有安卓和ios版本 </p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >群组共享 </p></td>
    <td width="286" valign="center" ><p >支持创建群组 </p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >外链 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >版本管理 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >共享和同步子目录 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >搜索 </p></td>
    <td width="286" valign="center" ><p >可以搜索特定范围内的特定类型的文件 </p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >在线协作 </p></td>
    <td width="141" valign="center" ><p >Doc/PPT&nbsp;在线预览 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >文本文件在线编辑 </p></td>
    <td width="286" valign="center" ><p >支持在线富文本格式 </p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >文件评论 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >群组讨论 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >Wiki&nbsp;功能 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >私人消息 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >事件流 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >邮件通知 </p></td>
    <td width="286" valign="center" ><p >通知未读消息和讨论 </p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >移动办公 </p></td>
    <td width="141" valign="center" ><p >文件查看、编辑和离线使用 </p></td>
    <td width="286" valign="center" ><p >支持&nbsp;iOS/Android&nbsp;平台 </p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >事件提醒 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
  <tr>
    <td width="68" valign="center" ><p >&nbsp;</p></td>
    <td width="141" valign="center" ><p >群组讨论 </p></td>
    <td width="286" valign="center" ><p >&nbsp;</p></td>
  </tr>
</table>


## &emsp;&emsp;ownCloud ##

<table width="459" border="1">
  <tr>
    <td width="449">全平台支持：客户端还有安卓和ios版本；</td>
  </tr>

  <tr>
    <td>可以分享，同步；</td>
  </tr>
  <tr>
    <td>有版本控制，类似dropbox的版本功能；</td>
  </tr>
  <tr>
    <td>可以加密自己的数据（不是https），这里指的是可以给自己的数据设置密码，使得拥有服务器的人不可以随意查看你的数据；</td>
  </tr>
  <tr>
    <td>支持拖拽上传（有趣的是，国内网盘那么多，竟然都不支持拖拽上传？？？！！！）</td>
  </tr>
  <tr>
    <td>主题随意变；</td>
  </tr>
  <tr>
    <td>文件预览：pdf（使用的是mozilla的pdf.js）、image</td>
  </tr>
  <tr>
    <td>内置日历、通讯录、音乐播放器、视频播放器、书签等，可以说，你能想到的功能，它都放进来了；</td>
  </tr>
  <tr>
    <td>支持导入外部数据：ftp、dropbox、google drive等</td>
  </tr>
</table>




## 3、结合自身需要评估后的结论 ##

&emsp;&emsp;公司准备采用一款开源项目搭建一个私有云存储，经过评估，一致认为Seafile更符合国人的操作习惯，功能也比较强大，另外对手机(Android、IOS)的支持较好。

 
## 4、参考资料 ##

https://seacloud.cc/group/3/wiki/%E4%B8%93%E4%B8%9A%E7%89%88%E4%BB%8B%E7%BB%8D/
http://www.ctocio.com/ccnews/5245.html

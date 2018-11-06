## 概述

网络钓鱼事件在网络世界中每时每刻都在发生，各种欺诈手段花样翻新，防不胜防。而这其中有一类钓鱼手段是黑客最常用的那就是邮件钓鱼。钓鱼邮件通常可以分三个类别：**链接钓鱼邮件**、**附件钓鱼邮件**以及**邮件头伪造钓鱼邮件**（或者叫仿冒邮件）。

## 钓鱼邮件类型

![email-1](https://github.com/bloodzer0/Enterprise_Security_Build--Open_Source/blob/master/Infrastructure%20Security/Office%20Security/Email%20Security/img/email-1.png)

## 原理说明

### 链接钓鱼
![email-2](https://github.com/bloodzer0/Enterprise_Security_Build--Open_Source/blob/master/Infrastructure%20Security/Office%20Security/Email%20Security/img/email-2.png)
### 附件钓鱼
![email-3](https://github.com/bloodzer0/Enterprise_Security_Build--Open_Source/blob/master/Infrastructure%20Security/Office%20Security/Email%20Security/img/email-3.png)

### 邮件头伪造钓鱼
![email-4](https://github.com/bloodzer0/Enterprise_Security_Build--Open_Source/blob/master/Infrastructure%20Security/Office%20Security/Email%20Security/img/email-4.png)

## 防御建议

### 个人用户

1. 提高个人安全意识，收发邮件时确认收发来源是否可靠，不要随意点击或者复制邮件中的网址，不要轻易下载来源不明的附件，建议对陌生人邮件一律不打开。

1. 尽量不在非可控环境下登录电子邮件，如网吧的电脑、其他人的电脑等。

1. 确保邮件收发和登陆终端系统的环境安全（PC、手机、PAD等），及时升级更新和进行漏洞补丁修复，安装终端安全防护软件并及时升级打开监控，确保邮件收发的环境安全。

1. 邮箱密码必须使用强密码（例如：密码长度大于12位字符，且必须为数字、英文大小写字母、特殊字符组合），并定期更换密码；密码不得与其他服务混用。

1. 如使用邮件客户端，确保客户端安装程序的安全性，按照邮件服务器支持的加密链接方式（如SSL）配置邮件收发，而不要使用明文协议收发邮件；对邮件客户端数据文件所在卷，建议采用卷加密（如Bitlocker）。

1. 浏览器收发邮件时，需要使用HTTPS协议登陆信箱，而不要使用HTTP登陆。以防被嗅探窃取账户密码。

1. 按照组织规定规范进行邮件签名。

1. 邮箱地址不要随意传播，减少攻击者找到攻击入口的可能；必须公开邮件地址的，可以把@符号用其他符号替换，避免被爬虫爬取识别后，成为垃圾邮件和攻击邮件群发的目标。

### 企业用户

1. 配置安全管理和使用电子邮件策略：包括电子邮件权限、收发用户身份设置、电子邮件内容限制、电子邮件附件要求、邮件传输协议安全、异常邮件监控、用户备份和归档保存等，具体可参考《信息安全策略编制指南-L9电子邮件安全策略》 。

1. 保障邮件系统所在的网络安全：包括网络结构安全、入侵防范和安全审计等，可参考《可管理的网络计划V4.0（NSA/IAD）》。

1. 保障邮件系统软硬件安全：包括服务器、操作系统、数据库的安全防范策略，可参考 《DISA安全技术实施指南STIG》。

1. 确保邮件系统的物理和管理安全：包括访问控制、管理制度等，具体可参考 《YD/T 3161-2016邮件系统安全防护要求》。

## 参考链接

1. 收到“来自自己”的敲诈邮件，请不要惊慌

    <https://www.freebuf.com/articles/network/187522.html>

1. 钓鱼邮件初探：黑客是如何进行邮件伪造的

    <https://www.freebuf.com/sectool/92397.html> 

1. 常见的钓鱼邮件类型有哪些

   <https://service.alibaba.com/hc/supplier/detail/20141141.htm> 

2. 企业邮件安全防护经验总结 

   <https://www.freebuf.com/articles/security-management/127752.html> 

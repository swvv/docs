---
description: >-
  Surge for macOS 是目前 macOS 平台上实现了 NE 的成品客户端软件，虽然有大量其他软件也实现了 NE 支持，但其可能不支持 「厘米云」
  使用的协议或配置繁琐，功能不完整和存在稳定性问题。
---

# Surge 使用教程

{% hint style="info" %}
Surge for macOS 的授权是与 iOS 互不关联的，需要单独购买。
{% endhint %}

{% hint style="warning" %}
这是一个付费软件，如果您未订阅厘米云，则需要购买才能使用。
{% endhint %}

## 系统环境

> 在此文章撰写时…  
> macOS Mojave 10.14.6  
> Surge Mac 3.3.2 \(Build 915\)

## 下载安装

* 官方下载：[Surge Mac 3.2.1 \(Build 864\)](https://nssurge.com/mac/v3/Surge-latest.zip)
* 本站托管：[Surge Mac 3.2.1 \(Build 915\)](https://download.iplc.wiki/%E9%99%84%E4%BB%B6/wiki/macOS/Surge%203%202.zip)

> 推荐使用本站托管版本，官网版本下载安装后仍需更新版本
>
> `915` 与 `864` 最大区别在于 VMESS 协议的支持，如不使用本站版本可能无法下载包含 VMESS 协议的配置文件

{% hint style="danger" %}
如果你是用本站订阅则需选择企业授权激活，反则使用你购买时信息激活
{% endhint %}

## 获取订阅

{% hint style="info" %}
如果使用本站 Enterprise 订阅请跳过此步骤
{% endhint %}

* 在用户中心首页选择`Surge 托管配置` 之后点击 `复制 Surge 4 托管配置链接` 

![](../.gitbook/assets/20bc97b8-79a0-4d93-a419-d15b787b14d7.png)

* 在 Surge 面板切换到 `设置` 页面，点击`配置按钮` 

![](../.gitbook/assets/qq20191219-125757.png)

* 点击 `Install from URL...` ，在弹窗页面填入刚刚复制的地址

![](../.gitbook/assets/qq20191219-130029.png)

## 配置激活

右击菜单栏 Surge 图标，将光标移动到 `切换配置` 选择 `Enterprise Profile` 即可激活本站配置文件

![](../.gitbook/assets/72e646ea-c94b-48b2-9bfe-052ce36490a9.png)

{% hint style="warning" %}
如果你是用的自购买授权或许这里的配置文件名为 `IPLCM.conf`
{% endhint %}

## 节点选择

通过右击 Surge 菜单栏图标来快速的选择图标与您的出站方式

![](../.gitbook/assets/qq20191219-131556.png)

## 代理启用

在系统菜单栏中右击 Surge 图标，下滑找到 `设置为系统代理` ，并将其选中

![](../.gitbook/assets/qq20191219-131829.png)

{% hint style="warning" %}
此外，某些应用程序可能不遵循系统代理（如终端）。对于这部分应用程序，如果需要其流量通过 「厘米云」 网络，你需要打开 Surge 的「增强模式」。
{% endhint %}


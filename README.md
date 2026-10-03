# 远程遥控 Remote Control

手机远程控制电脑 App（对标向日葵核心功能），基于 VNC/RFB 3.8 协议自研 Android 客户端 + 电脑端 TightVNC 服务端，网络层走 **ZeroTier 私有内网**。

## 功能

- 实时查看电脑屏幕（4K 分辨率支持）
- 单指拖动 = 移动鼠标，轻点 = 左键单击
- 双指滑动 = 滚轮滚动
- 键盘输入（支持中文，逐字符发送）
- Esc / 回车 / 退格快捷键
- 连接信息本地记忆

## 使用前提（电脑端一次性配置）

1. 电脑安装 [TightVNC 2.8.85](https://www.tightvnc.com/download.php)（服务模式运行，端口 5900）
2. 电脑与手机加入同一 ZeroTier 网络
3. 防火墙仅放行 ZeroTier 网段访问 5900 端口（安全白名单）

## 下载

- [APK 直链（jsDelivr CDN）](https://cdn.jsdelivr.net/gh/tangjie11685-rgb/remote-control-update@main/apk/remote-control-v1.0.0.apk)
- [GitHub Release](https://github.com/tangjie11685-rgb/remote-control-update/releases)
- [Gitee 镜像仓库](https://gitee.com/the-plump-buddha/remote-control-update)

## 版本记录

- v1.0.0 首版发布

> 安全说明：连接全程走 ZeroTier 加密内网（10.90.0.0/16），电脑防火墙仅允许该网段访问 VNC 端口。

# roco-stream Android 下载

[**下载 v0.2.0 预览版 APK（约 38 MB）**](https://github.com/htan-cat/roco-stream-releases/releases/download/v0.2.0/roco-stream-0.2.0-preview.apk)

[查看下载页面、版本说明与校验文件](https://github.com/htan-cat/roco-stream-releases/releases/tag/v0.2.0)

支持 Android 8.0 及以上，arm64-v8a / x86_64。此版本是 debug 签名预览包，尚未完成手机实测。

## 使用方法

1. 安装后授予悬浮窗权限，点击「启动」。默认显示原始包，可按需开启内置解析引擎。
2. 首版需要独立 VPN 采集工具（如 PCAPdroid）：仅选择游戏应用并排除 roco-stream，使用 classic PCAP 的 UDP 导出，目标 `127.0.0.1:57012`，关闭 PCAPNG。
3. 先启动 roco-stream，再启动采集器，最后重新登录游戏。点击悬浮球展开列表。

当前未内置 VPNService；背包完整解析需要匹配版本的描述符，默认 APK 不附带第三方游戏素材。

## 检查更新

应用中的「公开版本信息 HTTPS 地址」填写：

```text
https://raw.githubusercontent.com/htan-cat/roco-stream-releases/main/version.json
```

本仓库只提供安装包、版本清单和使用说明，源码保存在独立私有仓库。APK 内含的依赖及代码许可见安装包中的 THIRD_PARTY_NOTICES.md。

# WiFi Radar 发布渠道

这里是 **WiFi Radar**（Android WiFi 扫描与分析工具）的 APK 发布仓库，只用于提供安装包下载和 App 内的版本检测，不包含源代码。

## 下载

前往 [Releases](https://github.com/Hhb97/WifiRadar-releases/releases/latest) 下载最新版本的 `WifiRadar-x.y.apk`。

App 启动时会自动检查这里的最新 Release（最多每 12 小时一次），也可以在 App 右上角菜单中手动「检查更新」。

## 安装说明

- 要求 Android 7.0 及以上
- 从浏览器下载后，按系统提示允许「安装未知应用」即可安装
- 部分机型（如小米 Android 17）在授予「附近的设备」权限后，还需要额外授予「精确位置」权限才能扫描，App 会引导操作

## 校验签名

所有正式版本使用同一个签名证书，可用以下指纹确认安装包来源：

```
SHA-256: bbb04d12ac8f17c69cae43f73cfe81b4735855ce803e0da53ec757752ef53cf6
```

校验方法（需要 Android SDK Build-Tools）：

```bash
apksigner verify --print-certs WifiRadar-x.y.apk
```

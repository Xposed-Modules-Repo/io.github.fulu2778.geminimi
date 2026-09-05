# Gemini For HyperOS4

在国行小米 HyperOS 4 / Android 15+ 上，把原本归超级小爱管的系统手势换成 Google：

- **长按电源键** → 唤起 **Gemini Overlay**
- **长按小白条** → 唤起 **Google Circle to Search（圈定即搜）**

基于 libxposed API 102（支持热重载），将 Google 保持为数字助理，并阻止 MIUI 恢复为内置超级小爱。

## 安装

1. 在本页 Release 下载并安装 APK（包名 `io.github.fulu2778.geminimi`）
2. LSPosed 中启用模块
3. 作用域勾选：`system`、`com.miui.voiceassist`、`com.google.android.googlequicksearchbox`
4. 重启设备

## 源码

见 `SOURCE_URL` 文件（GitHub: fulu2778/Gemini-For-HyperOS4）。

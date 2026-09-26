# 直予 / Zhiyu 0.1.0 安装

## 简体中文

版本 **0.1.0（build 13）**。从 [Release 附件](https://github.com/memade/zhiyu/releases/tag/v0.1.0)下载对应平台的安装包，核对 `SHA256SUMS`。GitHub 自动生成的 Source code ZIP/TAR 不是安装包。

- **Android 7.0+ / arm64**：安装 `Zhiyu-0.1.0-android-arm64.apk`，按系统提示允许当前下载器或文件管理器安装应用。APK 已使用发行密钥签名。遇到签名冲突时停止安装并反馈，保留已有 App 和数据。
- **macOS 13+ / Apple Silicon**：打开 `Zhiyu-0.1.0-macos-arm64.dmg`，将 `zhiyu.app` 复制到 Applications，弹出映像后启动。使用 Developer ID 签名，并通过 Apple 公证。若已有旧版，请先将旧 App 保留到单独目录，再复制本版，保留原应用数据。
- **Windows 11 / x64**：完整解压 `Zhiyu-0.1.0-windows-x64.zip` 到可写目录，运行 `product\zhiyu.exe`。保留同目录的 DLL、`data` 和许可文件；不要单独移动 EXE。此便携包未做 Authenticode 签名。

**从 RC2 更新：**Android 包名由 `com.skstu.sovkit`、macOS Bundle ID 由 `com.skstu.nearvia` 改为 `com.skstu.sovkit.zhiyu`。新旧 App 使用独立数据，不会自动迁移联系人、身份或历史记录。Windows 数据目录由 `%LOCALAPPDATA%\com.skstu.sovkit` 改为 `%LOCALAPPDATA%\com.skstu.sovkit.zhiyu`，同样不会自动读取或迁移旧目录。请保留旧 App、旧数据和重要文件原件；安装本版无需先卸载旧版。

iOS 不提供本次公开下载，App Store 上架准备中。

## 繁體中文

版本 **0.1.0（build 13）**。從 [Release 附件](https://github.com/memade/zhiyu/releases/tag/v0.1.0)下載對應平台的安裝包，核對 `SHA256SUMS`。GitHub 自動產生的 Source code ZIP/TAR 並非安裝包。

- **Android 7.0+ / arm64**：安裝 `Zhiyu-0.1.0-android-arm64.apk`，依系統提示允許目前的下載器或檔案管理器安裝應用程式。APK 已使用發行金鑰簽章。如遇簽章衝突，請停止安裝並回報，保留既有 App 與資料。
- **macOS 13+ / Apple Silicon**：開啟 `Zhiyu-0.1.0-macos-arm64.dmg`，將 `zhiyu.app` 複製到 Applications，退出映像後啟動。使用 Developer ID 簽章，並通過 Apple 公證。如已有舊版，請先將舊 App 保留到獨立目錄，再複製本版，保留原應用程式資料。
- **Windows 11 / x64**：完整解壓縮 `Zhiyu-0.1.0-windows-x64.zip` 至可寫入目錄，執行 `product\zhiyu.exe`。保留同目錄的 DLL、`data` 及授權檔案；勿單獨移動 EXE。此可攜式套件尚未做 Authenticode 簽章。

**從 RC2 更新：**Android 套件名稱由 `com.skstu.sovkit`、macOS Bundle ID 由 `com.skstu.nearvia` 改為 `com.skstu.sovkit.zhiyu`。新舊 App 使用獨立資料，不會自動移轉聯絡人、身分或歷史紀錄。Windows 資料目錄由 `%LOCALAPPDATA%\com.skstu.sovkit` 改為 `%LOCALAPPDATA%\com.skstu.sovkit.zhiyu`，同樣不會自動讀取或移轉舊目錄。請保留舊 App、舊資料與重要檔案原件；安裝本版無需先解除安裝舊版。

iOS 不提供本次公開下載，App Store 上架準備中。

## English

Version **0.1.0, build 13**. Download the package for your platform from the [release assets](https://github.com/memade/zhiyu/releases/tag/v0.1.0) and verify `SHA256SUMS`. GitHub's automatic source archives are not application packages.

- **Android 7.0+ / arm64**: install `Zhiyu-0.1.0-android-arm64.apk`. Follow the system prompt to allow installation from the downloader or file manager you are using. The APK is signed with the release key. If signatures conflict, stop and report the issue; retain the existing app and data.
- **macOS 13+ / Apple Silicon**: open `Zhiyu-0.1.0-macos-arm64.dmg`, copy `zhiyu.app` into Applications, eject the image, then launch the installed app. It is Developer ID signed and notarized by Apple. If an older app is present, preserve it in a separate directory before copying this version, and retain its data.
- **Windows 11 / x64**: extract the entire `Zhiyu-0.1.0-windows-x64.zip` into a writable directory and run `product\zhiyu.exe`. Keep the DLLs, `data` directory and license files together; do not move the EXE alone. This portable package is not Authenticode signed.

**Updating from RC2:** the Android package name changes from `com.skstu.sovkit`, and the macOS Bundle ID from `com.skstu.nearvia`, to `com.skstu.sovkit.zhiyu`. The old and new apps use separate data. Contacts, identities and history are not migrated automatically. The Windows data directory changes from `%LOCALAPPDATA%\com.skstu.sovkit` to `%LOCALAPPDATA%\com.skstu.sovkit.zhiyu`; the old directory is not read or migrated automatically. Retain the previous app, its data and important original files. You do not need to uninstall the previous version first.

No public iOS download is included. App Store submission is being prepared.

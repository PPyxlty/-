# 🔥 完全銷毀器（Secure Delete.app）

一鍵拖拉檔案或資料夾，安全覆寫後刪除，支援 macOS Automator App / shell 腳本。

## 🚀 功能特色

- 拖曳檔案或資料夾即可自動刪除
- 使用 `gshred` 覆寫刪除（無法回復）
- 資料夾遞迴處理
- 刪除前確認（避免誤刪）
- 執行完跳出 macOS 通知

## 📦 安裝方式

### 使用 `.app` 應用程式
1. 下載 拖拉到我身上直接完全移除.app.zip (https://github.com/PPyxlty/Secure-Delete.app/archive/refs/heads/main.zip) 並解壓縮
2. 拖曳檔案/資料夾進 App 圖示即可使用


## 🔧 相依工具

- macOS
- [Homebrew](https://brew.sh/)
- `coreutils`（安裝 `gshred` 用）
```bash
brew install coreutils

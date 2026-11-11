# 帳務工作台 2.0 安裝檔

帳務工作台 2.0（Windows x64）的安裝檔發行處。此 repo 只放 GitHub Release 的安裝檔與簽章發行資訊，原始碼保持私有。

- 到右側 **Releases** 下載最新版的 `AccountingWorkbench2-<版本>-win-x64-setup.exe`，不需要 GitHub 帳號。
- 已安裝的程式會自動檢查這裡的最新版本並提示更新。
- 每個 Release 附 `AccountingWorkbench2-<版本>-release.json`：內含安裝檔大小與 SHA-256，並以 Ed25519 簽章；程式更新前會驗證簽章與雜湊。
- 安裝檔目前沒有 Windows 發行者簽章，第一次執行時 Windows 可能顯示 SmartScreen 提醒。
- 新版使用新的版本標籤，不覆寫既有附件。

使用前需以 AI GO 帳號登入，帳務資料不在此 repo、也不在安裝檔內。

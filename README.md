# Artelu · 守林人的回聲

公開遊戲成品發布庫。私人遊戲原始碼不放在此處。

目前為 **大更新測試版本 · 第一版**，遊戲版本 `0.3.0-test.2`、啟動器版本 `1.1.0`。

## 下載及安裝

1. 從 [新版發布](https://github.com/MoriTeahouse/Artelu-Releases/releases/tag/v0.3.0-test.2) 下載 `Artelu-Launcher-1.1.0-win-x64.zip`。
2. 解開啟動器 ZIP，執行 `ArteluLauncher.exe`，選擇安裝硬碟／資料夾。
3. 按「下載並安裝」。啟動器下載 ATR，部署遊戲與 .NET 8、SDL2、OpenAL，短暫啟動遊戲檢查環境，然後啟用版本。
4. 按「開始遊戲」。存檔在所選目錄 `UserData/Saves`；更新保留存檔。

需要 Windows 64 位元與支援 OpenGL 的顯示卡驅動。啟動器與遊戲隨附 .NET，不需手動安裝開發工具。

也可下載官方 `.atr`，使用新版啟動器「安裝本機 ATR」。ATR 由 MatrixTea 引擎模組解封裝；一般 ZIP 工具無法直接開啟。引擎格式金鑰可被逆向，因此這是專用封裝，不是不可破解的 DRM。新版只發布遊戲 ATR；啟動器 1.0 需先升級到 1.1。舊遊戲 ZIP 版本仍保留。

![Artelu Launcher 1.1](https://github.com/MoriTeahouse/Artelu-Releases/releases/download/v0.3.0-test.2/launcher-atr.png)

## 版本內容

- 原創「森林之心」圖標，森林月光啟動器。
- ATR：適應式 Brotli／Deflate、AES-256-GCM 區塊驗證及整檔 SHA-256。
- 自動部署並驗證執行環境；失敗或取消不切換目前版本。
- 三層探索、生存製作、父親的日誌、雙結局、光照與音效。
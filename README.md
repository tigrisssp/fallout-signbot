# fallout-signbot (廢土自動/m簽到bot)

這是一個專為 Minecraft 伺服器 (McFallout) 設計的自動簽到機器人。支援多帳號與自動跳過已簽到目標。

## 主要功能

* **多帳號支援**：支援無限多組微軟帳號輪替執行，每組帳號擁有獨立的紀錄檔。
* **自動跳過**：每次執行前會比對 `history_{id}.txt`，今日已完成的目標自動跳過。
* **圖形化設定產生器**：附帶 `config_generator.html`，不用寫程式碼也能輕鬆產生設定檔。

## 安裝與使用

### 前置需求
1. **有手** (能操作滑鼠)
2. **有腦** (能閱讀文字)
3. (選用) 有 Minecraft 正版帳號

### 使用教學

不需要安裝任何程式語言環境，下載即用。

#### 步驟 1：下載檔案
請至 [Releases] 頁面下載以下兩個檔案，並放在 **同一個資料夾** 內：
* `fallout-signbot.exe` (主程式)
* `config_generator.html` (設定檔產生器)

#### 步驟 2：產生設定檔
1. 雙擊打開 `config_generator.html`。
2. 點擊 **+ 新增帳號**，填入您的 ID 與 Email。
3. 點擊 **+ 新增目標**，填入您想簽到的 Bot ID (例如 `orange_bank`)。
4. 設定完成後，點擊 **下載 config.json**。
5. **將下載的 `config.json` 放入跟 `fallout-signbot.exe` 同一個資料夾中。**

#### 步驟 3：啟動
雙擊 `fallout-signbot.exe` 即可開始簽到。
*(第一次執行時需要進行微軟登入驗證，請依照視窗指示操作)*

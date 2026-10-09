# 日日好 My Little Days V1.0

手機優先的療癒系個人生活行事曆。原生 HTML / CSS / JavaScript，無後端、無第三方依賴。

## 使用方式

本機測試：在此資料夾執行 `python3 -m http.server 8000`，開啟 `http://localhost:8000`。不要用 `file://` 測試 PWA。

## GitHub Pages 部署

1. 建立 GitHub 公開儲存庫（例如 `dailygood`）。
2. 將此資料夾全部檔案上傳到儲存庫根目錄。
3. 開啟 Settings → Pages → Build and deployment，選擇 Deploy from a branch，分支 main、資料夾 /(root)。
4. 等待部署完成，使用 `https://你的帳號.github.io/dailygood/` 開啟。
5. iPhone Safari 點「分享」→「加入主畫面」。

相對路徑已考慮 GitHub Pages 子路徑。

## 功能

- 今日首頁、完整月曆、日期選取及跨月
- 記事新增、修改、刪除、完成勾選、localStorage 保存
- 日期搜尋、日期間隔計算
- 原創雲朵角色、每日一句
- PWA 安裝圖示與離線核心頁面快取

## 限制與重要提醒

- **記事只存於目前瀏覽器**，清除網站資料或更換裝置會遺失；V1 沒有備份與同步。
- **節日資料為部分固定日期的常見節日，並非完整臺灣政府核定放假日資料**。尚未收錄農曆節日、年度補假及完整國定假日核定表；請參閱 https://www.dgpa.gov.tw/ 。未來年度假期不得視為已核定。
- PWA 需透過 HTTPS 或 localhost 使用，首次載入完成快取後才可離線開啟；瀏覽器仍可能清除快取或儲存資料。
- iOS/Android 真機安裝與離線使用尚需實際驗證。

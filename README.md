# Pendulum X / D-Cyber 中文攻略

以 DigiKidult 原始中文攻略的文字及圖片重新設計的靜態網站。提供數碼圖鑑、進化路線、操作玩法、道具、關卡掉落、爆裂進化、Acom 代碼及 FAQ。適合手機、平板與桌面使用。

## 發佈至 GitHub Pages

1. 把 ZIP 解壓縮。
2. 將 `index.html`、`base.css`、`style.css`、`app.js`、`data.js`、`icon.svg`、`.nojekyll` 及整個 `assets` 資料夾放到 GitHub 儲存庫根目錄。
3. 到儲存庫 **Settings → Pages**。
4. 選擇 **Deploy from a branch**，再選 `main`（或你的分支）及 **/ (root)**，按 **Save**。
5. 等 GitHub 完成發佈，使用 Pages 顯示的網址開啟。

網站使用相對路徑，可直接放在專案儲存庫，不需要修改網址前綴。不需要安裝套件、建置、帳號或 API 金鑰。在電腦開啟 `index.html` 亦可離線閱讀；本機環境的複製按鈕如被瀏覽器限制，可手動選取代碼複製。

## 來源及資料說明

- 正確來源：https://docs.google.com/spreadsheets/d/1ZIi86TmiiuklyCQPPm7tKIGlHsTN4kSi0gG0JSve-PY/edit
- 原作者：DigiKidult 被選中嘅大細路；特別鳴謝台灣社群協助校閱。
- 視覺參考：https://digikidult.github.io/Digimon-VER-WS/
- 擷取日期：2026-10-23。靜態資料快照，並非即時同步。原始試算表未經修改。
- 65 筆版本圖鑑、185 條進化路線、17 件道具、91 筆關卡敵人／掉落、17 組爆裂進化、68 筆 Acom 用途、11 篇玩法主題及 8 篇 FAQ。版本圖鑑包含同名數碼獸的不同版本；用途數包含共用代碼的多個結果。
- 數據使用 Google Sheets 顯示值，保留百分比、時間及區域標示。圖片來自同一份試算表的匯出檔。隱藏工作表不納入發佈內容。
- 欄位「—」或省略的空條件表示原表未列要求，並非獨立確認不需該條件。部分原表名稱及用字可能不一致，網站保留來源寫法，各卡片附原表定位連結。
- Digimon 角色及相關圖像版權屬原權利人。此為非官方粉絲攻略。

## 更新

可直接修改 `data.js` 的對應欄位更新文字、圖片及條件。`app.js` 管理分類、篩選、詳情及複製功能；兩個 CSS 檔案管理樣式。資料處理及驗證腳本保留於工作資料夾，沒有包含在發佈 ZIP 內。

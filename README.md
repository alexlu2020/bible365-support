# Bible365 支援網站

獨立的公開支援網站專案。只包含靜態 HTML、CSS 與公開 App 圖示，不包含 App 原始碼、使用者資料、帳號憑證或舊 Sites／Cloudflare 設定。

- 支援網站：https://alexlu2020.github.io/bible365-support/
- 隱私權政策：https://alexlu2020.github.io/bible365-support/privacy/
- 聯絡 Email：alexsystem995@gmail.com

## 部署

GitHub Pages 使用 `main` 分支的根目錄，保留 `.nojekyll`。編輯 HTML 或 CSS 後直接提交並 push 到 `main`，由 GitHub Pages 自動發布。不需要安裝套件或執行建置。

`index.html` 是支援首頁；`privacy/index.html` 是隱私權政策；`styles.css` 為共用樣式；`404.html` 為找不到頁面的導覽。

## 移轉範圍（2026-10-25）

隱私權政策內容來自既有網站，保留原生效日期 2026-07-25，僅更新站名顯示、站內導覽與經開發者授權公開的聯絡 Email。舊網站未停用，也未設定轉址。支援首頁補充現有 App 操作說明，樣式沿用原網站方向。

網站聯絡方式僅保留 Email；網站不再提供 GitHub 問題回報入口。這項變更未關閉儲存庫本身的問題回報功能。

## 隱私政策更新（2026-10-25）

經開發者確認後更新並取代原政策，生效日期為 2026-10-25。補充內容：

- 本機語言、字體、佈景偏好，以及 SQLite 收藏的實際欄位。
- JSON 匯出、匯入時的本機快取與系統檔案選擇／分享介面。
- 未加密的 JSON、外部接收方、系統備份及刪除 App 後仍可能存在的副本。
- 主動寄送支援郵件的內容、用途、以必要期間為原則的保存，以及查詢、更正、刪除請求入口。不承諾未確認的固定天數。
- GitHub Pages 的安全用途 IP 紀錄，以及 Gmail、Apple App Store、Google Play 的各自政策連結。

不宣稱開發者能遠端讀取本機收藏、提供自動雲端同步、保證安全抹除或保證商店審核通過。政策需隨實際功能與開發者支援處理方式持續維護。

本次沒有修改 App 內連結、App Store Connect、Google Play Console 或 DNS 設定。請將商店後台的支援與隱私網址改為上方新網址。若要將新網址加入 App，需另行修改與建置。

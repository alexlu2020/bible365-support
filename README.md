# Bible365 支援網站

獨立的公開支援網站專案。只包含靜態 HTML、CSS 與公開 App 圖示，不包含 App 原始碼、使用者資料、帳號憑證或舊 Sites／Cloudflare 設定。

- 支援網站：https://alexlu2020.github.io/bible365-support/
- 隱私權政策：https://alexlu2020.github.io/bible365-support/privacy/
- 聯絡 Email：alexsystem995@gmail.com
- 問題回報：https://github.com/alexlu2020/bible365-support/issues

## 部署

GitHub Pages 使用 `main` 分支的根目錄，保留 `.nojekyll`。編輯 HTML 或 CSS 後直接提交並 push 到 `main`，由 GitHub Pages 自動發布。不需要安裝套件或執行建置。

`index.html` 是支援首頁；`privacy/index.html` 是隱私權政策；`styles.css` 為共用樣式；`404.html` 為找不到頁面的導覽。

## 移轉範圍（2026-10-25）

隱私權政策內容來自既有網站，保留原生效日期 2026-07-25，僅更新站名顯示、站內導覽與經開發者授權公開的聯絡 Email／問題回報入口。舊網站未停用，也未設定轉址。支援首頁補充現有 App 操作說明，樣式沿用原網站方向。

原政策的本機儲存段落尚未描述後來新增的收藏資料庫、語言偏好、JSON 匯出／匯入，以及使用者自行分享或寄信時的資料處理。正式送審前應由開發者確認並另行更新政策內容；此次搬遷不擅自擴充法律或隱私承諾。

本次沒有修改 App 內連結、App Store Connect、Google Play Console 或 DNS 設定。請將商店後台的支援與隱私網址改為上方新網址。若要將新網址加入 App，需另行修改與建置。

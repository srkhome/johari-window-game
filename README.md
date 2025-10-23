# 元氣精神｜周哈里窗自我探索測驗（GitHub Pages 版）

這是一個單檔前端小工具（無後端），可直接部署到 **GitHub Pages** 使用。
功能：40 題量表、分頁作答、進度條、四象限分數、雷達圖（Chart.js）、結果匯出（PNG / PDF / JSON）。

## 一鍵上架到 GitHub Pages
1. 建立公開 Repo（例如 `johari-window-game`）。
2. 上傳本資料夾全部內容（至少包含 `index.html` 與 `assets/logo.svg`）。
3. 到 **Settings → Pages**：
   - Branch 選 `main`；
   - /root；
   - Save。
4. 之後以 `https://你的帳號.github.io/你的repo/` 造訪。

## 自訂
- 網站抬頭與品牌區位於 `index.html` 的 Topbar，Logo 使用 `assets/logo.svg`。
- 匯出檔名格式為 `元氣精神_周哈里窗_YYYYMMDD_HHMM`，可在 `filenameBase()` 調整。
- 若要改色系，調整 `:root` 內的 CSS 變數（--open、--hidden、--blind、--unknown、--brand 等）。

## 免責聲明
本工具僅供自我覺察與團隊對話，不做臨床診斷。

# Editing Rules & Workflow (HTML + SCSS + JS)

## 1) 專案目錄
- HTML：根目錄的 `*.html`
- SCSS：`assets/scss`（編譯輸出到 `assets/css/style.css`）
- JS：`assets/js`（入口 `assets/js/main.js`）
- 圖片：`assets/img`（不可異動檔名與路徑）
- 字型：`assets/fonts`

## 2) 編輯原則
- **只改被點名的檔案**，預設禁止跨頁大改。
- **HTML 只能在標記區塊編輯**：
  ```html
  <!-- CURSOR:BEGIN editable:hero -->
  ...這裡的內容允許調整/新增...
  <!-- CURSOR:END editable -->

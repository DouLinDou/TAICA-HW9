# GitHub Pages 部署資料夾

此資料夾是一份可獨立部署的靜態網站，入口為 `index.html`，本地圖片與 Kawaii AZKi 片頭音檔都在 `assets/`。

## 上傳方式

1. 建立一個 GitHub repository。
2. 將此資料夾中的**所有內容**（`index.html`、`assets/`、本說明檔）放到 repository 根目錄。
3. 在 repository 的 **Settings → Pages**，將發布來源設為 `Deploy from a branch`，選擇 `main` 分支與 `/(root)`，再儲存。
4. 等待 Pages 顯示網站網址後開啟。

不要只上傳 `index.html`；`assets/` 內包含頁面使用的圖片與 Kawaii AZKi 音檔。假名與詞彙真人錄音、授權頁和 Google 瀏覽器語音補讀需要網路連線。頁尾列出的 Wiki 依據名稱可供追溯，但完整 Wiki 檔案不在這個獨立部署資料夾中。

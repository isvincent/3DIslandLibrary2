# 閱讀之嶼｜可直接上傳的正式版

這份是已建置的靜態網站，根目錄有 index.html、assets/ 與 .nojekyll。
將此資料夾內全部內容上傳至 GitHub 儲存庫根目錄，Settings → Pages →
Deploy from a branch → main → /(root)，等待部署成功即可。
也可放在既有網站子資料夾，資源均使用相對路徑。

本機預覽（需要 Python）：在本資料夾執行 python -m http.server 8080，
開啟 http://localhost:8080/。不要使用 file:// 雙擊開啟。

如需編輯模型、文案或重建，請下載另一份 library-island-source.zip。
完整專案內含 ES Modules 來源、package-lock、測試與 GitHub Actions 設定。
本次沒有發布至您的 GitHub；實機觸控與 Safari／Firefox 尚未驗證。

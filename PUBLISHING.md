# v1.2.3 上架步驟

1. 將本原始碼套件的內容上傳到既有 GitHub 儲存庫根目錄，確認儲存庫公開。保留既有其他檔案；README、CHANGELOG、metadata.txt 及新的 icon.svg 應更新為此次內容，logoico.png 可移除。
2. 確認公開版本的 nlma_token_refresh/ 與發布 ZIP 完全一致。
3. 在 QGIS 官方平台 https://plugins.qgis.org/ 登入，以當前頁面提供的登入方式為準。
4. 開啟 https://plugins.qgis.org/plugins/nlma_token_refresh/ ，依平台指引上傳新版本 nlma_token_refresh-1.2.3.zip。
5. 處理平台驗證訊息並等待審核；已提交不代表已核准或公開。

版本設定 experimental=False、qgisMaximumVersion=4.99、supportsQt6=True；此標記不代表已通過官方審核。請勿在 GitHub 新增另一套不同授權；本次採 GPL-2.0-or-later，根目錄與外掛目錄皆附 LICENSE。

本外掛透過 Claude Code 製作。

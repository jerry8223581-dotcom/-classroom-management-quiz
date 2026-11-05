# 班級經營期中考複習網站

這是可直接上傳GitHub Pages的靜態發布版，沒有安裝或建置程序，也不需要後端、資料庫、登入、API金鑰或雲端服務。

## 功能

- 221道有效選擇題：隨機10題或全部題目，同次不重複。
- 答對顯示綠色提示，約0.8秒後自動換題；答錯顯示選錯選項及正確答案，等手動下一題。
- 顯示模式、進度、計分結果，可同模式重考或選擇其他模式。
- 錯題紀錄及未完成測驗保存在各自瀏覽器的localStorage，重新整理仍保留。
- 20道簡答題及AI精簡參考答案，同頁直接閱讀。第12題的理論分類範圍保留待確認註記。

## 檔案

```text
index.html
style.css
site.css
app.js
data.js
.nojekyll
.gitignore
README.md
```

前五個檔案是執行必要資源，請一起上傳，檔名大小寫不要改。網頁使用相對路徑與#頁面切換，可部署在任意儲存庫子目錄。本版沒有執行必需的圖片檔；原始PDF頁面截圖只供本機核對，不在發布版。

## GitHub Pages

1. 您自行建立或選擇儲存庫，將**本資料夾內的內容**放到儲存庫根目錄；不要只傳index.html，也不要把整個課程資料夾、Word、PDF、備份與audit一起上傳。
2. Settings → Pages → Build and deployment，Source選Deploy from a branch。
3. 選main（或實際分支）與/(root)，Save，等待部署完成。
4. 以Pages提供的HTTPS網址開啟，通常為https://帳號.github.io/儲存庫名稱/。
5. 用手機與電腦檢查兩種測驗、簡答題及重新整理後的紀錄保存。

官方說明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 學習紀錄與資料

每位使用者的紀錄只存在自己的瀏覽器，不會傳給網站作者或其他朋友。本機file://紀錄不會自動移轉到HTTPS網站；不同瀏覽器、裝置也不會自動同步。清除瀏覽器網站資料會清除紀錄。從未設定公開學生名冊或集中收件後端。

簡答題答案為AI整理之精簡參考答案，不是教師標準答案。原始題目與參考連結保持不變；外部參考連結僅供選擇性閱讀，不是網站載入依賴。

本資料夾不包含原始Word、PDF、掃描頁、私人檔案、本機磁碟路徑、測試腳本或測試截圖。.gitignore是防止誤加入的輔助措施；不要把密碼、金鑰或真實學生資料寫入HTML、JavaScript或題庫。

已完成本機GitHub Pages式子目錄測試；尚未建立GitHub儲存庫、推送或進行實際線上部署。正式網址仍需部署後確認。

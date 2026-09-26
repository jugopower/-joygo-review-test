Joy Go 棋譜解盤－GitHub / Render 測試版

【檔案】
index.html              主程式
sample-9x9.sgf          9路測試棋譜
sample-13x13.sgf        13路測試棋譜
sample-19x19.sgf        19路測試棋譜

【GitHub】
1. 新建一個 Repository，例如：joygo-review-test
2. 將本資料夾內 4 個檔案全部上傳到 Repository 根目錄
3. 確認 index.html 在最外層，不要再包一層資料夾

【Render】
1. 登入 Render
2. New → Static Site
3. 連接剛才的 GitHub Repository
4. Build Command：留空
5. Publish Directory：.
6. 建立網站
7. 等部署完成後，Render 會提供 https://xxxxx.onrender.com 網址

【iPad 測試】
1. 用 Safari 開啟 Render 的 https 網址
2. 畫面上方應顯示「系統：可載入 SGF」
3. 按「載入 SGF」
4. 選 sample-19x19.sgf（或你自己的棋譜）
5. 載入後應顯示檔名、19×19、總手數
6. 測試上一手、下一手、播放、暫停、播放秒數
7. 再測文字解說
8. 錄音時 Safari 會要求麥克風權限，請選「允許」

注意：
若畫面仍只顯示「系統：啟動中…」，表示 JavaScript 沒有執行成功。
正常 HTTPS Safari 頁面應顯示「系統：可載入 SGF」。

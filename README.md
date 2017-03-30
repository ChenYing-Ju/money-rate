## Function：
能快速觀察匯率變動，並且設定範圍值作為提醒
## Describtion：
##### 利用Node.js的功能(request、cheerio)抓取網頁之數值，再搭配nw.js可以做到用.exe的方式執行，所以目前的作法是將2個檔案(index.html+package.json)壓縮成.zip，並且拉向nw.exe執行。
##### 關於抓取特定網頁內容（網路爬蟲）的部分，是利用Chrome 按下 F12 後，點選左上角之箭頭，從網頁中的css部分找出關鍵code。
##### 程式碼完成後，也可以透過指令將檔案打包成.exe，但必須含在nw.js的資料夾下執行，方法如下：
 1. 打開cmd
 2. 使用cd指令，找到該文件的目錄下
 3. 輸入 copy /b nw.exe + x.zip y.exe  (x:打包的.zip檔名 y:.exe將要命名之檔名)

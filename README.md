## Function：
觀察匯率變動，能夠設定範圍值作為提醒
## Describtion：
##### 目前的作法是將2個檔案(index.html+package.json)打包成zip檔案，並且拉向nw.exe檔執行。
##### 也可以打包成exe檔，但必須含在nw的資料夾下執行，方法如下：
 1. 打開cmd
 2. 使用cd指令，找到該文件的目錄下
 3. 輸入 copy /b nw.exe+＊＊.nw ＃＃.exe
> ＊＊:打包的zip之檔名
> ＃＃:執行檔將要命名之檔名

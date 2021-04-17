# hw5：簡答題
1. 請解釋前端與後端的差異
前端 : 表面看的到的，ex 網頁畫面等等
後端 : 你看不到的，ex 資料庫等等

2. 假設我今天去 Google 首頁搜尋框打上：JavaScript 並且按下 Enter，請說出從這一刻開始到我看到搜尋結果為止發生在背後的事情。
a. 按下 Enter ， 會傳輸加密資料 "JavaScript"到 Google 的伺服器
b. 伺服器將收到的資料解密後，在 Google 已幫網頁建立好索引的資料庫裡找到和 "JavaSpript" 這個標籤有關的網址，回傳到電腦裡的 Google 瀏覽器
c. 瀏覽器再將資料解密成網頁懂的語言，將結果顯示出來。

3. 
find	在整個硬碟裡的資料搜尋，輸出其位置	find <file's name>
locate	在資料庫來搜尋，輸出其位置	locate <file's name>
clear	清空 CLI	clear 讓畫面 CLI 變乾淨
chmod	修改檔案權限	chmod 664 README.md修改檔案權限為 -rw-rw-r-- , r = 4, w = 2, x =1
cut	將一段訊息的某一段切出來	echo $PATH | cut -d ':' -f 5 印出 PATH 變數的第五個路徑

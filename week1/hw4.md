# hw4：跟你朋友介紹 Git
1. git init 	啟動版本控制	
vim. gitignore	忽略不要控制的檔案	
git add .	全部加入	把東西放入新資料夾(暫存的)
git commit -m "name"	建立版本	把資料夾改成版本流水號
加入後有新檔案記得再 add 並 commit		
git commit -am "name"	有更新後新版本建立	
git checkout "流水號"	回到特定版本	切換資料夾

2. branch 分支		
當要開發新功能，需開branch		
git branch "name"	開分支	
git checkout "branch name"	切換到分支開發	
git checkout "master"	切換回 master 準備合併	`
git merg "branch name"	合併動作	
若發生衝突，手動修改完後 commit		
完成		

3. github 使用		
push 上傳檔案		pull 下載檔案
於 github 建立新 repository		git pull origin "name"
git pull -u origin "name"	上傳版本至 github	
做修改或新增文件		
於 git-bash commit	commit 修改後的版本	
git pul -u origini "new name"	上傳新版本至 github	
github 進行 pull request		
通過後 merge ，之後刪掉 branch		

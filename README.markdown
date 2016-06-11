###git init
```
git init 一開始的初始化
```

### git add 
```
git add . 全部新增	
git add app/*	新增APP目錄底下
git add *.txt 新增附檔名為txt
git add -u	僅將「更新」或「刪除」的檔案變更寫入到「索引檔」中。
```

###git status
```
git status
git status -s	簡短說明
```

###git commit
```
git commit
git commit -m "版本紀錄的說明文字"
```    

###git log
```
git log				顯示log
git log -10		只顯示10筆log
```

###git rm
```
git rm 的指令執行的時候，會同時做兩件事：
刪除工作目錄快取的 'Gruntfile.js' 這個檔案 (用來標示這個刪除檔案的動作要列入版本控管)
刪除工作目錄下的 'Gruntfile.js' 這個實體檔案 (代表真的把這個實體檔案給刪除)

git rm filename 的時候，除了更新索引檔之外，連工作目錄下的檔案也會一併被刪除
git rm --cached a.txt 只想刪除索引檔中的該檔，又要保留工作目錄下的實體檔案
git rm '*.txt'  
git rm 'app/*.html'
```

###git mv
```
git mv 'oldname' 'newname'	將檔案更名
```

###git reset
```
git reset 重設一下工作目錄的索引狀態，例如add -A 之後，還原
git reset --hard 如果想把工作目錄也給還原到目前的最新版，一次把所有檔案都給還原了
git rm 刪除的目錄或檔案，還是用 git mv 更名的目錄或檔案，透過 git reset 都無法把「實體檔案」給救回來
！
```

###git checkout
```
git checkout master 'filename' 只還原一個檔案
```

###git gc
```
git gc	會自動執行重新封裝等動作，但你依然可以自行下達指令執行
```

###git fsck
```
git fsck	檢查 Git 維護的檔案系統是否完整
```

###git push
```
git push -u origin master 有更新的上傳到GitHub
```

###git branch
```
git branch  										 =>查看有哪些分支
git branch [branch_name]     		 =>建立分支，目前工作目錄維持在自己的分支
git checkout -b [branch_name]		 =>建立分支，將目前工作目錄切換到新的分支
git checkout [branch_name]			 =>切換當下的目錄到哪一個分支
git branch -d [branch_name]			 =>刪除一個分支，如果是當下的分支不可刪除
git log													 =>查看紀錄
```
使用SourceTree 工具可以用圖示，進一步了解分支架構，[使用方法](https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/docs/08%20%E9%97%9C%E6%96%BC%E5%88%86%E6%94%AF%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%80%E5%BF%B5%E8%88%87%E4%BD%BF%E7%94%A8%E6%96%B9%E5%BC%8F.markdown)。


###git diff 
```
git diff                 => 工作目錄 vs 索引
git diff HEAD            => 工作目錄 vs HEAD
git diff --cached HEAD   => 索引     vs HEAD
git diff --cached        => 索引     vs HEAD
git diff HEAD^ HEAD      => HEAD^   vs HEAD 比較【最新版的前一版】與【最新版】之間的差異
```
###git help 
```
詳細的指令與參數說明，可以輸入 git help reset 查詢完整的文件。
詳細的指令與參數說明，可以輸入 git help checkout 查詢完整的文件。
詳細的指令與參數說明，可以輸入 git help branch 查詢完整的文件。
```




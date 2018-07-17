### 今天是第一次在做git的多人開發

###### ps 自行增加的地方為 < > 這裡面，如果裡面有"" 就是要加上去。
---
1. 首先就是把資料給clone下來
``` sh
$git clone <"網址">
``` 

2. 進去資料夾裡面
``` sh
$cd <資料夾名稱>
``` 

3. 改正自己想改的東西....

4. 創立一個新的branch 
``` sh
$git branch <檔案名稱>
```

5. 切換目前branch 的地方
``` sh
$git checkout <branch名稱>
```  

6. 如果要查看的話下指令
###### 查看目前有的分之
``` sh
$git branch
``` 
###### 比較檔案的不同，有更改那些東西
``` sh
$git diff
``` 
###### 查看現在檔案的狀態，看那些沒有被追蹤
``` sh
$git statuas
``` 

7. 這邊先做一些設定，才能Commit上去。
###### 新增email
``` sh
$git config --global user.email <"email">
``` 
###### 新增uesr.name
``` sh
$git config --global user.name <"name">
``` 
###### 把編輯器改成vim比較熟悉
``` sh
$git config --global core.editor vim
```

8. 如果沒什麼問題就可以開始上傳了。

``` sh
$git commit <檔案名稱>
``` 
9. 之後就能上傳檔案了。
``` sh
$git push origin <分支名稱>
``` 

10. 接下來再到網站上面進行一些操作確認，進入編輯的網站後，就能按下畫面中的確認。
![](https://github.com/fogdingding/github/blob/master/img/git-push-網站點選按鈕.JPG)

11. 接下來新增一些註解，方便別人、日後查看
![](https://github.com/fogdingding/github/blob/master/img/git-push-新增註解.JPG)

12. 在畫面右手邊，之後就可以請別人進行查看、確認
![](https://github.com/fogdingding/github/blob/master/img/git-push-請別人觀看，確認.JPG)
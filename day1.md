# Day0
今天是第一天，所以並未學習特別困難的部分，主要就是裝裝環境，辦辦帳號，或是一些好用的套件。

1.[git](https://git-scm.com/)

2.[github](https://github.com/)

3.[VScode](https://code.visualstudio.com)

4.[Cmder](http://cmder.net/)

裝完即可開始主要的指令學習
-----
# 指令學習

在剛開始，需要的指令並不多，只需要幾個即可做完大部分的事情，如同80/20法則

1. git init 

>>>**告訴git，這邊有一個資料夾需要控管**

2. git add README.md

>>>**新增一個主要的說明文件(想要上傳的東西)。**

3. git commit -m "first commit"

>>>**建立一個分支存儲點，並描述為"______"**

4. git remote add origin ________

>>>**這邊告訴git目前我們要對誰做事情，在____補上 git@github.com:'User_name'/'Project_name'.git**

>>>**另外有時候會有無法上傳的問題，很可能是remote的部分出現問題**

>>>**請使用 [remote](https://help.github.com/articles/removing-a-remote/)相關資訊**

>>>**主要就是 git remote -v 、 git remote rm destination來做操作**

5. git push -u origin master

>>>**把剛剛建立好的分支，上傳至master。(只有這個才是真正的上傳到github哦)**
-------
# 指令解說

1. 在這個部分，首先是在命令提示字元(Terminal)的地方下達，以後也都是唷。 當然主要就是為了告訴git這邊有一個資料夾要做管理了哦。另一個部分就是會新增兩個檔案如圖所示 

![list-01](https://github.com/fogdingding/github/blob/master/img/list-01.JPG)

2. 這邊我們用一個譬喻的情境，來讓各位了解，什麼事github上傳時候的階段性。 首先假設我是一名小學生，我得 1.寫完作業，2.把作業放進書包，3.把書包繳給老師。三個階段，這個部分的時候屬於寫完作業了，並告訴我的電腦這件事情。(location 當然，這個階段可以隨時進行更正。)

3. 這個階段引用上點的情境譬喻，則為第二點，我把我剛剛宣告我寫完作業的部分，把牠們放進書包裡，準備要拿給老師。(location 當然，這個階段可以隨時進行更正。)

4. 這個部分，只是為了以防之前可能有做別的動作。

5. 這個階段，就是情境譬喻當中最為主要的部份了，就是把書包繳給老師(Cloud 這個階段就不能隨時進行更正了，必須從頭來過才行。)，如果他沒有問題，就會詢問你要上傳的地方的帳號密碼。在做輸入即可。

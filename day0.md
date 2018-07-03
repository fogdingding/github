#今天第一天，所以學習主要的 push pull即可。

以下指令建立在已經安裝好GIT環境。

git init 
//告訴git 這邊有一個資料夾需要控管
git add README.md
//新增一個主要的說明文件，並使用MD格式。
git commit -m "first commit"
//建立一個分支。
git remote add origin https://github.com/fogdingding/github.git
//這邊告訴目前我們要對什麼做事情
git push -u origin master
//把我現在寫好的東西，上傳上去。(只有這個才是上傳到雲端)
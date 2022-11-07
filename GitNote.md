# Git
+ git branch:查看本地有哪些分支
```bash
git branch -r
``` 
``` java
System.out.println
```
+ git init :初始化git功能 (always first step)
+ git add . :所有資料都要被git追蹤
+ git commit -m "test" : commit test(自行替換)
+ git status: 查看是否都有commit了，確定才能push
+ git push :上傳進度
+ git push -u origin Jean_dev :上傳進度到Jean_dev分支

+ git branch:查看本地有哪些分支
+ git checkout -b xxx分支名 :創建並同時切換分支
+ git branch xxx分支名 :創建分支
+ git checkout xxx分支名 :切換分支

+ git checkout 分支名稱:切換本地分支名稱
+ git branch -D develop:刪除develop分支


+ esc狂按 + :wq!可以跳出
+ q :離開


+ git pull origin YiJing_dev :從遠端拉某個分支到本地端(記得先切換到本地某個目標分支)
+ git log --graph:類似sourcetree頁面

+ git log --oneline :可以查看之前的紀錄修改那些東西
+ git log :可以查看修改的細節(時間、作者)
+ git checkout 某個hashcode :可以回到某個時間點
+ git push -f :強制push到remote (be careful他不會管是否同步)
+ git clone :
***pull=fetch(獲得遠端進度)+merge(將遠端跟本地端)

+ git fetch:獲得遠端進度
+ git fetch origin develop tab tab:獲得遠端origin的進度
+ git merge ajaxTest:若當前分支是Jean_dev，意思就是:把ajaxTest這個分支的進度merge到Jean_dev裡面，Jean_dev就是最新的版本 
+ git revert :取消merge
.

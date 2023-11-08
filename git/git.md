# Git

## Create
```bash
# create a new repository on the command line
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/<Username>/<Project_Name>.git
git push -u origin master

# push an existing repository from the command line
git remote add origin https://github.com/<Username>/<Project_Name>.git
git branch -M master
git push -u origin master
```

## Base
```bash
# 複製遠端的 Repository 檔案到本地端。
git clone <Repository URL>

# 檢查本地端檔案異動狀態。
git status

# 取消git add
git reset <File>
git reset
```

## Remote
```bash
# 列出當前專案中已設置的遠端專案
git remote

# 列出當前專案中已設置的遠端專案 並顯示url
git remote -v

# 新增一個新的遠端專案
git remote add <Remote_Name> <Remote_Url>

# 將以設置的遠端專案重新命名
git remote rename <Old_Name> <New_Name>

# 從當前專案中刪除指定的遠端專案
git remote remove <Remote_Name>

# 修改指定遠端專案的url
git remote set-url <Remote_Name> <New_Url>

# 顯示指定遠端專案的詳細訊息
git remote show <Remote_Name>
```

## config
```bash
# 顯示當前的git設定資訊
git config --list

# 編輯git設定檔 區域專案
git config -e

# 編輯git設定檔 全域專案
git config -e --global

# 設置提交時的使用者資訊
git config --global user.name "<Name>"
git config --global user.email <Email>
```

## Branch
```bash
# 創建分支
git branch <Branch_Name>

# 切換分支
git checkout <Branch_Name>

# 合併分支
git merge

# 列出分支
git branch

# 創建並切換該分支
git checkout -b <Branch_Name>

# 刪除分支
git branch -d <Branch_Name>
```

## Log
```bash
# 顯示歷史紀錄
git log

# 以列表形式顯示指定文件的歷史紀錄
git blame <File>

# 以單行顯示歷史紀錄
git log --oneline

# 顯示出現分支﹑合併時間點的歷史紀錄
git log --graph

# 逆向顯示歷史紀錄
git log --reverse

# 顯示指定用戶的歷史紀錄
git log --author=<Author>

# 指定日期 三周前且在11月1號之後提交
git log --before={3.weeks.ago} --after={2023-11-01}

# 隱藏合併提交
git log --no-merges
```

## Tag
```bash
test
```

# Git 學習檔案

這個檔案是為了學習如何在專案中使用 Git 而建立的。

## 常用 Git 指令

- `git status`：查看目前版本狀態
- `git add <檔案>`：將檔案加入暫存區
- `git commit -m "訊息"`：提交變更
- `git log`：查看提交紀錄
- `git diff`：查看尚未暫存的變更
- `git branch`：顯示所有分支
- `git checkout <分支或檔案>`：切換分支或還原檔案
- `git merge <分支>`：合併指定分支到目前分支
- `git pull`：從遠端取得並合併最新版本
- `git push`：將本地提交推送到遠端
- `git clone <網址>`：複製遠端專案到本地
- `git remote -v`：顯示遠端倉庫資訊
- `git reset --hard <commit>`：重設到指定提交（會丟失變更，請小心使用）
- `git remote set-url origin <新網址>`：重新設定遠端專案（origin）的網址
- `git stash`：暫存目前未提交的變更
- `git stash pop`：還原最近一次暫存的變更
- `git fetch`：從遠端取得最新資料但不合併
- `git cherry-pick <commit>`：套用指定的 commit 到目前分支
- `git rm <檔案>`：從版本控制中移除檔案
- `git mv <舊檔案> <新檔案>`：重新命名檔案
- `git tag <標籤名稱>`：建立標籤
- `git show <commit 或 tag>`：顯示指定提交或標籤的詳細資訊

祝你學習愉快！
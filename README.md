# Git-Github
## Git 基礎 <br />
(第一次使用要用git config 初始幾個設定，設定帳號、密碼) <br />
- **git init**: 資料檔案初始化成為git repository <br />
- **git add [file name] / git add .**  : 將文件新增到git <br />
- **git commit –m “[messages]”**: 保存進度加上備註訊息 <br />
- **git status**: 查看檔案目前狀態 (顯示跟上次commit不同的地方modified或 untracked)
- **git log / git log --online**: 查看commit紀錄 / 簡化版 <br />
- **git reset -- [file name]**: 取消已經add的檔案 <br />
- **git commit -- amend –m “[messages]”**: 修改最後一次commit紀錄 <br />
- **git checkout <commit id> --[file name]**: 還原檔案先前的版本 (需要add 跟 commit 代表不會刪除原先紀錄) <br />
- **git reset --hard [commit id]**: 還原到過去版本(不可逆的版本還原) <br />
- **新增.gitignore 檔案**: 避免無關的檔案混入 <br />
## Github操作 <br />
- **git remote add origin https://...** : 連接本地和遠端的儲存庫 <br />
- **git branch –M main** <br />
- **git push –u origin main**: 把本地位於main分支的資料推送到遠端 <br />

- **git clone <website url>**: clone專案到自己的本地 <br />
- **git push origin[remote name] main[branch name]**: 推本地端branch到遠端 <br />
- **git pull origin[remote name] main[remote branch name]**: 抓取最新的更新並直接合併到目前所在分支 <br />
- **git checkout –b [new branch name]**: 在本地端新增新的分支(之後再push origin newbranch name即可) <br />

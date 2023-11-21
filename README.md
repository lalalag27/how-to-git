# git 基本操作

1.git init  在 Workspace 創建 .git 目錄
2.git add  建立索引
3.git commit 至本地資料庫 (Local Repository)
4.git push 至 GitHub 資料庫 (Remote Repository)

＃ 步驟：
創建目錄
```
git init
```
將工作區內所有檔案鍵入索引
```
git add .
```
將索引檔案加入本工作區暫存
```
git commit -m "要上傳的名稱"
```
設置遠端GitHub儲存庫
```
git remote add origin 在github複製的專案https
```
原本設置的分支為master,要改成main
```
git checkout -b main
```
建立分支
```
git branch
```
將與github線上的歷史紀錄一起合併（第一次一定要確實核對是否有合併）
```
git pull --allow-unreleated-histories
```
將自有更新的檔案上傳到github
```
git push -u origin main
```


＃ 更新檔案後上傳
將工作區內所有檔案鍵入索引
```
git add .
```
將索引檔案加入指定github路徑
```
git commit -m "要上傳的名稱"
```
原本設置的分支為master,要改成main
```
git checkout -b main
```


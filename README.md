# Git

### 创建GitHub Repository 

### clone Repository 到本地

```powershell
git clone https://github.com/lin-bobo/test.git
```

### 提交到本地

```powershell
git commit
```

- 添加新文件

  ```powershell
  git add *  # 添加全部文件
  git add filename  # 添加某个文件
  ```

### 提交到GitHub

```powershell
git push
```

- 查看用户

  ```powershell
  git config --list
  ```

- 查看跟踪状态

  ```powershell
  git status
  ```

  

### 合作开发

- 解决冲突

  ```powershell
  git pull  # 拉取远程合并
  # 再次提交
  git add file
  git commit
  git push
  ```

- 回到过去

  ```powershell
  # 查看提交记录
  git log  # commit xxx
  # 修改指针，退回之前版本
  git reset --hard xxx
  # 查看各个版本
  git reflog  
  ```

  

### 建立里程碑

GitHub新建release


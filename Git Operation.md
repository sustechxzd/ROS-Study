## Git 操作

---

1. 初始化本地仓库

   1. 进入项目目录 

      ```bash
      cd D:\Repo
      ```

   2. 初始化 Git 仓库

      ```bash
      git init
      ```

2. 配置用户信息（提交身份）

   ```bash
   # 只针对当前仓库设置（如果全局权限有问题）
   git config user.name "sustechxzd"
   git config user.email "youremail@example.com"
   
   # 查看当前仓库配置
   git config --list
   ```

3. 查看仓库状态

   ```bash
   git status
   ```

4. 添加文件到暂存区

   ```bash
   # 添加当前目录下的所有文件
   git add .
   
   # 或者只添加指定文件
   git add README.md
   ```

5. 提交到本地仓库

   ```bash
   git commit -m "Initial commit: add project files"
   ```

   

6. 查看提交历史

   ```bash
   git log
   ```

6. 远程仓库操作

   1. 添加远程仓库

      ```bash
      git remote add origin https://github.com/yourusername/ROS-Study.git
      ```

      解释：把远程仓库 URL 命名为 `origin`（默认别名）。

   2. 查看远程仓库

      ```bash
      git remote -v
      ```

      解释：显示远程仓库 URL，用于 fetch/push。

7. 推送到远程仓库

   ```bash
   # 首次推送，设置 upstream
   git push -u origin main
   
   # 后续推送
   git push
   ```

   解释：把本地 `main` 分支提交推送到远程仓库 `origin`。`-u` 表示设置默认 upstream，以后可以直接用 `git push`

8. 推送到远程仓库

   ```bash
   # 首次推送，设置 upstream
   git push -u origin main
   
   # 后续推送
   git push
   ```

   解释：把本地 `main` 分支提交推送到远程仓库 `origin`。`-u` 表示设置默认 upstream，以后可以直接用 `git push`。

9. 拉取远程更新

   ```bash
   git pull
   ```








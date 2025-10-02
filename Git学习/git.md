# 1. 在 GitHub 上创建仓库

- 打开 GitHub → Create repository

# 2. 本地操作流程

## 1. 初始化仓库（第一步）

git init

## 2. 配置用户信息（使用您 GitHub 的信息）

git config --global user.email "your-real-email@gmail.com"
git config --global user.name "Your-GitHub-Username"

## 3. 添加文件到暂存区

git add .

## 4. 提交更改

git commit -m "initial commit"

## 5. 添加远程仓库（使用您自己复制的 GitHub 仓库 URL）

git remote add origin https://github.com/your-username/your-repo-name.git

## 6. 推送到远程仓库

git push origin main

## 7. 验证远程仓库

git remote -v

# Resource
My Resourse

这里是我的资源库，包含网页中的资源


<h1 align="center">🚧 Project 404</h1>
<p align="center"><i>“Not Found? Not a problem.”</i></p>

---

## 🧑‍🤝‍🧑 协作开发规范

本项目由两人协作开发。我们使用 Git + GitHub 进行版本控制和协作开发，遵循以下流程确保开发过程高效、有序、无冲突。

---

## 🔄 协作流程步骤
git clone到本地

### 🥽 1. 获取主分支最新代码

```bash
git checkout main
git pull origin main
```
### 🌱 2. 创建并切换到功能分支

```bash
git checkout -b feature/你的名字-任务名
```
### 🛠 3. 编码
编码之后，如果对方更新了其中的文件，需要合并检查之后再推送
```bash
***编码***
```
### 🚧 Step 3.5合并主分支并检查 + 提交更改
```bash
# 确保当前在你的 feature 分支
git checkout feature/你的名字-功能名

# 拉取最新主分支
git fetch origin
git merge origin/main
```
有冲突手动解决，修改后执行：
```bash
git add .
git commit -m "简要描述本次修改"
```

### ☁️ 4. 推送分支到 GitHub
```bash
git push origin feature/你的名字-任务名
```
### 5. 发起 Pull Request（PR）
打开 GitHub → 仓库页面 → 点击 “Compare & pull request”
填写功能描述、提交 PR
由另一位成员 Review / 合并（或根据约定直接合并）

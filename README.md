# 社团招新智能匹配平台

一个基于Vue.js 3开发的大学社团招新智能匹配平台。

## 功能特点

- **100个社团数据**：涵盖学术科技、文化艺术、体育运动、志愿服务等10个类别
- **多维度筛选**：支持按类型、活跃度、规模搜索
- **智能匹配算法**：基于用户兴趣和特长推荐最适合的Top 3社团
- **一键报名**：简化社团报名流程

## 本地运行

直接用浏览器打开 `index.html` 文件即可。

## 部署到 GitHub Pages

### 方式一：手动部署

1. 在GitHub上创建新仓库（如 `club-matching-platform`）
2. 将本项目文件推送到仓库
3. 进入仓库 Settings → Pages
4. 在 Source 中选择 "Deploy from a branch"
5. Branch 选择 "main"，目录选择 "/ (root)"
6. 点击 Save，等待部署完成

### 方式二：自动部署（推荐）

1. 推送代码到GitHub仓库后会自动触发部署
2. 访问 `https://你的用户名.github.io/仓库名/`

### 部署步骤详解

```bash
# 1. 初始化Git仓库
git init

# 2. 添加所有文件
git add .

# 3. 提交代码
git commit -m "Initial commit"

# 4. 创建main分支
git branch -M main

# 5. 添加远程仓库（替换为你的仓库URL）
git remote add origin https://github.com/你的用户名/club-matching-platform.git

# 6. 推送到GitHub
git push -u origin main
```

推送完成后，进入GitHub仓库的 **Settings → Pages**，确认Source设置为 "Deploy from a branch" 的 "main" 分支。

## 使用说明

1. **社团天地**：浏览所有社团，使用筛选功能查找
2. **我的匹配**：填写个人信息，系统自动推荐Top 3社团
3. **一键报名**：点击即可完成报名

## 技术栈

- Vue.js 3 (CDN)
- 原生HTML/CSS/JavaScript
- 无需构建工具，纯静态部署

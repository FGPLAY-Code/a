# 教育初心 - 体育老师专访网页

## 项目简介
这是一个展示体育老师张老师专访内容的静态网页，采用现代化的设计风格，具有动态渐变蓝绿背景和优雅的动画效果。

## 特性
- 🎨 动态渐变背景效果
- 📱 响应式设计，支持移动端
- ✨ 流畅的动画和交互效果
- 🌐 已配置GitHub Pages自动部署

## 文件结构
```
├── index.html          # 主页面文件
├── _config.yml         # GitHub Pages配置文件
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions部署配置
├── README.md           # 项目说明文档
└── 新闻稿.txt.txt     # 原始新闻稿内容
```

## 部署到GitHub Pages步骤

### 1. 创建GitHub仓库
1. 登录GitHub
2. 创建一个新的公开仓库，命名为 `news-interview`（或你喜欢的名字）
3. 不要勾选 "Initialize this repository with a README"

### 2. 上传文件到仓库
```bash
# 在本地项目目录中执行
git init
git add .
git commit -m "Initial commit: 体育老师专访网页"
git branch -M main
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```

### 3. 启用GitHub Pages
1. 进入仓库的 Settings 页面
2. 滚动到 Pages 部分
3. 在 "Source" 中选择 "GitHub Actions"
4. 保存设置

### 4. 访问网站
部署完成后，你的网站将可通过以下地址访问：
`https://你的用户名.github.io/你的仓库名/`

## 自定义配置
- 修改 `index.html` 中的内容
- 调整 `_config.yml` 中的网站标题和描述
- 自定义CSS样式和动画效果

## 技术栈
- HTML5
- CSS3 (动画、渐变、响应式)
- GitHub Actions (CI/CD)
- GitHub Pages (托管)

## 许可证
MIT License
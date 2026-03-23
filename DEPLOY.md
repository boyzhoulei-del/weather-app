# 天气网站部署方案

## 推荐方案排序

### 1️⃣ **Vercel**（⭐ 最推荐）
- **优点**：完全免费、自动部署、国内访问快、支持自定义域名
- **缺点**：需要 GitHub 账号
- **步骤**：
  1. 上传代码到 GitHub
  2. 在 Vercel 连接 GitHub repo
  3. 自动部署，获得公网 URL

### 2️⃣ **Netlify**
- **优点**：免费、部署快、支持自定义域名
- **缺点**：国内访问可能有延迟
- **步骤**：同 Vercel

### 3️⃣ **GitHub Pages**
- **优点**：完全免费、稳定
- **缺点**：需要 GitHub、国内访问慢
- **URL 格式**：`username.github.io/weather-app`

### 4️⃣ **Cloudflare Pages**
- **优点**：免费、CDN 加速、国内访问快
- **缺点**：需要 Cloudflare 账号
- **步骤**：连接 GitHub 自动部署

### 5️⃣ **Railway / Render**
- **优点**：免费额度充足
- **缺点**：需要信用卡验证

---

## 快速部署（推荐 Vercel）

### 第一步：上传到 GitHub

```bash
# 1. 初始化 git
cd ~/.qclaw/workspace/weather-app
git init
git add .
git commit -m "Initial weather app"

# 2. 创建 GitHub repo（网页操作）
# 访问 https://github.com/new
# 创建 repo 名称：weather-app

# 3. 推送代码
git remote add origin https://github.com/YOUR_USERNAME/weather-app.git
git branch -M main
git push -u origin main
```

### 第二步：在 Vercel 部署

1. 访问 https://vercel.com
2. 用 GitHub 账号登录
3. 点 "Import Project"
4. 选择 `weather-app` repo
5. 点 "Deploy"
6. 等待 ~1 分钟，获得公网 URL

**完成！** 你会得到类似这样的 URL：
```
https://weather-app-xxx.vercel.app
```

---

## 需要帮助吗？

我可以帮你：
- ✅ 生成 GitHub 部署脚本
- ✅ 配置自定义域名
- ✅ 设置自动更新
- ✅ 添加 SSL 证书

告诉我你选哪个方案！

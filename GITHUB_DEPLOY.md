# 🚀 GitHub + Vercel 部署指南

## 第一步：创建 GitHub 仓库

1. 打开 https://github.com/new
2. 填写信息：
   - **Repository name**: `weather-app`
   - **Description**: 杭州天气预报网站
   - **Public** 选项选中
   - 其他保持默认
3. 点 "Create repository"

## 第二步：推送代码到 GitHub

复制下面的命令，在终端运行：

```bash
cd ~/.qclaw/workspace/weather-app

# 添加远程仓库
git remote add origin https://github.com/boyzhoulei-del/weather-app.git

# 推送代码
git branch -M main
git push -u origin main
```

**第一次推送时会要求输入 GitHub 账号密码**

如果提示需要 Personal Access Token：
1. 访问 https://github.com/settings/tokens
2. 点 "Generate new token (classic)"
3. 勾选 `repo` 权限
4. 生成 token
5. 复制 token 作为密码粘贴

## 第三步：部署到 Vercel

1. 打开 https://vercel.com/new
2. 用 GitHub 账号登录
3. 点 "Import Project"
4. 在搜索框输入 `weather-app`
5. 选择你的仓库
6. 点 "Import"
7. 保持默认设置，点 "Deploy"
8. 等待 1-2 分钟...

## 完成！🎉

部署完成后，你会看到一个公网 URL，类似：
```
https://weather-app-xxx.vercel.app
```

这就是你的天气网站！可以分享给任何人访问。

---

## 后续更新

以后如果要更新网站：
1. 修改 `index.html`
2. 运行：
```bash
cd ~/.qclaw/workspace/weather-app
git add .
git commit -m "Update weather app"
git push
```
3. Vercel 会自动重新部署

---

## 需要帮助？

有问题随时问我！

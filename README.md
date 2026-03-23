# 杭州天气预报网站

一个美观的实时天气预报网站，显示杭州的当前天气、一周预报、月度总览和空气质量数据。

## 功能特性

- 🌡️ 实时天气数据（温度、湿度、风速、气压等）
- 🌧️ 一周天气预报
- 📊 月度天气总览
- 💨 实时空气质量指数（AQI）
- 🎨 现代化毛玻璃设计
- 📱 完全响应式布局
- ⚡ 每次打开自动更新数据

## 数据来源

- **天气数据**：wttr.in
- **空气质量**：waqi.info

## 技术栈

- HTML5
- CSS3（Grid、Flexbox、动画）
- Vanilla JavaScript（无框架依赖）

## 快速开始

1. 克隆仓库
```bash
git clone https://github.com/boyzhoulei-del/weather-app.git
cd weather-app
```

2. 用浏览器打开 `index.html`
```bash
open index.html
```

3. 或者用本地服务器
```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 部署

### Vercel（推荐）
1. 访问 https://vercel.com
2. 用 GitHub 账号登录
3. 点 "Import Project"
4. 选择此仓库
5. 点 "Deploy"

### Netlify
1. 访问 https://netlify.com
2. 连接 GitHub
3. 选择此仓库
4. 自动部署

## 自定义

编辑 `index.html` 中的以下部分：

- 城市名称：搜索 "杭州" 替换为你的城市
- 坐标：修改 "120.17°" 和 "30.25°"
- 颜色主题：修改 CSS 变量 `--accent-cyan` 等

## 许可证

MIT

## 作者

Created with ❤️ by QClaw

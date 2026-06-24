# 景观行业 AI 日报 — 静态部署

## 文件说明
- `index.html` — 入口页（自动跳转最新日报）
- `landscape-ai-daily-YYYY-MM-DD.html` — 每日日报

## 本地预览
直接用浏览器打开 `index.html` 即可。

## 部署到 Vercel
```bash
# 安装 Vercel CLI
npm install -g vercel

# 登录（首次需要）
vercel login

# 部署
cd D:/landscape-daily-site
vercel --prod
```

部署成功后，Vercel 会给你一个固定链接，如：
`https://landscape-ai-daily.vercel.app`

## 更新日报
1. 把新生成的 `landscape-ai-daily-YYYY-MM-DD.html` 复制到本目录
2. 修改 `index.html` 中的默认日期
3. 重新部署：`vercel --prod`

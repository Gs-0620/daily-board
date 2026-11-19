# daily-board

- `index.html` — 孕产时间线 · 温馨版（主页面，含「现场记一笔」面板）
- `classic.html` — 孕产时间线 · 原版（米纸红章风）
- `board.html` — 每日信息板（数据在 `data.json`）
- `app.json` — 页面「现场记一笔」的数据文件（账单 + 心情，浏览器提交自动写入）

用法：打开公网页面 → 展开「✍️ 现场记一笔」→ 首次把 GitHub 令牌粘入（只存本机浏览器）→ 填账单/心情提交，约 1 分钟后全站自动更新。访客无令牌时只读。

推送到 `main` 分支后自动发布到 GitHub Pages。

公网地址：<https://gs-0620.github.io/daily-board/>

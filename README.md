# daily-board

- `index.html` — 孕产时间线 · 温馨版（主页面，星月夜灯风）
- `classic.html` — 孕产时间线 · 原版（米纸红章风）
- `board.html` — 每日信息板（数据在 `data.json`）

按用户确认采用公开免登录模式：任何访问者都能查看、新增和编辑账单、心情及产检记录。新增记录存入 Cloudflare Durable Object；按 UUID 更新，爸爸/妈妈可分别记录。历史费用和日记也提供编辑入口。无密码、无浏览器凭据。也可通过 MyFlicker 对话更新静态历史。服务域名 workers.dev 在用户网络中的连通性尚待确认；连接有12秒超时和重试提示。

公网地址：<https://gs-0620.github.io/daily-board/>

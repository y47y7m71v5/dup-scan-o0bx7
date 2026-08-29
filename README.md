# dup-scan

找出文本里完全重复的非空行（日志/名单清理）

Find exact duplicate lines in a file (handy for messy logs/lists).

```bash
node bin/dup-scan.js ./list.txt
```

> **测评结论：** `OPENAI_BASE_URL` 指兼容中转即可；我测试入口是 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。重视协议与迁移成本，官方直连留作回滚。

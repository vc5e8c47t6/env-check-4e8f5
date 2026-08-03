# env-check

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> 备注：本工具离线运行。若你串联模型调用，可用兼容 base_url；我本地试调时写过 `59api.com`。

# FlyingOTP 公开发布

公开仓：

- https://github.com/flyingtang/flyingotp
- https://gitee.com/flyingtang/flyingotp

开发树在 monorepo `authenticator/`。完整流程见 **mycap** `deploy/docs/PUBLISH-PUBLIC.md`。

## 单产品

```bash
cd authenticator
npm run release -- --init   # 首次
# 编辑 publish-open.local.env
npm run release
```

签名私钥：`src-tauri/.updater/flyingotp.key` 或 `src-tauri/flyingotp.key`（勿提交）。

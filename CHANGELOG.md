# CHANGELOG.md · 仓库级变更

## 仓库 · 2026-11-17 · 接入单项目规范机器层

- 接入 knowledge-base 的**单项目规范**（spec 2.1.3 / repo-kit 2.7.2，profile `link-only`）
- 新增 `schema/taxonomy.json`、`tools/repo-kit/`、`tools/update-repo-kit.ps1`、`schema/kit.lock.json` 与 CI
- 只查链接与入口（link-only）：本仓是索引表（22 个外链、0 个相对链接），没有内容页可套契约
- 验收：`REPO CHECK: PASS`（ERROR=0）、`KIT LOCK: PASS (v2.7.2, spec=2.1.3)`

- 本次不改任何内容页；索引表与插件文档原样保留

## 仓库 · 2026-10-09 · 建库

### 建库

- 建立索引仓库（纯文档、零代码），收录下列项目：
- 收录：Android 应用、微信小程序、手机 Web 应用
- 🔒 私有仓库在索引中标注、不提供对外链接


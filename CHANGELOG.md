# CHANGELOG.md · 仓库级变更

## 仓库 · 2026-11-19 · 升级 repo-kit 2.9.0

- kit 2.7.2 → **2.9.0**；`schema/kit.lock.json` 重写（`spec_version` 2.1.3 → **2.1.4**）
- 新增能力：`AGENTS_TOO_LONG`（`AGENTS.md` > 150 行报 ERROR）。本仓 `AGENTS.md` 现 22 行，升级当天零拦截
- 2.8.1 起 `check_spec` 只比主/次版本，补丁差异（2.1.3↔2.1.4）不再报错
- `schema/taxonomy.json` 的 `version` 同步为 2.9.0（避免 `skew: taxonomy-vs-lock`）；
  仓库自有配置（`include` / `frontmatter_exempt` / `generated_files`）**未改**
- 验收：`REPO CHECK: PASS`、`KIT LOCK: PASS (v2.9.0, spec=2.1.4)`

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


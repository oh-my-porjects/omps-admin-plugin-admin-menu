# admin-menu 退役约束

本仓库是已退役的 V1-V3 项目后台模块，不是可部署插件。

- 不得恢复 `plugin.yaml`、Go 插件入口、`AdminWebHint`、`admin-web.yaml`、菜单聚合或旧 Spec 存储接口。
- 不得把本仓库加入公共模块注册表、项目环境引用或 runtime 插件加载列表。
- V4 项目后台的唯一链路是模块 `admin-intents.yaml` + 已验证 `api-docs/` + admin-server V4 编译发布 + runtime `/admin/_meta/ui-v4/*`。
- 需要扩展后台能力时，修改真实业务或公共模块的 API 契约和 `admin-intents.yaml`，不要在此创建兼容层。

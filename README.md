# admin-menu 已退役

`admin-menu` 是 V1-V3 项目后台用于菜单和 Spec 存储的历史公共模块，已被彻底移除。

- V4 菜单由已发布的 `admin-ui-v4` 完整发布集直接生成。
- V4 Spec 由 `admin-intents.yaml`、已验证 `api-docs/` 和项目意图确定性编译。
- runtime 只接收 `/admin/_meta/ui-v4/specs/bundle` 的完整替换发布，不加载本仓库，也不读取历史菜单或 Spec。
- admin-server 启动和数据库迁移都会删除 `admin-menu` 的公共模块注册和项目引用。

本仓库仅保留为已退役模块的历史 Git 身份，不再包含可部署插件、接口、页面配置或测试用例。不得重新添加 `plugin.yaml`、`AdminWebHint`、`admin-web.yaml` 或任何 V1-V3 运行协议。

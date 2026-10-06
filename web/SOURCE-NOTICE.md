# 迁移来源

`data/catalog.json` 的世界内容和说明来自本机 `astrbot_plugin_fishing` 仓库的 `core/initial_data.py`、称号补充迁移与三个成就定义文件。导出器位于 `tools/export_catalog.py`，来源文件 SHA-256 和内容数量见 `data/manifest.json`。

目标的钓鱼、精炼、库存、水族箱、道具、商店、奖池、成就、税务、交易所与单人小游戏规则根据源 `core/services` 和配置默认值适配为 GDScript。逐项来源、目标入口、行为差异与排除项见 `docs/migration-coverage.md`。目标保留源 AGPL-3.0 许可要求，不将规则迁移声明为无来源的独立实现。

源仓库提供 GNU Affero General Public License v3；原文保存在 `SOURCE-LICENSE-AGPL-3.0.txt`。此来源声明不替代其许可条款。目标项目的既有 `godot_ai` 插件使用自身许可证。

迁移的玩法、适配差异和完成状态见 `docs/migration-plan.md`。未复制第三方社区美术素材。

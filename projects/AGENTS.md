# AGENTS.md

## 目录结构

```text
projects/
├── AGENTS.md
├── WORKSPACE_INITIALIZATION.md
├── template/
└── workspaces/
```

## 直接子项

### `WORKSPACE_INITIALIZATION.md`

- **职责**：管理从 `template/` 创建 `workspaces/` 实例，以及恢复实例和接入实际项目仓库的流程。
- **读取条件**：需要创建或恢复 `workspaces/` 实例，或为实例接入实际项目仓库时读取。

### `template/`

- **职责**：提供 `workspaces/` 实例共用的管理结构和局部规则，不包含具体项目信息。

### `workspaces/`

- **职责**：承载各具体项目独立使用的管理实例。

## Git 管理边界

- **工作台 Git**：管理工作台框架、通用规则、用户画像和 `template/`，不管理 `workspaces/` 实例。
- **工作区 Git**：`workspaces/` 实例由 `template/` 创建；每个实例使用独立 Git 管理项目背景、状态、任务、日志和复盘，不管理其 `repository/` 中的实际项目内容。
- **项目仓库 Git**：管理各实例 `repository/` 中的实际项目内容和版本历史。

三类 Git 仓库彼此独立；执行 Git 操作时，应先确认当前操作属于哪一层仓库。

# AGENTS.md

## 目录结构

```text
rules/
├── AGENTS.md
├── MEMORY_PROTOCOL.md
├── CHANGE_PROTOCOL.md
└── FRAMEWORK_EVOLUTION.md
```

## 直接子项

### `MEMORY_PROTOCOL.md`

- **职责**：管理工作台中需要跨会话保留的信息的识别、归属、确认、记录和整理机制。
- **读取条件**：默认读取。

### `CHANGE_PROTOCOL.md`

- **职责**：定义文档、代码及其他项目文件共同遵守的修改与落盘规则。
- **读取条件**：需要新建、修改、移动或删除文档、代码及其他项目文件时读取。

### `FRAMEWORK_EVOLUTION.md`

- **职责**：管理框架所处阶段，以及框架设计、调整和阶段更新时适用的演进约束。
- **读取条件**：涉及框架自身的结构、职责、规则、工作流或模板机制设计与修改，或需要更新框架阶段时读取。

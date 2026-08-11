# AGENTS.md

## 目录结构

```text
tasks/
├── AGENTS.md
├── RULES.md
├── monthly/
│   ├── TEMPLATE.md
│   └── <YYYY-MM>.md
├── weekly/
│   ├── TEMPLATE.md
│   └── <YYYY-MM-Wnn>.md
└── daily/
    ├── TEMPLATE.md
    └── <YYYY-MM-DD>.md
```

## 直接子项

### `RULES.md`

- **职责**：定义 Agent 在当前项目中协助用户制定、推进和维护计划与任务时共同遵守的规则。
- **读取条件**：默认读取。

### `monthly/`

- **职责**：按月份承载月度计划。

### `weekly/`

- **职责**：按周承载周计划。

### `daily/`

- **职责**：按日期承载日计划和具体任务。

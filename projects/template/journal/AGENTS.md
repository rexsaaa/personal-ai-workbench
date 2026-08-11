# AGENTS.md

## 目录结构

```text
journal/
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

- **职责**：定义 Agent 在当前项目中协助用户记录执行情况、开展复盘和维护记录时共同遵守的规则。
- **读取条件**：默认读取。

### `monthly/`

- **职责**：按月份承载月度执行总结与复盘。

### `weekly/`

- **职责**：按周承载周执行总结与复盘。

### `daily/`

- **职责**：按日期承载每日执行记录与复盘。

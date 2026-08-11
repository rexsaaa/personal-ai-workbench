# AGENTS.md

## 目录结构

```text
profile/
├── AGENTS.md
├── PROFILE.md
├── COLLABORATION.md
├── PROFILE_INITIALIZATION.md
├── PROFILE_RULES.md
└── insights/
```

## 直接子项

### `PROFILE.md`

- **职责**：作为当前用户跨项目画像的权威快照，集中呈现当前背景、长期方向、能力、资源、持续约束和自我认知，供用户自我回顾和 Agent 开展协作时参考。
- **读取条件**：默认读取。

### `COLLABORATION.md`

- **职责**：作为当前用户协作规则的权威快照，集中呈现 Agent 在协作中应遵循的当前有效偏好和约定。
- **读取条件**：默认读取。

### `PROFILE_INITIALIZATION.md`

- **职责**：管理当前用户画像和协作规则的首次初始化流程，并为必要的章节复核提供引导。
- **读取条件**：发现 `PROFILE.md` 或 `COLLABORATION.md` 存在“待初始化”标记，或用户明确要求复核相关章节时读取。

### `PROFILE_RULES.md`

- **职责**：定义 `profile/` 内容在写入和维护时应如何提炼、表达并保持一致。
- **读取条件**：候选信息确定进入 `profile/`，或需要维护 `profile/` 现有内容时读取。

### `insights/`

- **职责**：承载当前用户在实践和思考中形成、具有跨项目参考价值的经验、认知与个人洞察。
- **读取条件**：任务需要参考、记录或维护相关经验、认知与个人洞察时读取。

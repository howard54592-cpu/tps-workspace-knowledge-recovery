# TPS Workspace Knowledge Recovery

工作区知识库迭代辅助技能。负责持续优化工作区配置、更新核心知识。

## 功能模块

### 1. 资料索引构建
- 扫描 memory/ 文件夹中的日志
- 自动提炼关键事件生成索引
- 维护团队成员信息

### 2. 搜索渠道管理
- 监控各渠道成功率
- 动态调整权重
- 支持增删搜索渠道
- **配置**: [references/channels.md](references/channels.md)

### 3. Skill 说明更新
- 定时/事件触发配置
- 团队配置动态调整
- 关键字库管理
- **配置**: [references/keywords.md](references/keywords.md)

### 4. 版本管理
- 记录版本变更历史
- 一键切换版本
- 版本对比功能
- **配置**: [references/versions.md](references/versions.md)

## 引用配置文件

| 配置文件 | 用途 |
|----------|------|
| [references/channels.md](references/channels.md) | 搜索渠道及权重配置 |
| [references/keywords.md](references/keywords.md) | 团队关键字及配置 |
| [references/versions.md](references/versions.md) | 版本历史及切换 |

## 文件结构
```
skill-name/
├── SKILL.md
├── assets/          # 生成的索引文件
├── references/     # ⬆️ 配置文件（被SKILL.md引用）
└── scripts/       # 迭代脚本
```

## 版本
- v1.0.0 (2026-03-19): 初始版本

# SKILLBOT Skills · 10 份可落地能力包

SKILLBOT 的 10 个板块方法论，每份 `SKILL.md` 都遵循同一结构：**何时使用 / 工作流 / 质量检查 / 输出格式**。配套的可视化演示见 [skillbot-showcase](https://github.com/lifterz/skillbot-showcase)。

## 能力包一览

| 能力包 | 一句话 | 适用场景 |
|--------|--------|---------|
| `plan-grill` | 一句话想法 → 五轮追问 → 可执行需求卡 | 需求只有一两句话时 |
| `ui-craft` | 简报 → 有意图的界面 → 规范自检三道门 | 任何"用户看得见的界面" |
| `video-studio` | 一句话 → 分镜 → 三轨时间线 → 成片 | 宣传片 / 产品视频 |
| `media-forge` | 描述 → 提示词工程 → 生成队列 → 资产库 | 配图 / 封面 / 素材 |
| `browser-agent` | 任务结构化 → 真实浏览器分步执行 → 留痕交付 | 查价 / 填表 / 监控 |
| `code-review` | Diff → 五轴扫描 → 分级问题 → 修复补丁 | 合并前检查 |
| `bug-hunter` | 取证 → 假设树 → 排除法 → 根因 → 回归 | 偶发 / 疑难故障 |
| `task-splitter` | 大目标 → 依赖图 → 工单 → 关键路径 | 项目启动与排期 |
| `growth-miner` | 社区扫描 → 意图匹配 → 价值优先回复 | 冷启动 / 找种子用户 |
| `teach-anything` | 类比 → 图示 → 实操 → 测验 | 讲透任何概念 |

## 使用方式

把任意能力包目录放进你的 Agent 技能目录（如 `~/.agent/skills/`），Agent 会按 `SKILL.md` 的 frontmatter `description` 自动匹配触发。

## 设计约定

- 每份方法论都带**可检查的质量清单**，不是空洞口号
- 强调"可证伪、可验证、有数字"：假设要能被证伪、Bug 修复要带复现测试、指标要有具体数值
- 演示页 = 方法论的舞台化呈现，两者一一对应

## License

MIT © SKILLBOT

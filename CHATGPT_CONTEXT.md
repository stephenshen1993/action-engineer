# AI 协作者启动入口

## 作用

这是 Action Engineer 项目的本地 AI 协作者导航页。

不要一次读取整个仓库。根据当前任务加载必要文件。

## 项目一句话定位

记录一名传统工程师在 AI 时代，如何从“长期准备、追求正确、出售时间”，逐渐走向“真实行动、AI 协作、构建长期资产”。

## 文件职责

| 文件 | 唯一职责 |
| --- | --- |
| `PROJECT_CONTEXT.md` | 稳定背景：作者、定位、读者和长期方向 |
| `CURRENT_STATUS.md` | 动态状态：当前阶段、重点和下一步 |
| `workflow/README.md` | 日常创作、发布和归档流程 |
| `workflow/writing_guide.md` | 表达风格及详细规则入口 |
| `content/published/INDEX.md` | 已发布内容地图 |
| `TODO.md` | 当前待办 |
| `logs/project_log.md` | 按时间追加的简单复盘 |
| `CHATGPT_PROJECT_BRIEF.md` | 上传给 ChatGPT Project 的独立精简包 |

## 按任务读取

| 任务 | 读取文件 |
| --- | --- |
| 深聊、选题、内容推演 | `PROJECT_CONTEXT.md`、`CURRENT_STATUS.md` |
| 写文章、改文章 | 额外读取 `workflow/writing_guide.md` |
| 开始一篇新文章 | 使用 `workflow/templates/article_creation_card.md` |
| 发布前 Review | 使用 `workflow/article_review_prompt.md` |
| 回顾历史内容、避免重复 | 额外读取 `content/published/INDEX.md` |
| 归档新文章 | 额外读取 `workflow/README.md` 和归档模板 |

## 协作分工

| 角色 | 职责 |
| --- | --- |
| 用户 | 提供真实经历、判断、情绪和最终决策 |
| ChatGPT | 深聊、挖掘核心矛盾、输出可发布文章 |
| Codex | 维护文件、归档内容、更新索引和上下文 |

## 协作底线

- 不编造经历、数据、感受或反馈。
- 缺少事实时，先向用户确认。
- 不为了完善系统偏离正在进行的创作。
- 当前阶段不主动引入复杂自动化、Agent 或内容矩阵。

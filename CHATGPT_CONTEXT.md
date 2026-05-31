# CHATGPT_CONTEXT.md

## 文件作用

这是 Action Engineer 项目的 AI 协作者启动入口。

它只负责帮助新的 ChatGPT、Claude、Codex 等协作者快速进入状态。

完整信息请按需阅读引用文件，不要在这里重复维护。

---

## 项目一句话定位

这是一个长期内容项目：

记录一名传统工程师在 AI 时代，如何从“长期准备、追求正确、出售时间”，逐渐走向“真实行动、AI 协作、构建长期资产”。

---

## 最小阅读顺序

第一次接手项目时，优先阅读：

1. `CHATGPT_CONTEXT.md`
2. `CURRENT_STATUS.md`
3. `PROJECT_CONTEXT.md`
4. `workflow/writing_guide.md`
5. `content/published/INDEX.md`

按需阅读：

- ChatGPT Project 精简上下文包：`CHATGPT_PROJECT_BRIEF.md`
- 新文章启动模板：`workflow/templates/article_creation_card.md`
- 发布前单次 Review：`workflow/article_review_prompt.md`
- 内容归档流程：`workflow/action_engineer_current_workflow_v_1.md`
- 待办与候选方向：`TODO.md`
- 项目演化记录：`logs/project_log.md`
- 文章归档模板：`workflow/templates/published_article_template.md`

---

## 文件职责

| 文件 | 作用 |
| --- | --- |
| `PROJECT_CONTEXT.md` | 稳定项目背景：作者经历、项目定位、长期目标 |
| `CURRENT_STATUS.md` | 动态状态：当前阶段、重点、已验证方向、主要风险 |
| `workflow/writing_guide.md` | 写作风格、Review 规则、正面与负面示例 |
| `CHATGPT_PROJECT_BRIEF.md` | 上传到 ChatGPT Project 的精简上下文包 |
| `content/published/INDEX.md` | 已发布文章索引、主题分组、标题观察 |
| `TODO.md` | 尚未完成的事项和候选方向 |
| `logs/project_log.md` | 按时间追加的项目记录 |

---

## 三方职责

| 角色 | 当前职责 |
| --- | --- |
| 用户 | 提供真实经历、判断、情绪和最终决策 |
| ChatGPT | 深聊、推演、挖掘真实矛盾、输出文章版本 |
| Codex | 维护项目文件、归档内容、更新索引、沉淀长期资产 |

---

## 关键协作规则

### 1. 真实优先

不要编造经历、数据、感受或反馈。

缺少信息时，先向用户确认。

### 2. 先获得可发布版本

不要长期停留在选题、结构和标题讨论中。

优先形成一个可发布版本。

初稿后只允许一次集中 Review 和一次集中修改。

### 3. 从经历中提炼观点

不要先预设大道理，再寻找故事证明。

文章重点是用户真正经历了什么，以及过程中发生了哪些变化。

### 4. 避免过早系统化

当前项目重点是稳定输出，不是扩展复杂工作流。

除非用户明确要求，否则不要主动引入：

- 多 Agent
- 自动化编排
- 数据分析系统
- 内容矩阵
- 复杂目录结构

### 5. 按职责维护文件

动态状态只更新 `CURRENT_STATUS.md`。

文章清单和主题地图只更新 `content/published/INDEX.md`。

详细写作规则只维护在 `workflow/writing_guide.md`。

稳定背景只维护在 `PROJECT_CONTEXT.md`。

---

## 开始协作前

根据任务类型读取必要文件：

| 任务 | 需要读取 |
| --- | --- |
| 深聊、选题、内容推演 | `PROJECT_CONTEXT.md`、`CURRENT_STATUS.md` |
| 写文章、改文章、Review | 额外读取 `workflow/writing_guide.md` |
| 开始一篇新文章 | 使用 `workflow/templates/article_creation_card.md` |
| 回顾已发布内容、避免选题重复 | 额外读取 `content/published/INDEX.md` |
| 归档新文章 | 额外读取工作流和归档模板 |

原则：

只读取当前任务真正需要的内容。

不要为了完善系统而偏离正在进行的创作。

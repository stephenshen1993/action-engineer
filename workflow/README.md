# Workflow 文档说明

这里存放创作工作流相关文档。

## 文档职责

| 文件 | 职责 | 使用时机 |
| --- | --- | --- |
| `CHATGPT_SESSION_START.md` | ChatGPT 网页版新会话启动流程、追问提示词和交接格式 | 每次在 ChatGPT 网页版开新创作会话时 |
| `CREATION_GUIDE.md` | 日常创作、正文结构、Review 和停止条件 | 每次开始写文章时 |
| `VISUAL_GUIDE.md` | 封面、头图、插图和配乐规则 | 需要制作视觉素材或选配乐时 |
| `LESSONS_LEARNED.md` | 从单篇创作中沉淀出的长期经验 | 遇到相似问题，需要回查历史经验时 |
| `templates/published_article.md` | 已发布文章归档模板 | Codex 归档文章时 |

## 读取顺序

日常创作默认读取：

1. `PROJECT_CONTEXT.md`
2. `CURRENT_STATUS.md`
3. `workflow/CREATION_GUIDE.md`

如果是在 ChatGPT 网页版开启新会话，先按：

4. `workflow/CHATGPT_SESSION_START.md`

执行启动流程。

只有在需要视觉决策时，再读取：

5. `workflow/VISUAL_GUIDE.md`

只有在需要避免重复、查找历史经验或做阶段复盘时，再读取：

6. `workflow/LESSONS_LEARNED.md`

不要每次都把所有文档塞进上下文。

## 更新规则

- 新增日常创作规则：更新 `CREATION_GUIDE.md`
- 新增 ChatGPT 网页版启动或交接规则：更新 `CHATGPT_SESSION_START.md`
- 新增视觉或配乐规则：更新 `VISUAL_GUIDE.md`
- 新增单篇创作复盘：更新 `LESSONS_LEARNED.md`
- 新增项目阶段记录：更新 `logs/project_log.md`

如果一条经验只对某一篇文章有效，不要写进指南。

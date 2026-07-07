# 行动工程师（Action Engineer）

这是 Action Engineer 项目的入口。

项目定位见：`PROJECT_CONTEXT.md`。

这个仓库只做三件事：

1. 保存项目长期上下文。
2. 归档已发布内容和素材。
3. 沉淀创作方法和阶段记录。

## 从哪里开始

| 需求 | 入口 |
| --- | --- |
| 了解项目定位 | [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md) |
| 查看当前阶段和下一步 | [CURRENT_STATUS.md](CURRENT_STATUS.md) |
| 了解创作工作流文档怎么用 | [workflow/README.md](workflow/README.md) |
| 启动 ChatGPT 网页版新会话 | [workflow/CHATGPT_SESSION_START.md](workflow/CHATGPT_SESSION_START.md) |
| 开始创作或让 ChatGPT 接手 | [workflow/CREATION_GUIDE.md](workflow/CREATION_GUIDE.md) |
| 查看创作复盘和方法论沉淀 | [workflow/LESSONS_LEARNED.md](workflow/LESSONS_LEARNED.md) |
| 制作封面、头图或插图 | [workflow/VISUAL_GUIDE.md](workflow/VISUAL_GUIDE.md) |
| 了解内容资产如何归档 | [content/README.md](content/README.md) |
| 回看已发布内容 | [content/published/INDEX.md](content/published/INDEX.md) |
| 查看项目演化记录 | [logs/project_log.md](logs/project_log.md) |

## 给 ChatGPT 的上下文

创作时直接提供源文件，不单独维护 ChatGPT 专属副本：

1. `PROJECT_CONTEXT.md`
2. `CURRENT_STATUS.md`
3. `workflow/CREATION_GUIDE.md`

需要回顾历史内容、避免重复或制作视觉素材时，再按需补充：

4. `content/published/INDEX.md`
5. `workflow/VISUAL_GUIDE.md`
6. `workflow/LESSONS_LEARNED.md`

日常创作不要默认全文塞入所有文档，优先控制上下文负担。

## 仓库结构

```text
README.md                 # 仓库入口和文档导航
PROJECT_CONTEXT.md        # 长期稳定定位
CURRENT_STATUS.md         # 当前动态状态

content/
  README.md               # 内容资产归档规则
  ideas/                  # 尚未进入创作阶段的真实现场
  published/              # 已发布文章与内容地图
  assets/published/       # 已发布文章使用的图片

workflow/
  README.md               # 工作流文档职责和读取顺序
  CHATGPT_SESSION_START.md # ChatGPT 网页版新会话启动流程
  CREATION_GUIDE.md       # 创作协作、表达规则、Review 和停止条件
  VISUAL_GUIDE.md         # 封面、头图和插图规则
  LESSONS_LEARNED.md      # 历史复盘和长期经验
  templates/

logs/
  project_log.md          # 项目里程碑和维护记录
```

## 文档职责

| 文件 | 放什么 | 不放什么 |
| --- | --- | --- |
| `PROJECT_CONTEXT.md` | 长期定位、作者背景、叙事主线 | 发布数量、短期目标、近期复盘 |
| `CURRENT_STATUS.md` | 当前阶段、下一步动作、当下提醒 | 长期方法论、历史记录 |
| `workflow/CHATGPT_SESSION_START.md` | ChatGPT 网页版新会话启动方式、追问流程、交接格式 | 正文写作规则、历史复盘 |
| `workflow/CREATION_GUIDE.md` | 日常创作和 Review 规则 | 单篇完整复盘 |
| `workflow/VISUAL_GUIDE.md` | 封面、头图、插图、配乐规则 | 正文写作规则 |
| `workflow/LESSONS_LEARNED.md` | 可复用创作经验和单篇复盘沉淀 | 项目流水账 |
| `content/published/INDEX.md` | 已发布内容地图和主题索引 | 文章全文和过程素材 |
| `logs/project_log.md` | 项目阶段变化、归档记录、维护记录 | 可沉淀到指南里的方法论全文 |

## 维护边界

1. 不为未来可能发生的复杂需求提前设计系统。
2. 不把过程素材长期堆进仓库。
3. 不把所有经验都塞进日常创作上下文。
4. 新经验先判断归属：规则进 `workflow`，资产进 `content`，阶段变化进 `logs`。
5. 当前阶段优先控制单篇创作耗时，达到发布标准后及时停止优化。

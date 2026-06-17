# 行动工程师（Action Engineer）

这是 Action Engineer 项目的入口。

项目定位见：`PROJECT_CONTEXT.md`。

## 从哪里开始

| 需求 | 入口 |
| --- | --- |
| 了解项目定位 | [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md) |
| 查看当前阶段和下一步 | [CURRENT_STATUS.md](CURRENT_STATUS.md) |
| 开始创作或让 ChatGPT 接手 | [workflow/CREATION_GUIDE.md](workflow/CREATION_GUIDE.md) |
| 查看创作复盘和方法论沉淀 | [workflow/LESSONS_LEARNED.md](workflow/LESSONS_LEARNED.md) |
| 制作封面、头图或插图 | [workflow/VISUAL_GUIDE.md](workflow/VISUAL_GUIDE.md) |
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
content/
  ideas/                  # 尚未进入创作阶段的真实现场
  published/              # 已发布文章与内容地图
  assets/published/       # 已发布文章使用的图片

workflow/
  CREATION_GUIDE.md       # 创作协作、表达规则、Review 和停止条件
  VISUAL_GUIDE.md         # 封面、头图和插图规则
  templates/

logs/
  project_log.md          # 简单复盘记录
```

## 维护原则

1. 稳定背景只更新 `PROJECT_CONTEXT.md`。
2. 动态状态只更新 `CURRENT_STATUS.md`。
3. 已发布内容只归档到 `content/published/` 和 `content/assets/published/`。
4. 创作规则只更新 `workflow/CREATION_GUIDE.md`。
5. 创作复盘和长期经验只更新 `workflow/LESSONS_LEARNED.md`。
6. 当前阶段优先控制单篇创作耗时，达到发布标准后及时停止优化。
7. 素材只保留实际发布版本，过程封面、头图和插图默认不归档。

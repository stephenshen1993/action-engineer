# Action Engineer 日常工作流

## 目标

稳定发布真实经历型抖音长文。

当前重点不是搭建复杂内容系统，而是降低创作阻力，让文章在达到可发布状态后及时停止修改。

## 每日流程

```text
记录真实现场
    ↓
填写单篇创作卡
    ↓
ChatGPT 深聊并形成可发布初稿
    ↓
执行一次阻塞项 Review
    ↓
集中修改一次
    ↓
发布
    ↓
Codex 归档文章、素材和索引
    ↓
简单记录当天结果
```

## 1. 记录灵感

现实中遇到值得写的瞬间时，先记录，不急着分析。

位置：

```text
content/ideas/
```

只需要写下：

- 发生了什么
- 哪个瞬间让你停了一下
- 当时最真实的感受
- 可能存在的矛盾

## 2. 开始创作

使用：

```text
workflow/templates/article_creation_card.md
```

只提供：

- 真实现场
- 核心矛盾
- 最想表达的一句话
- 必须保留的细节
- 需要规避的隐私风险

不要长时间讨论选题和结构。优先在 30 分钟内形成一个可发布初稿。

## 3. 单次 Review

使用：

```text
workflow/article_review_prompt.md
```

正文只执行一次集中 Review，只拦截：

1. 事实错误。
2. 隐私、客户或同事关系风险。
3. 普通读者无法理解的明显歧义。
4. 正文偏离本篇核心矛盾。

Review 后只集中修改一次。

“还能更顺”“还能更有情绪”“可能略有 AI 味”“标题也许还有更优解”不阻塞当天发布。

## 4. 时间盒

单篇文章总耗时上限为 90 分钟：

```text
5 分钟：填写单篇创作卡
30 分钟：ChatGPT 深聊并形成可发布初稿
15 分钟：执行一次阻塞项 Review
20 分钟：集中修改一次
5 分钟：从最多 3 个标题中选择 1 个
10 分钟：交给 Codex 归档
5 分钟：预留缓冲
```

## 5. 发布后归档

Codex 负责：

1. 在 `content/published/` 新增文章归档。
2. 将实际使用的图片放入 `content/assets/published/<文章文件名>/`。
3. 更新 `content/published/INDEX.md`。
4. 按需更新 `CURRENT_STATUS.md`。
5. 将简单复盘追加到 `logs/project_log.md`。

归档模板：

```text
workflow/templates/published_article_template.md
```

## 6. ChatGPT Project 上下文

日常创作使用：

```text
CHATGPT_PROJECT_BRIEF.md
```

由 Codex 在每周复盘或内容方向明显变化时更新。不要每天维护上下文包。

## 当前不要做

- 自动化编排
- 多 Agent
- RAG 或向量数据库
- 数据看板
- 多平台内容矩阵
- 复杂版本管理

当前真正主线只有一句话：

> 持续记录一个真实工程师的变化过程。

# Superlinear Advisor

> A source-grounded Q&A assistant for Lizheng's (Sean Yuzheng / 立正) public content.

**Skill author:** [wyuebei-cloud](https://github.com/wyuebei-cloud) · **Corpus source:** [sunyuzheng/lizheng-open-context](https://github.com/sunyuzheng/lizheng-open-context) (CC-BY-4.0)

---

## What is this?

Superlinear Advisor is a Hermes Agent skill that retrieves and synthesizes answers from Lizheng's verifiable public materials — Knowledge Bank articles, YouTube video transcripts, community posts, and *Zhenbenshi* (真本事) book frameworks.

**This is NOT a persona clone.** It does not imitate Lizheng's voice. It cites sources so you can form your own judgment.

## Key features

- **Source-graded answers**: Every claim is tagged as Direct Source / Synthesis / Current Thesis / Inference
- **Video timestamp recall**: Can retrieve specific points from YouTube video transcripts with timecodes
- **Context Architecture aware**: Understands Lizheng's frameworks (impossible triangle of AI transformation, fake work, dynamic quality, etc.)

## Out-of-box usage

1. Install Hermes Agent
2. Import this skill (copy `SKILL.md` to your Hermes skills directory, or use Skills Center)
3. Clone the corpus:
   ```bash
   cd ~/Documents
   git clone https://github.com/sunyuzheng/lizheng-open-context.git
   ```
4. Ask anything about Lizheng's views:
   - "立正怎么评价AI转型？"
   - "白领工作的本质是什么？"
   - "立正在视频里怎么提到David Graeber？"

## Source priority

1. `core-thesis.md` — current stable views
2. Knowledge Bank posts — full arguments with dates
3. *Zhenbenshi* frameworks
4. Solo video transcripts
5. Selected community comments

## Samples

See [`samples/fde-qa.md`](samples/fde-qa.md) for a full Q&A sample (Lizheng's take on FDE roles).

## Hard Rules

- NEVER fabricate quotes, timestamps, or URLs
- NEVER present synthesis as direct source
- NEVER claim an old video represents current stance
- NEVER mimic "Lizheng's voice"
- ALWAYS distinguish direct source / synthesis / inference
- ALWAYS give original links + publication dates

## License

Skill code: [MIT](https://opensource.org/licenses/MIT) · Content from Lizheng: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)

Upstream corpus: [sunyuzheng/lizheng-open-context](https://github.com/sunyuzheng/lizheng-open-context)

---

<br>

# 超线性小助手

> 基于公开来源的立正（Sean Yuzheng / 立正）公共内容问答助手。

**Skill 作者：** [wyuebei-cloud](https://github.com/wyuebei-cloud) · **语料来源：** [sunyuzheng/lizheng-open-context](https://github.com/sunyuzheng/lizheng-open-context) (CC-BY-4.0)

---

## 这是什么？

超线性小助手是 Hermes Agent 的一个 skill，从立正的公开材料中检索并综合回答——包括 Knowledge Bank 文章、YouTube 视频转录、社区帖子，以及《真本事》书籍框架。

**这不是人格克隆。** 它不模仿立正的语气。它引用来源，让你自己形成判断。

## 核心特性

- **溯源分级**：每个论点标注为直接来源 / 综合推断 / 当前主张 / 推理
- **视频时间码召回**：可从 YouTube 视频转录中检索具体内容并标注时间码
- **Context Architecture 感知**：理解立正的框架体系（AI 转型不可能三角、fake work、动态良质等）

## 开箱即用

1. 安装 Hermes Agent
2. 导入本 skill（复制 `SKILL.md` 到 Hermes skills 目录，或通过技能中心导入）
3. 克隆语料库：
   ```bash
   cd ~/Documents
   git clone https://github.com/sunyuzheng/lizheng-open-context.git
   ```
4. 直接提问：
   - "立正怎么评价AI转型？"
   - "白领工作的本质是什么？"
   - "立正在视频里怎么提到David Graeber？"

## 来源优先级

1. `core-thesis.md` — 当前稳定主张
2. Knowledge Bank 文章 — 带日期的完整论述
3. 《真本事》框架
4. 立正独立视频转录
5. 精选社区评论

## 示例

完整问答示例见 [`samples/fde-qa.md`](samples/fde-qa.md)（立正怎么看 FDE 岗位）。

## 硬性规则

- 不生成不存在的引文、时间码或链接
- 不把综合伪装成直接引用
- 不让旧视频自动升级成当前立场
- 不模仿"立正口吻"
- 始终区分直接来源 / 综合 / 推断
- 始终提供原始链接 + 发布日期

## 许可

Skill 代码：[MIT](https://opensource.org/licenses/MIT) · 立正内容：[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)

上游语料库：[sunyuzheng/lizheng-open-context](https://github.com/sunyuzheng/lizheng-open-context)

# skills / 索引

每个 skill 是已经被消化过的理解的可执行形态。**理解先于实现**——一个 skill 能不能稳定运行，不取决于它的格式有多漂亮，取决于它背后的理解是否扎实。能追溯回 canon 中一篇具体文章的 skill，是 vidyā 闭环的本来形态。

skill 分两类：

**lens** — 单一视角或动作。可以在对话的任意时刻被召唤；只使用已经在上下文中的材料，不主动打开新文件、不驱动多步流程。短小、可组合、有显式的硬约束。

**workflow** — 完整方法论。自己驱动多步流程，往往内部编排多个 lens。

---

## lens

- **theory** — 用 Naur 三标准解释代码（现实↔代码 / 为何如此 / 修改顺纹逆纹）
- **predict** — 读不熟悉的代码前先猜，读后对照差异
- **metaphor** — 一句"像 ___"逼出系统的形，看哪个模块塞不进去
- **negative-space** — 这段代码刻意不做什么
- **counterfactual** — 换成 X 会先在哪里崩

> `predict` / `metaphor` / `negative-space` / `counterfactual` 抽取自 `code-theory-reconstruction` 的 move set；大 skill 内部目前未动，留待这套 lens 试用稳定后再考虑改造为编排体。每个 lens 的源头标在自己 SKILL.md 顶部。

---

## workflow

- **code-theory-reconstruction** · 代码理解陪练。三种模式（orient / debug / extend），全程把"理论持有者"的角色留给用户，agent 只做对手、书记、综合提醒 · from: `canon/languages/naur_programming_as_theory_building.md`、`canon/inquiry/polanyi_tacit_dimension.md`
- **socratic-paper-reading** · 苏格拉底式多遍读论文。机械工作（抽结构、查引用、找图、生成攻击面）交给 agent，判断工作（这真的成立吗、这真的新吗、我会怎么写）留给用户 · 适用：用户分享 paper / 上传 PDF
- **github-qa-extractor** · 从 GitHub 仓库抽出有结构意义的问题——issue、PR、discussion、code review · 适用：用户提供 repo URL

---

## 给新 skill 的最低要求

1. **frontmatter 至少有 `name` 和 `description`。** description 是 AI 自动调用的索引——它的工作不是"说明书"，而是触发器。
2. **description 三件套**：
   - **触发短语**——用户实际会说出的、agent 应当听见的话（包括 `/<name>` 这种显式命令）。
   - **反触发情况**——什么时候不要用、什么时候让位给别的 skill。
   - **scope / precondition**——这个 skill 的边界。
3. **lens 必须显式说明它"不做什么"。** 例如"do not re-open files"、"only use what's already in conversation"。没有这种硬约束的 lens 会无声膨胀回 workflow，组件化就失败了。
4. **新增后在本索引补一行**，格式：`name · 一句话讲它做什么 · 触发方式 · scope · from: <canon path>`。
5. **如果直接对应 canon 某篇文章，标出 `from:` 路径。** 这建立 canon ↔ skill 的可追溯关系；canon 那篇更新或被移出（参见 `trace/_deleted.md`），相关 skill 也应当被重审。

# Project Rules

## 当前目标

完成开店前可上线的 Session Concept Versions，并等待开店后进入真实用户测试。

当前阶段最大的风险是复杂化。

## Workspace Architecture Governance

当前不新增 `Founder Operating System/` 文件夹。

经过评估，当前 Piano by Her 工作台已经具备 Founder Operating System 的核心组成。以下文件组合即作为 Founder Operating System:

- [Brand Philosophy](./Brand_Philosophy.md)
- [Project Rules](./Project_Rules.md)
- [Decision Log](./Decision_Log.md)
- [Project Index](./Project_Index.md)
- [Task Board](./Task_Board.md)
- [AI Constitution](./AI_Constitution.md)

不新增新的信息层级，避免让项目变厚、变复杂。

### 核心文件职责

| 文件 | 唯一职责 | 禁止承担 |
| --- | --- | --- |
| Brand_Philosophy.md | 记录为什么做 Piano by Her，包括品牌愿景、长期目标、用户价值、核心理念 | 当前任务、项目进度、日计划 |
| Project_Index.md | 当前项目总览，包括项目列表、项目状态、项目阶段 | 详细任务 |
| Decision_Log.md | 记录为什么做这个决定，并保留历史决策 | 替代 Version Log 或 Task Board |
| Project_Rules.md | 所有项目通用规则，包括轻量原则、归档流程、治理规则、Zero Trust Governance | 具体项目内容 |
| AI_Constitution.md | AI Agent 工作规则，包括 AI 职责、Evidence、Fact / Hypothesis / Recommendation、Creator Review | 品牌哲学、项目进度 |
| AI_Agent_Progress.md | AI Agent 当前开发进度，包括已完成、下一步、阻塞 | 长期规则 |
| Task_Board.md | 人类可读的当前行动板，只展示 Current Focus、Next Action、Waiting | 完整任务管理数据库 |

### Session 文件夹职责

| 文件夹 | 职责 | 禁止承担 |
| --- | --- | --- |
| Session/Framework/ | 所有 Session 通用规则，包括 Session 生命周期、通用流程、通用组件 | 具体 Session 内容 |
| Session/Products/ | 具体 Session 产品，包括核心主题、Session Card、歌曲、Teacher Score、Lesson Video、临别赠卡、体验组件 | 通用治理规则 |

当前如果发现旧内容已经散落在多个位置，不自动删除、不自动移动。先标记为架构治理建议，等待 Creator Review。

## AI Agent Context Loading Rule

任何 AI Agent 生成 Daily Brief、项目建议、状态判断时，必须按以下优先级读取上下文:

1. [Brand Philosophy](./Brand_Philosophy.md): 确定长期方向。
2. [Project Rules](./Project_Rules.md): 确定工作规则。
3. [Decision Log](./Decision_Log.md): 读取最新决策；旧决策必须检查是否存在 Current Rule Override。
4. [Project Index](./Project_Index.md): 读取当前项目状态。
5. 具体项目文件: 例如 Session、Space、AI Agent 相关文件。

禁止随机读取所有文件后自行判断。

如果不同文件出现冲突，判断优先级为:

最新 Decision Log

>

Project Rules

>

Brand Philosophy

>

旧历史记录

AI 不允许根据旧记录恢复已经废弃的规则。

## 核心定位

最高层品牌依据是 [Brand Philosophy](./Brand_Philosophy.md)。任何品牌定位、产品哲学、体验理念、长期方向都必须与 Brand Philosophy 保持一致。

Brand Philosophy 应保持精简，只记录最核心、最长期、最不能丢失的东西。具体 Session 设计、任务、执行细节不进入 Brand Philosophy。

Piano by Her 不是钢琴品牌，也不是单纯的女性疗愈空间。

Piano by Her 是一个以 Session 为核心的人生体验品牌。

钢琴只是当前阶段最熟悉、最能使用的第一个 Medium。未来可以扩展到缝纫、插花、美甲、瑜伽、冥想、茶、写作等媒介，但任何 Medium 都不能取代 Session 本身。

真正发生改变的人，是用户自己。老师、钢琴、空间、香味、音乐、卡片，都只是帮助她完成改变的支持系统。

## 命名原则

核心体验统一称为 Session，或“人生体验 Session”。

不使用 Course 或 Lesson 命名核心产品，因为它们会把用户预期拉向老师、学习、技能和考试。

## 我的职责

从现在开始，我承担三个角色:

1. Product Manager: 推进 Piano by Her 的产品研发。
2. Archivist: 管理项目档案，记录重要决策背后的原因。
3. Challenger: 在新产品、流程、物料、功能进入开发前提出挑战。

## Archivist 规则

重要决策不能只记录结论，必须记录:

- Decision: 做了什么决定。
- 为什么这样做？
- 为什么不用其他方案？
- 这个决定解决了什么问题？
- 以后如果重新设计，需要注意什么？

目标是保留设计初衷，避免未来回顾时只看到结论，忘记原因。

## Brand Philosophy 更新规则

如果一次讨论涉及品牌定位、产品哲学、体验理念、长期方向，而不仅仅是某个 Session 的设计，必须判断:

这是否会影响 Brand Philosophy？

如果会，必须同步更新 [Brand Philosophy](./Brand_Philosophy.md)，并在 Philosophy Evolution 中记录:

- 新增了什么理念。
- 为什么新增。
- 它会如何影响未来产品的发展。

## 自动归档规则

以后用户提出新内容时，不要求用户判断应该更新哪个文档。我必须先判断:

1. 它属于哪个模块？
2. 它属于哪个生命周期状态？
3. 它是否影响 Brand Philosophy？
4. 是否需要进入 Decision Log？
5. 是否需要产生新任务？

然后自动更新对应文档。

归档层级:

| 内容类型 | 归档位置 |
| --- | --- |
| 品牌存在意义、长期理念、用户价值、体验哲学 | Brand Philosophy |
| 开发规则、生命周期、是否该做、Parking Lot | Project Rules |
| Session 通用开发结构 | Session Framework |
| 具体 Session 内容 | 对应 Session 文档或 Session Framework 中的当前状态记录 |
| 空间布局、装修、Arrival、Journey Room、Landing Room、Cafe | Space 相关文档 |
| 具体任务 | Task Board |
| 重要决策及原因 | Decision Log |
| 版本变化 | Version Log |
| 尚未开始开发或尚未确定方向的未来想法 | Parking Lot |

判断目标不是做更多，而是维护长期产品系统，避免不同 Session 之间出现优先级误解。

## GitHub 仓库维护规则

GitHub 仓库 `wd98990921-byte/Piano-by-her` 是 Piano by Her 项目的唯一正式版本（Single Source of Truth）。

所有正式内容均维护在该仓库中。

### ChatGPT 与 Codex 分工

ChatGPT 负责:

- 产品讨论。
- 品牌讨论。
- Session 设计。
- 商业策略。
- 创意发散方案推演。

这些内容属于 Discussion，不直接进入正式仓库。

Codex 负责:

- 更新正式文档。
- 保持项目结构一致。
- 创建 commit。
- 输出 Update Summary。
- 告知当前 commit 状态。
- 保持版本历史完整。

Codex 是 Project Manager，不是讨论者。

### 允许更新 GitHub 的条件

只有当用户明确说以下任一表达时，才允许修改正式仓库:

- 更新到 Codex
- 同步正式版本
- 更新 GitHub

平时讨论内容不要提前写入仓库。

未经用户确认的内容，一律视为草稿，不进入正式仓库。

### 每次正式更新必须完成

1. 更新对应文档，例如 Brand、Session、Space、Product、Task、Framework 等。
2. 更新 Decision Log，记录今天做了哪些正式决定、为什么这么决定、影响哪些模块。
3. 更新 Version Log，记录日期、版本、更新内容和重大变更。
4. 如果目录发生变化，必须同步 README 与 Project Index。
5. Commit，Commit Message 必须有意义。
6. 输出 Update Summary，并提醒用户在终端手动执行 `git push origin main` 完成 GitHub 同步。

Codex 不再执行 `git push origin main`。

原因:

终端环境的 GitHub 凭证和 VPN 代理更稳定。由用户手动 push，可以避免 Codex 环境出现 HTTPS 443、Keychain、Token、代理等问题。

Commit Message 示例:

- Session01 Restart finalized
- Landing Room workflow updated
- Brand Philosophy refinement
- Membership product update

禁止使用没有意义的 Commit Message，例如 `update`、`fix`、`123`。

### Git 操作前检查

每次进行任何 Git 操作之前，必须先检查:

- 当前 branch。
- remote。
- latest commit。
- 工作区是否干净。

如果仓库已经初始化且 GitHub 已连接，不重复执行 `git init`、`git remote add` 等初始化命令。

Codex 可以继续检查:

- 当前 HEAD commit。
- main 是否领先 origin/main。
- 当前工作区是否干净。

但不要主动处理 GitHub 登录、Token、代理、push 等问题。

### 不允许

未经确认，不允许:

- 删除文件。
- 修改项目结构。
- 大规模重构。
- 覆盖历史内容。

如果需要结构调整，必须先询问用户。

如果用户明确要求恢复历史版本，优先通过 Git 历史（Commit History）恢复，而不是手工覆盖文件。

### 项目结构原则

保持目前结构:

- Brand
- Session
- Space
- Product
- Task
- Decision Log
- Version Log
- README
- Project Index
- Project Rules

不要随意增加新的一级目录。

新增内容优先放到已有体系。

### Session 开发规则

Session 永远采用:

讨论 → 稳定 → 正式更新 → Commit → 用户手动 Push

不要边讨论边修改正式版本。

### 正式更新后的输出格式

每次正式更新结束，必须输出 Update Summary:

```markdown
# Update Summary

## 本次更新

✅ 修改文件

新增：

修改：

删除：

Decision Log：

Version Log：

Commit：

xxxxxxxx

Push：

未执行（由用户通过终端手动完成）

或:

Push：

等待用户手动执行：

git push origin main

## 下一步建议（最多三项）

1.
2.
3.
```

## Notion 协作规则

项目采用 Notion + GitHub 双系统。

Notion 是项目管理中心（Workspace），负责:

- Daily Task（日常待办）。
- Sprint / Timeline。
- Roadmap。
- Meeting Notes。
- 灵感收集。
- 临时资料。
- 数据库管理。
- 日常运营。

Notion 允许保存:

- 草稿。
- 临时修改。
- 未成熟想法。
- 实验内容。

GitHub 是正式项目仓库（Source of Truth），保存确认后的正式版本:

- Brand。
- Session。
- Space。
- Product。
- Framework。
- README。
- Project Rules。
- Decision Log。
- Version Log。

以后如果用户说“更新到 Codex”，除了更新正式文档并创建 commit 外，Codex 需要同时判断是否存在对应的 Notion 正式数据库，例如:

- Session Database。
- Product Database。
- Space Database。
- Decision Database。
- Task Database。

如果存在对应内容，需要保持 Notion 与 GitHub 的正式内容一致。

长期原则:

- Notion = 项目管理（Project Management）。
- GitHub = 产品知识库（Product Knowledge Base）。
- GitHub 不负责运营。
- Notion 不负责版本管理。
- 任何正式版本更新，都以 GitHub 为最终版本源。
- GitHub 同步由用户在终端手动执行 `git push origin main` 完成。

## AI Collaboration Workflow

未来 ChatGPT、Notion、Codex、GitHub 按以下方式协作。

### 1. Capture

所有新想法、灵感、未验证方向，先记录在 Notion Inbox / Parking Lot。

不直接进入正式项目文档。

### 2. Develop

需要深入思考的内容，在 ChatGPT 中讨论、推演、完善。

ChatGPT 是探索空间，不是正式归档空间。

### 3. Commit

只有经过确认的稳定内容，才同步到 Codex 正式文档。

Codex 负责判断内容进入哪个正式文档，并保持项目结构一致。

### 4. Version

Codex 完成正式更新并创建 commit 后，提醒用户在终端执行 `git push origin main`，通过 GitHub 保存版本。

GitHub 记录经过确认的正式版本，不记录每一个草稿想法。

### 原则

不要让每一个小想法进入正式文档。

先探索，再确认，再归档。

## 项目瘦身规则

Piano by Her 的日常开发只围绕五个模块:

1. Brand: 品牌初心、理念、长期不会改变的东西。
2. Session: 每一个 Session 的设计。
3. Space: 线下空间、动线、装修、氛围。
4. Product: 实体产品、文创、卡片、视频、香薰等。
5. Task: 当前真正需要做的事情。

复杂理论保留在后台，不作为每天开发时的主界面。

目标是让项目每天都愿意打开，并一眼知道今天该做什么。

## Update Summary 输出规则

以后每次完成任何更新后，必须固定输出「Update Summary（更新摘要）」。

目的不是让用户阅读 Markdown 文档，而是让用户快速知道:

1. 项目发生了什么变化。
2. 当前开发到哪里了。
3. 下一步应该做什么。

固定格式:

```markdown
# Update Summary

## 本次更新
- ✅ Brand Philosophy：
  （一句话说明新增或修改了什么）

- ✅ Session：
  （一句话说明新增或修改了什么）

- ✅ Space：
  （一句话说明新增或修改了什么）

- ✅ Project Rules：
  （一句话说明新增或修改了什么）

- ✅ Decision Log：
  （记录了什么重要决策）

- 📋 新增 Task：
  （新增了哪些待办）

- 🅿️ Parking Lot：
  （哪些想法被暂存，以及为什么）

## 当前项目状态
一句话说明目前开发到了哪一步。

## 下一步建议（最多三件事）

1.
2.
3.

## 风险提醒（如果有）

如果发现偏离 Brand Philosophy、设计过度、增加复杂度，直接提醒。

如果没有风险，写:

✅ 当前方向与 Brand Philosophy 保持一致。
```

下一步建议最多三件事，并按影响力排序。

## Challenger 规则

以后任何新的产品、流程、物料、功能进入开发前，先做 Experience First 判断，再回答 Challenger 五问。

## 反过度设计规则

任何时候，如果用户开始过度设计、偏离 MVP、增加复杂度，我不能顺着继续开发。

我必须主动提醒:

- 当前想法是否偏离已确认的 Session 生命周期。
- 当前想法是否增加了不必要复杂度。
- 当前想法是否仍然符合 Brand Philosophy。

如果存在风险，我必须给出更简单、更容易验证的方案。

优先选择:

1. 更少步骤。
2. 更少物料。
3. 更少空间改造。
4. 更快真实测试。
5. 更直接验证 Transformation。

## Experience First 原则

Piano by Her 的所有设计，都必须围绕用户体验，而不是产品本身。

每讨论一个新想法，先判断它提升的是:

1. Emotion: 用户情绪。
2. Transformation: 用户改变。
3. Experience: 用户体验。
4. Product: 仅仅增加了一个产品。

如果只是增加 Product，而没有提升 Emotion、Transformation、Experience，需要提醒重新思考，不进入开发。

永远优先设计体验，而不是设计产品。

## Session 日常开发方式

日常开发每个 Session，只围绕三个问题:

1. User Journey: 用户从推门进入，到最后离开的全过程。
2. Experience Detail: 每一步具体发生什么。
3. Products: 为了这个 Session 需要制作什么。

优先回答:

- 这个体验完整吗？
- 流程顺吗？
- 用户舒服吗？
- 有没有多余步骤？
- 需要制作什么？

禁止先设计产品、卡片、文创或空间。

Why、Transformation、Memory、Validation 等理念保留为后台指导原则，主要沉淀在 Brand Philosophy 和 Project Rules 中。

## Session 生命周期规则

所有 Session 使用同一套生命周期:

Idea → Concept Development → Completed → Testing → Iteration

所有 Session 地位相同。

Session 01、Session 02、Session 03 等只是不同主题产品，不代表开发顺序、重要程度或上线优先级。

开店后，所有已经完成开发的 Session 会同时作为客户可选择的体验主题上线。

不要使用“先验证 Session 01，再开发 Session 02”的逻辑。

### 状态定义

- Idea: 只有初步想法，尚未开始开发。
- Concept Development: Session 从概念到体验组件的完整设计阶段。
- Completed: Concept Version 已完成，核心主题明确，用户体验流程明确，主要体验组件完成；不代表已经经过真实客户测试。
- Testing: 开店后进入真实用户体验测试阶段，收集客户反馈、观察体验效果、根据真实数据优化。
- Iteration: 根据真实反馈进行修改。

Concept Development 包括:

- Before We Meet（所有 Session 通用模块，默认完成）。
- 核心主题定义。
- Session Card 正反面。
- 歌曲选择。
- Teacher Score。
- Lesson Video。
- 临别赠卡正反面。
- 其他体验组件。

已完成 Concept Version 的 Session:

- 不自动进入 MVP。
- 不自动创建优化任务。
- 不自动进入下一阶段。

只有开店后的真实用户反馈、数据结果，或创始人明确要求，才进入 Testing 或 Iteration。

当前 Session 状态:

- Session 01｜RESTART｜重新开始: Completed。
- Session 02｜LEAVE IT THERE｜放下: Completed。
- Session 03｜BECOMING｜成为: Concept Development。

## Parking Lot 规则

Parking Lot 只用于:

- 有想法但尚未开始开发的 Session。
- 尚未确定方向的主题。
- 尚未开始开发的 Medium、产品、空间或长期方向。

已经完成概念设计的 Session 不继续放在 Parking Lot。

## Medium 原则

当前已完成 Concept Version 的 Session 使用钢琴作为 Medium。其他 Medium 记录在 Parking Lot，不自动进入当前开发。

## Challenger 五问

任何新的产品、流程、物料、功能进入开发前，必须回答五个问题:

1. 它解决了什么问题？
2. 如果没有它，Session 还能成立吗？
3. 有没有更简单的方法？
4. 是否已经有其他产品承担了这个功能？
5. 如果必须删掉一个产品，它会不会是最先被删掉的那个？

如果不能通过，不进入开发，建议放入 [Parking Lot](./Parking%20Lot（以后再做）/ParkingLot.md)。

## 轻量原则

不要为了丰富而增加内容。

只为了提升体验而增加内容。

每增加一个新东西，都必须思考是否有东西可以删掉。

产品应该越来越简单，而不是越来越复杂。

## 轻量开发原则

如果讨论开始偏向以下方向，需要主动提醒是否已经被验证:

- 设计太多产品。
- 设计太多 Session。
- 设计太多文创。
- 设计太多会员体系。
- 设计未来几年才需要的内容。

如果尚未开始开发或尚未确定方向，建议放入 Parking Lot。

## 工作原则

我的工作不是帮助项目做更多，而是帮助项目:

- 做得更少。
- 做得更准确。
- 做得更完整。

每一个设计都必须被检查:

- 是否让产品更简单？
- 是否让产品更清晰？
- 是否让体验更打动人？

如果不能，应主动提出质疑，而不是直接开发。

## 研发目标

开发目标不是功能越来越多。

开发目标是: 真正打动人的核心体验越来越深。

## 关联文档

- [Brand Philosophy](./Brand_Philosophy.md)
- [README](./README.md)
- [Decision Log](./Decision_Log.md)
- [Session Framework](./Session/Framework/Framework.md)
- [Parking Lot](./Parking%20Lot（以后再做）/ParkingLot.md)

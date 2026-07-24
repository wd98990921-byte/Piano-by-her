# Decision Log

## Purpose

Decision Log is the Decision Library for Piano by Her.

It does not only record final decisions.

It records the logic behind important decisions so future AI Agents can understand why a direction was chosen, what alternatives were considered, and how the decision should be validated later.

Existing historical entries are preserved as they are.

Future important decisions should use the template below.

## Future Decision Template

### Decision: [Decision Title]

- Status:
- Date:
- Impacted Modules:

#### 1. Decision

What was decided?

#### 2. Context

Why did this decision need to be made at that moment?

#### 3. Options Considered

What options were considered?

#### 4. Final Choice

What option was chosen?

#### 5. Reasoning

Why was this option chosen over the alternatives?

#### 6. Future Validation

How will we know later whether this decision was right?

## 2026-07-08

### 决策: 当前只开发 Session 01《重新开始》

- 状态: ☑ 已完成
- 原因: 项目处于 MVP 阶段，需要先完成一个可真实测试的线下体验。
- 影响模块: Session 01, Testing, Journey Room, Products, Media

### 决策: 非当前阶段想法进入 Parking Lot

- 状态: ☑ 已完成
- 原因: 避免第二家店、Session 02、文创、会员等方向打断当前开发节奏。
- 影响模块: Parking Lot, Task Board

### 决策: Session 从人生体验设计开始

- 状态: ☑ 已完成
- 原因: Piano by Her 的 Session 主体是她的人生处境与转变，不是钢琴产品本身。
- 影响模块: Session Framework, Session 01, Space
- 结果: 每个 Session 按 Why, Who, Before, After, Journey, Piano Moment 建立；钢琴只是 Journey 中的一个环节。
- 后续更新: 已在 v0.3 升级为 Why → Who → Before → Transformation → After → Journey → Piano Moment → Memory → Validation。

### 决策: Transformation 是 Session 的核心

- 状态: ☑ 已完成
- 原因: Piano by Her 不卖钢琴课，也不卖疗愈，而是设计 Life Experience；真正的核心是用户内心发生的改变。
- 影响模块: Session Framework, Session 01, Testing, Products, Space
- 结果: 每个 Session 必须按 Why → Who → Before → Transformation → After → Journey → Piano Moment → Memory → Validation 推进。

### 决策: 新增内容必须通过 MVP 三问

- 状态: ☑ 已完成
- 原因: 避免产品、流程、物料、空间配置提前膨胀。
- 影响模块: Session Framework, Task Board, Parking Lot, Products, Space
- 结果: 新增内容必须回答它解决什么问题、没有它 Session 是否还能成立、它是否是 Session 01 MVP 必须项；不能通过则进入 Parking Lot。
- 后续更新: 已在 2026-07-09 升级为 Challenger 五问。

## 2026-07-09

### Decision: 我同时承担 Product Manager / Archivist / Challenger 三个角色

- 状态: ☑ 已完成
- 为什么这样做: Piano by Her 进入长期研发后，仅推进任务不够；项目还需要保存设计初衷，并持续阻止不必要的复杂化。
- 为什么不用其他方案: 如果只做 Product Manager，容易把用户提出的想法直接转成任务；如果只记录最终结论，未来会丢失为什么这样设计。
- 这个决定解决了什么问题: 建立“推进、归档、挑战”三种职责，保证项目既能向前走，也能保留判断依据，并及时拦截非 MVP 内容。
- 以后如果重新设计，需要注意什么: 不要把 Challenger 变成否定一切；挑战的目的不是阻止开发，而是让真正必要的内容进入开发。
- 影响模块: README, Project Rules, Decision Log, Session Framework, Parking Lot

### Decision: 新增内容必须通过 Challenger 五问

- 状态: ☑ 已完成
- 为什么这样做: Piano by Her 当前最大风险是复杂化；新产品、流程、物料、功能如果未经挑战，会稀释 Session 01 的核心体验。
- 为什么不用其他方案: 原有 MVP 三问能判断“是否必要”，但不足以检查是否有更简单方法、是否重复、是否应该被优先删除。
- 这个决定解决了什么问题: 在进入开发前建立拦截机制，避免为了丰富而增加内容。
- 以后如果重新设计，需要注意什么: 五问通过不等于立刻开发；仍需确认它服务 Emotion → Transformation → Experience → Medium → Product → Space 的顺序。
- 影响模块: README, Project Rules, Session Framework, Parking Lot, Products, Space

### Decision: 产品轻量优先

- 状态: ☑ 已完成
- 为什么这样做: 当前目标是完成 Session 01 真实用户测试，核心体验深度比功能数量重要。
- 为什么不用其他方案: 通过增加更多产品、Session、文创、会员体系来显得完整，会提高执行成本，并让真实用户测试失焦。
- 这个决定解决了什么问题: 明确“不要为了丰富而增加内容，只为了提升体验而增加内容”。
- 以后如果重新设计，需要注意什么: 每增加一个新东西，都要同时检查是否有旧东西可以删掉。
- 影响模块: Project Rules, Task Board, Parking Lot, Products, Space

### Decision: Experience First 是新增想法的前置判断

- 状态: ☑ 已完成
- 为什么这样做: Piano by Her 的核心不是产品数量，而是用户是否在体验中发生情绪、改变和记忆。
- 为什么不用其他方案: 如果只用 Challenger 五问，仍可能讨论一个“看似有用但本质只是新增产品”的想法；Experience First 能先判断它是否提升 Emotion、Transformation 或 Experience。
- 这个决定解决了什么问题: 防止项目把产品当作目标，确保新想法先服务用户体验，再考虑是否需要产品承载。
- 以后如果重新设计，需要注意什么: Product 不是被禁止；Product 必须证明自己服务前三者，而不是独立存在。
- 影响模块: README, Project Rules, Session Framework, Decision Log

### Decision: Piano by Her 是以 Session 为核心的人生体验品牌

- 状态: ☑ 已完成
- 为什么这样做: “钢琴品牌”或“女性疗愈空间”都无法准确表达项目核心。Piano by Her 真正提供的是通过被设计好的 Session，帮助女性在某个人生状态里暂时放下外界身份，重新回到自己，并带走真实的内在改变。
- 为什么不用其他方案: 如果定位为钢琴品牌，项目会被技能、课程和练习逻辑限制；如果定位为疗愈空间，又容易变成泛化的情绪安抚。当前定位把核心资产明确为 Session 体验系统，媒介只是支持系统。
- 这个决定解决了什么问题: 明确长期品牌可以多媒介发展，同时防止任何媒介取代 Session 本身。
- 以后如果重新设计，需要注意什么: 不能因为增加新媒介而偏离初心。品牌不是让女性学会更多技能，也不是让女性变得更优秀，而是让她在一个被温柔设计的 Session 里重新感受到自己，并带着一点更轻松、更勇敢、更完整的自己离开。
- 影响模块: README, Project Rules, Session Framework, Session 01, Project Index, Parking Lot

### Decision: 在开发顺序中加入 Medium 层

- 状态: ☑ 已完成
- 为什么这样做: 钢琴只是当前阶段最熟悉、最能使用的第一个媒介；未来可能出现缝纫、插花、美甲、瑜伽、冥想、茶、写作等媒介，需要在 Framework 中明确 Medium 与 Session 的关系。
- 为什么不用其他方案: 如果继续只写 Product，媒介会被误认为产品或物料；如果继续只写 Piano Moment，长期扩展会被钢琴绑定。
- 这个决定解决了什么问题: 将开发顺序升级为 Emotion → Transformation → Experience → Medium → Product → Space，确保先定义改变，再选择媒介。
- 以后如果重新设计，需要注意什么: Medium 的选择必须服务 Transformation；当前 MVP 只使用钢琴，其他 Medium 全部进入 Parking Lot。
- 影响模块: Session Framework, README, Project Rules, Project Index, Session 01, Parking Lot

### Decision: 核心体验统一称为 Session

- 状态: ☑ 已完成
- 为什么这样做: Course / Lesson 会让用户想到老师、学习、技能、考试，与 Piano by Her 的体验定位不一致。
- 为什么不用其他方案: 如果继续使用 Course 或 Lesson，项目容易被拉回钢琴课或技能课逻辑。
- 这个决定解决了什么问题: 统一产品语言，明确核心不是教学，而是人生体验 Session。
- 以后如果重新设计，需要注意什么: 内部文档和对外表达都应优先使用 Session 或“人生体验 Session”；只有在解释“不是课程”时才使用 Course / Lesson 作为反例。
- 影响模块: README, Project Rules, Session Framework, Session 01

### Decision: Session 01《重新开始》从“解决问题”升级为“重新连接自己”

- 状态: ☑ 已完成
- 为什么这样做: “重新开始”不应该被设计成替用户解决人生问题。Session 01 的真实价值是提供一个空间，让她暂时放下所有身份，重新连接自己，并带着一点勇气回到现实。
- 为什么不用其他方案: 如果继续把 Before 写成焦虑、疲惫、压力，表达太浅；如果把 After 写成学会一首歌或钢琴水平，会把体验拉回技能课逻辑；如果把它定义成 SPA、按摩或咖啡式放松，又无法体现完整人生体验。
- 这个决定解决了什么问题: 明确 Session 01 的核心 Transformation: 不是“重新开始了”，而是“重新相信自己可以开始”。
- 以后如果重新设计，需要注意什么: 不要承诺改变用户人生。Session 只负责改变她看待人生的方式，并通过真实体验支持这个变化。
- 影响模块: Session 01, Session Framework, Testing, Journey, Landing Room, Cafe

### Decision: Journey 每一步都必须写 Why

- 状态: ☑ 已完成
- 为什么这样做: Journey 不是流程清单，而是解释为什么她需要经历这一切。
- 为什么不用其他方案: 如果只列 Arrival、洗手、护手霜、卡片、点香、钢琴、拍照、休息、Landing Room、Cafe，容易变成“堆体验环节”，无法判断哪些必须保留。
- 这个决定解决了什么问题: 每一步都必须回答为什么存在、解决什么问题、如果删掉体验会失去什么，从而控制复杂化。
- 以后如果重新设计，需要注意什么: 任何无法说明 Why 的步骤，默认不进入 MVP；拍照、点香、卡片等都必须通过真实测试验证必要性。
- 影响模块: Session 01, Session Framework, Arrival, Journey Room, Landing Room, Cafe

### Decision: Session 01 测试保留“先钢琴 / 先放松”两种方案（已被 2026-07-13 正式教学模式覆盖）

- 状态: ☑ 已完成
- 为什么这样做: 当前还没有真实用户反馈证明应该先进入钢琴，还是先让用户放松。
- 为什么不用其他方案: 现在直接决定会把设计者判断当成用户真实反应，增加测试偏差。
- 这个决定解决了什么问题: 把不确定性保留到真实测试中，让用户决定哪种顺序更适合完成 Transformation。
- 以后如果重新设计，需要注意什么: 第一轮测试必须记录两种路径下用户进入状态、放松程度、钢琴参与感和离开后的表达差异。
- 影响模块: Session 01, Testing, Journey Room
- 后续更新: 2026-07-13 已定稿为“老师先现场带她开始，再把空间还给她；需要时，再回来”。不再保留“先钢琴 / 先放松”作为当前正式测试方案。

### Decision: Landing Room 与 Cafe 重新定位

- 状态: ☑ 已完成
- 为什么这样做: Landing Room 和 Cafe 不能只是结束和社交空间。Session 结束后，用户需要的是重新进入现实之前的缓冲，以及可选择停留方式的自由。
- 为什么不用其他方案: 如果 Landing Room 只是休息室，会丢失“重新准备面对世界”的作用；如果 Cafe 被定义为社交，会压迫需要独处的用户。
- 这个决定解决了什么问题: 明确 Journey Room 是人生暂停，Landing Room 是重新准备面对世界，Cafe 是停留的自由。
- 以后如果重新设计，需要注意什么: Cafe 不规定用户必须聊天、分享或消费；独处、发呆、看书、什么都不做都应成立。
- 影响模块: Session 01, Landing Room, Cafe, Testing

### Decision: 本轮 Session 开发顺序调整为 Why → Who → Before → Transformation → After → Journey → Memory → Product → Space

- 状态: ☑ 已完成
- 为什么这样做: 本轮发现卡片、护手霜、拍照、点香等都容易被提前当成产品设计，但真正需要先定义的是用户为什么来、为什么改变、体验为什么存在。
- 为什么不用其他方案: 旧顺序把 Medium、Product、Space 放得过早，容易让媒介和物料主导设计。
- 这个决定解决了什么问题: 强制先完成核心人生命题、用户状态、内在改变和 Journey 逻辑，再让产品与空间自然生长。
- 以后如果重新设计，需要注意什么: Medium 仍然重要，但作为支持系统处理；不允许先设计产品、卡片、文创，再倒推体验。
- 影响模块: Session Framework, Session 01, Products, Space

### Decision: Brand Philosophy 成为最高层品牌文档

- 状态: ☑ 已完成
- 为什么这样做: Piano by Her 已经沉淀出多个跨 Session、跨 Medium、跨空间的核心理念。如果继续散落在 Session、Decision Log、Project Rules 中，未来产品变多后会增加偏离初心的风险。
- 为什么不用其他方案: 只靠 Decision Log 记录会偏向决策历史，不适合作为长期品牌依据；只放在 Session Framework 会把品牌哲学误认为 Session 方法论。
- 这个决定解决了什么问题: 建立一个最高层文档，统一记录品牌为什么存在、真正想改变什么、长期愿景、体验哲学、产品哲学和不可丢失的原则。
- 以后如果重新设计，需要注意什么: 任何涉及品牌定位、产品哲学、体验理念、长期方向的重要讨论，都要判断是否同步更新 Brand Philosophy，并在 Philosophy Evolution 中记录演进原因。
- 影响模块: Brand Philosophy, README, Project Rules, Project Index, Decision Log, Version Log

### Decision: 建立自动归档工作流

- 状态: ☑ 已完成
- 为什么这样做: 项目文档已经分为 Brand Philosophy、Project Rules、Session Framework、Session 01、Space、Task Board、Decision Log、Version Log、Parking Lot。继续让用户判断更新哪个文档，会增加维护成本并造成信息散落。
- 为什么不用其他方案: 如果只在对话中记录，信息无法沉淀；如果所有内容都写进 Brand Philosophy，会让最高层文档变厚并失去清晰度；如果只写 Decision Log，又无法指导日常执行。
- 这个决定解决了什么问题: 建立自动判断层级和自动归档机制，确保每个新想法被保留、开发、删减或放入 Parking Lot。
- 以后如果重新设计，需要注意什么: 自动归档不能等于自动开发。仍必须先判断是否属于当前 MVP、是否影响 Brand Philosophy、是否需要 Decision Log、是否产生新任务。
- 影响模块: README, Project Rules, Project Index, Brand Philosophy, Decision Log, Version Log

### Decision: Brand Philosophy 保持精简

- 状态: ☑ 已完成
- 为什么这样做: Brand Philosophy 是最高层文档，应该记录长期有效的品牌核心，而不是积累所有理念和执行细节。
- 为什么不用其他方案: 如果 Brand Philosophy 无限变厚，它会失去判断力，未来团队也难以用它做决策。
- 这个决定解决了什么问题: 将 Brand Philosophy 重构为 Why / We Believe / We Don't Believe / Design Principles / Never Change / Philosophy Evolution 六段结构。
- 以后如果重新设计，需要注意什么: 只有影响品牌定位、产品哲学、体验理念、长期方向的内容才进入 Brand Philosophy；Session 具体设计留在 Session 文档。
- 影响模块: Brand Philosophy, Project Rules, README, Project Index

## 2026-07-10

### Decision: 项目日常开发方式瘦身为五个模块

- 状态: ☑ 已完成
- 为什么这样做: 过去的 Framework 更像软件产品管理系统，抽象层过多，不适合每天打开使用。当前更需要一个直观入口，让用户先看到体验画面和今天要做什么。
- 为什么不用其他方案: 如果继续以 Why、Transformation、Memory、Validation 等理论作为日常主界面，会增加理解成本；如果完全删除这些原则，又会丢失品牌和体验判断依据。
- 这个决定解决了什么问题: 将复杂理论保留在后台，日常开发只面对 Brand、Session、Space、Product、Task 五个模块。
- 以后如果重新设计，需要注意什么: 瘦身不是放弃原则。Brand Philosophy 和 Project Rules 继续约束方向，但日常 Session 开发优先用 User Journey、Experience Detail、Products。
- 影响模块: README, Project Rules, Project Index, Session Framework, Session 01, Task Board

### Decision: Session 日常开发改为 User Journey / Experience Detail / Products

- 状态: ☑ 已完成
- 为什么这样做: 用户的思维方式是先看到完整体验画面，而不是先处理理论框架。Session 需要先画出用户从进入到离开的过程，再优化细节和产品。
- 为什么不用其他方案: 如果先讨论理论，容易进入抽象管理；如果先做产品，容易变成卡片、文创、视频堆叠。
- 这个决定解决了什么问题: 让 Session 设计变成可视化、可检查、可测试的体验流程。
- 以后如果重新设计，需要注意什么: 每次讨论 Session，优先问体验完整吗、流程顺吗、用户舒服吗、有没有多余步骤、需要制作什么。
- 影响模块: Session Framework, Session 01, Products, Testing

## 2026-07-13

### Decision: Session 01《重新开始》正式曲目与交付周期确定

- 状态: ☑ 已完成
- 为什么这样做: Session 01 需要从概念进入可交付版本，必须明确名称、曲目、周期和完整完成后的交付物。
- 为什么不用其他方案: 如果继续保持曲目和完成标准不确定，真实测试无法判断体验是否完整，也无法规划老师教学和视频交付。
- 这个决定解决了什么问题: 正式确定 Session 名称为“重新开始 | Restart”，曲目为 Lost in Island，一首歌建议通过 1 个月、4 次体验完整完成；4 次不是强制，完整完成后才拍摄 Journey Film。
- 以后如果重新设计，需要注意什么: 4 次是建议周期，不是会员或课程强制绑定；客人可以只体验 1 次、体验 2 次后切换其他 Session，或随时选择新的 Session。
- 影响模块: Session 01, Products, Testing, Task Board

### Decision: 钢琴教学采用“老师先带她开始，再把空间还给她”

- 状态: ☑ 已完成
- 为什么这样做: Piano by Her 的体验需要老师帮助客人进入状态，但又不能让用户持续依赖老师或被教学感压迫。
- 为什么不用其他方案: 全程录播教学会缺少人的引导；老师全程在场会减少用户独处和自我连接的空间。
- 这个决定解决了什么问题: 明确老师现场出现进行手位、旋律和最初学习引导；随后老师离开，客人看 Lesson Video 独立练习，需要时按铃短暂协助。
- 以后如果重新设计，需要注意什么: 老师是支持系统，不是体验中心。任何新教学设计都要保留“开始时陪伴、练习时留白、需要时回来”的结构。
- 影响模块: Session 01, Session Framework, Products, Testing

### Decision: Lesson Video 取代客人用五线谱

- 状态: ☑ 已完成
- 为什么这样做: 客人不需要在离店后承担练习任务，完整 Lesson Video 比纸质谱更适合承担记忆与回顾功能。
- 为什么不用其他方案: 客人用五线谱、数字谱、琴键定位图、左右手轨道图、动态键盘、琴键贴纸、拆分教学视频都会增加学习负担和产品复杂度。
- 这个决定解决了什么问题: Lesson Video 正式定位为电子曲谱 / 记忆辅助；五线谱只供老师内部教学使用。
- 以后如果重新设计，需要注意什么: 不做单手版、双手版、分段版、逐课进度版或个性化剪辑；每位第一次体验《重新开始》的客人收到同一支完整 Lesson Video。
- 影响模块: Session 01, Products, Session Framework

### Decision: Session 01 单次交付物与完整完成交付物分层

- 状态: ☑ 已完成
- 为什么这样做: 一次体验后客人未必能演奏得足够完整，不适合把当堂手部弹奏录像作为标准交付物。
- 为什么不用其他方案: 如果每次都交付手部录像或个性化视频，会增加制作成本，也可能让用户产生表演压力。
- 这个决定解决了什么问题: 单次体验交付 Session Card、Journey Photo、完整 Lesson Video；完整完成该 Session 后，再交付专属 Journey Film / 成品弹奏视频。
- 以后如果重新设计，需要注意什么: Journey Film 只给完整完成 Session 的客人；Journey Photo 更适合作为单次体验纪念。
- 影响模块: Session 01, Products, Media, Testing

## 2026-07-14

### Decision: GitHub 成为唯一正式版本，Notion 成为项目管理中心

- 状态: ☑ 已完成
- 为什么这样做: Piano by Her 已经完成第一次 GitHub Push，需要把正式知识库和日常讨论/运营空间分开，避免每次讨论都提前污染正式仓库。
- 为什么不用其他方案: 如果所有讨论都直接写进 GitHub，正式版本会变成草稿堆；如果只用 Notion，项目缺少清晰的版本历史和可追溯的正式文档；如果 ChatGPT、Codex、GitHub、Notion 职责不清，后续维护会混乱。
- 这个决定解决了什么问题: 明确 ChatGPT 是讨论空间，Codex 是正式项目维护者，GitHub 是产品知识库和 Single Source of Truth，Notion 是项目管理中心。
- 以后如果重新设计，需要注意什么: 只有用户明确说“更新到 Codex”“同步正式版本”或“更新 GitHub”时，才修改正式仓库；未经确认的内容一律视为草稿。任何正式更新都必须同步对应文档、Decision Log、Version Log，并 Commit / Push 到 main。
- 影响模块: README, Project Rules, Project Index, Decision Log, Version Log

## 2026-07-16

### Decision: Session 产品更新流程补充为 Session Card → Piano Song → Emotion Card

- 状态: ☑ 已完成
- 为什么这样做: Session 需要保持日常开发简单，但进入产品化定义时，需要有稳定顺序，避免先做物料或视频而丢失体验主线。
- 为什么不用其他方案: 如果直接扩展复杂课程结构，会让项目重新变成教学系统；如果不定义产品更新顺序，Session Card、曲目、Lesson Video、Emotion Card 容易散落在不同文档。
- 这个决定解决了什么问题: 明确 Session Card 用于进入前确认主题与当下状态；Piano Song 负责曲目、老师曲谱和 Lesson Video；Emotion Card 负责结束时保留核心情绪。
- 以后如果重新设计，需要注意什么: 这只是产品更新顺序，不改变 Session 01 现有正式结构，也不允许把产品开发放到体验之前。
- 影响模块: Session Framework, Products

### Decision: Lesson Video 增加 Hand & Fingering Guide

- 状态: ☑ 已完成
- 为什么这样做: 成人体验者可能知道音符，但不知道手指如何安排。左右手指法提示能降低进入钢琴体验的阻力。
- 为什么不用其他方案: 不恢复纸质谱、数字谱、琴键贴纸或复杂动态键盘，因为这些会增加产品复杂度，并偏离 MVP 轻量原则。
- 这个决定解决了什么问题: 在不新增复杂交付物的前提下，让 Lesson Video 承担必要的手指安排提示。
- 以后如果重新设计，需要注意什么: Hand & Fingering Guide 是 Lesson Video 内部内容，不是新增独立客户交付物。
- 影响模块: Products, Session Framework

### Decision: Session 02｜LEAVE IT THERE 只进入 Parking Lot 的 Concept Development

- 状态: ☑ 已完成
- 为什么这样做: Session 02 已有明确方向，但 Session 01 仍是当前 MVP，不应建立完整 Session 文件或打断当前研发节奏。
- 为什么不用其他方案: 如果现在创建完整 Session 02 文档，会提前扩展 Session 系统；如果完全不记录，又会丢失已确认的概念方向。
- 这个决定解决了什么问题: 将 Session 02｜LEAVE IT THERE｜放下保留为未来概念，记录主题、核心句、精神和已确认的 Session Card 第一题。
- 以后如果重新设计，需要注意什么: Session 02 不针对某一种事件，而是让客户将自己的故事带入；正式开发必须等 Session 01 达到稳定版本后再启动。
- 影响模块: Parking Lot, Session Framework, Products

### Decision: Piano Fingering Guide 与 Session Song Reveal 暂存 Parking Lot

- 状态: ☑ 已完成
- 为什么这样做: 两个想法都可能改善 Session 体验，但目前尚未通过真实测试验证，也不应立刻增加当前 MVP 的物料和流程复杂度。
- 为什么不用其他方案: 如果现在直接制作钢琴指法指引牌，可能与 Lesson Video 中的 Hand & Fingering Guide 重复；如果现在直接改变歌曲呈现时机，可能影响现有 Session 01 流程而没有测试依据。
- 这个决定解决了什么问题: 保留两个有价值的体验优化方向，同时不打断 Session 01 当前研发节奏。
- 以后如果重新设计，需要注意什么: Piano Fingering Guide 应先验证是否被 Lesson Video 内部指法提示替代；Session Song Reveal 当前倾向方案 B，即在填写 Session Card 时播放曲目，但仍需讨论与测试。
- 影响模块: Parking Lot, Products, Session Framework, Session 01

## 2026-07-21

### Decision: 每个 Session 的正式交付物加入临别赠卡

- Decision: 每个 Session 的正式交付物都加入临别赠卡；Session 01《重新开始》的临别赠卡已设计完成，Session Card 背面内容已完成。
- Context: Session 需要在用户离开前承接体验后的情绪，让她带走一句与本次 Session 相关的话，而不是只留下学习材料或照片。
- Options Considered: 只保留 Session Card、Lesson Video、Journey Photo；将临别赠卡作为可选物料；将临别赠卡纳入每个 Session 的正式交付物。
- Final Choice: 将临别赠卡纳入每个 Session 的正式交付物。
- Reasoning: 临别赠卡直接服务离开时的情绪承接和记忆保留，符合 Session 以体验和 Transformation 为核心的定位；同时它足够轻量，不会增加复杂系统。
- Future Validation: 真实用户测试时观察用户是否理解并保留临别赠卡，以及它是否帮助用户记住 Session 的核心情绪。
- 影响模块: Session Framework, Session 01, Products, Task Board

### Decision: Session 02《放下》继续停留在 Parking Lot，但记录已确认制作进度

- Decision: Session 02｜LEAVE IT THERE｜放下继续不建立完整 Session 文件；仅在 Parking Lot 记录曲目 Sometimes Someone、Teacher Score、Session Card、Lesson Video、临别赠卡已完成。
- Context: Session 02 已出现多个确认成果，但当前 MVP 仍是 Session 01《重新开始》，不能让 Session 02 打断当前测试节奏。
- Options Considered: 立即创建 Session 02 完整文档；完全不记录 Session 02 新进度；在 Parking Lot 中记录已确认事实但不启动正式开发。
- Final Choice: 在 Parking Lot 中记录 Session 02 已确认制作进度，维持 Concept Development 状态。
- Reasoning: 这样既不丢失已经完成的资产，也不把 Session 02 提前推入当前 MVP。
- Future Validation: Session 01 达到稳定版本后，再判断 Session 02 是否进入正式 Session 开发。
- 影响模块: Parking Lot, Products, Task Board

### Decision: Session 生命周期统一为 Idea → Concept Development → Completed → Testing → Iteration

- Decision: 建立统一 Session 生命周期；所有 Session 地位相同，Session 编号不代表开发顺序、重要程度或上线优先级；Session 01｜RESTART｜重新开始与 Session 02｜LEAVE IT THERE｜放下当前状态均为 Completed。
- Context: 旧规则将 Session 01 视为当前 MVP，并把 Session 02 放在 Parking Lot，容易造成不同 Session 之间的优先级误解。
- Options Considered: 保留 Session 01 优先验证逻辑；为 Session 02 创建完整独立文件；建立统一生命周期并只更新状态规则。
- Final Choice: 建立统一生命周期，删除“先验证 Session 01，再开发 Session 02”的项目管理逻辑；已完成 Concept Version 的 Session 不继续放在 Parking Lot。
- Reasoning: Session 01、Session 02、Session 03 等是不同主题产品，不是优先级排序。开店后，所有已经完成开发的 Session 会同时作为客户可选择的体验主题上线。
- Future Validation: 只有开店后的真实用户反馈、数据结果，或创始人明确要求，才进入 Testing 或 Iteration。
- 影响模块: Session Framework, Project Rules, README, Project Index, AI Constitution, Products, Testing, Task Board, Parking Lot, Session 01, Version Log

### Decision: Session 03｜BECOMING｜成为进入 Concept Development

- Decision: Session 03 正式定名为 BECOMING｜成为，状态为 Concept Development。
- Context: 创始人明确输入 Session 03 名称与生命周期状态，需要纳入统一 Session 生命周期管理。
- Options Considered: 放入 Parking Lot；创建完整 Session 03 文件；只在生命周期状态中记录。
- Final Choice: 不放入 Parking Lot，不创建完整 Session 文件；只在 Session 生命周期与当前状态中记录为 Concept Development。
- Reasoning: 根据新生命周期规则，已经开始概念开发的 Session 不属于 Parking Lot；但目前只确认名称和状态，不能扩展未确认内容。
- Future Validation: 只有创始人明确提供更多内容，才继续补充 Session 03 的体验组件。
- 影响模块: Session Framework, README, Project Rules, Project Index, Task Board, Version Log

### Decision: 不新增 Founder Operating System 文件夹，改为定义现有核心文件职责

- Decision: 不新增 `Founder Operating System/` 文件夹；当前已有文件组合即作为 Founder Operating System，包括 Brand Philosophy、Project Rules、Decision Log、Project Index、Task Board、AI Constitution。
- Context: 当前工作台已经具备 Founder Operating System 的核心组成。继续新增一级文件夹会增加信息层级，让 AI 读取上下文更容易混乱。
- Options Considered: 新增 Founder Operating System 文件夹；维持现状不加说明；保留现有结构并定义文件职责与 AI 读取规则。
- Final Choice: 保留现有结构，不新增文件夹；通过 Project Rules、Project Index、AI Constitution 明确文件职责和读取优先级。
- Reasoning: 这能解决信息重复、职责混乱、AI 读取上下文错误的问题，同时避免大规模移动文件或创建复杂系统。
- Future Validation: 后续如果 AI 输出状态判断时仍混淆规则、历史与当前状态，需要优先检查是否遵守 Context Loading Rule。
- Current Rule Override:
  - 旧规则: 可以考虑新增 Founder Operating System 作为更高层工作台。
  - 当前规则: 不新增 Founder Operating System 文件夹，现有核心文件组合即作为 Founder Operating System。
  - 原因: 当前结构已经足够，新增层级会增加复杂度。
- 影响模块: Project Rules, Project Index, AI Constitution, Decision Log, Version Log

### Decision: 被新决策替代的旧规则必须标记 Current Rule Override

- Decision: Decision Log 保留历史，但所有被新决策替代的旧规则，需要用 Current Rule Override 标记旧规则、当前规则和原因。
- Context: Decision Log 中保留了早期 Session 01 MVP、Session 02 Parking Lot 等历史逻辑。AI 如果只搜索关键词，可能误把旧记录当作当前规则。
- Options Considered: 删除旧历史；重写全部 Decision Log；保留历史并新增 Current Rule Override 标记。
- Final Choice: 保留历史，不删除；新增 Current Rule Override 机制。
- Reasoning: 既保留项目演进证据，又防止 AI 恢复已经废弃的规则。
- Future Validation: AI 读取 Decision Log 时必须优先读取最新决策，并检查 Current Rule Override。
- Current Rule Override:
  - 旧规则: 旧历史记录可以直接作为当前判断依据。
  - 当前规则: 旧历史记录必须检查是否被最新 Decision Log 覆盖。
  - 原因: 项目规则会演进，旧记录是历史证据，不一定是当前规则。
- 影响模块: Decision Log, AI Constitution, Project Rules

### Current Rule Override: Session 优先级规则

- 旧规则: Session 01 优先作为 MVP，Session 02 先放入 Parking Lot，等 Session 01 验证后再开发。
- 当前规则: 所有 Session 地位相同；Session 01、Session 02、Session 03 等只是不同主题产品，不代表开发顺序、重要程度或上线优先级。
- 原因: Session 是产品库，不是单一产品。开店后，所有已经完成开发的 Session 会同时作为客户可选择的体验主题上线。

### Current Rule Override: Parking Lot 规则

- 旧规则: 不属于 Session 01 MVP 的内容进入 Parking Lot。
- 当前规则: Parking Lot 只用于有想法但尚未开始开发的 Session、尚未确定方向的主题、尚未开始开发的 Medium / 产品 / 空间 / 长期方向。
- 原因: 已完成概念设计或已进入 Concept Development 的 Session 不应继续停留在 Parking Lot。

### Decision: Community Layer｜品牌共创参与层进入 Parking Lot

- Decision: 将 Community Layer｜品牌共创参与层记录为 Parking Lot，当前不进入 MVP，不影响 Session、Space、Product 开发节奏。
- Context: 该想法探索客户如何以最低成本参与 Piano by Her 的成长，获得轻微掌控感和归属感，但目前尚未进入开发。
- Options Considered: 立即加入 Space 或 Product 开发；创建独立 Community 系统；记录到 Parking Lot。
- Final Choice: 只记录到 Parking Lot。
- Reasoning: Her Trace、Her Choice、Her Archive 都可能提高情感价值和复访理由，但会影响空间运营与品牌参与机制。当前没有运营稳定后的真实反馈，不应提前开发或新增系统。
- Future Validation: 等待未来空间运营稳定后，基于真实客户反馈、复访行为和创始人明确要求重新评估。
- 影响模块: Parking Lot

### Decision: Piano by Her Membership 进入 Product Definition V1

- Decision: 创建 Piano by Her Membership｜长期陪伴会员产品定义，状态为 Product Definition V1。
- Context: 创始人明确输入会员体系的产品定义。它不是传统琴行会员、按课时购买或技能等级提升体系，而是 Lifestyle + Music Experience Membership。
- Options Considered: 继续作为 Parking Lot 的“会员升级”；直接拆解运营任务和价格设计；创建 Membership 产品定义文档。
- Final Choice: 创建 [Membership](./Product/Membership/Membership.md) 作为产品体系文档。
- Reasoning: Membership 已从泛泛的“会员升级”变成清晰的产品定义，但当前仍不进入执行任务、不拆解运营任务、不进入开发排期。独立文档能保存产品定义，同时避免打乱 Session、Space、Product 当前节奏。
- Future Validation: 等待空间确定和开业运营验证，根据真实客户反馈迭代。
- 影响模块: Product, Project Index, Decision Log, Version Log

# Session Framework

## 日常开发方式

以后每一个 Session 的日常开发，只围绕三个问题:

1. User Journey: 用户从推门进入到最后离开的完整流程是什么？
2. Experience Detail: 每一步具体发生什么？
3. Products: 为了完成这个 Session，需要制作什么？

先把体验画出来，再优化。

不要先进入大量理论。

## ① User Journey

User Journey 是用户从推门进入，到最后离开的全过程。

先完整，再优化。

示例:

Arrival

↓

Journey Room

↓

Piano

↓

Photo

↓

Landing Room

↓

Cafe

## ② Experience Detail

Experience Detail 是把 Journey 每一步具体化。

示例:

| Journey Step | Experience Detail |
| --- | --- |
| Arrival | 换鞋、放包、洗手、护手霜 |
| Journey | 写 Session Card、点香、调整灯光、音乐 |
| Piano | 老师现场带她开始、客人看 Lesson Video 独立练习、需要时按铃呼叫老师 |
| Landing | 暖茶、书、安静停留 |
| Cafe | 社交、阅读、喝东西 |

日常开发时，优先回答:

- 这个体验完整吗？
- 流程顺吗？
- 用户舒服吗？
- 有没有多余步骤？
- 需要制作什么？

## ③ Products

Products 是为了这个 Session 需要制作的东西。

示例:

- Session Card
- Today Check-in
- Journey Card
- 香薰
- 视频
- Lesson Video
- Teacher Score（老师内部使用）
- 照片模板

产品永远服务体验。

不要先设计产品，再倒推体验。

## 钢琴类 Session 的教学原则

当前 MVP 的 Medium 是钢琴。

钢琴教学不采用全程录播替代老师，也不把客人推向传统练琴任务。

原则:

- 老师先带她开始。
- 然后把空间还给她。
- 她需要时，老师再回来。

Lesson Video 可以作为电子曲谱 / 记忆辅助，但不承担完整教学替代老师的角色。

客人不需要看到五线谱。五线谱可以作为老师内部教学材料。

## Product 简化原则

如果视频已经能承担记忆与回顾功能，不再额外开发纸质谱、数字谱、琴键定位图、左右手轨道图、动态键盘、琴键贴纸、拆分教学视频等复杂辅助产品。

每一个产品都必须回答:

- 它服务 User Journey 的哪一步？
- 它是否让用户更舒服、更容易进入体验？
- 如果没有它，体验是否仍然成立？
- 它是否是当前 MVP 必须制作的？

## 后台指导原则

以下原则不作为日常开发主界面，但必须在后台约束所有设计:

- Why: 这个 Session 为什么存在。
- Transformation: 用户发生什么内在改变。
- Memory: 用户为什么之后还会记得。
- Validation: 如何判断体验成功。
- Medium: 用什么媒介帮助体验发生。

这些原则保留在 [Brand Philosophy](../../Brand_Philosophy.md) 和 [Project Rules](../../Project_Rules.md) 中。

## 当前 MVP

当前只开发 Session 01《重新开始》。

当前 Medium 是钢琴。

其他 Medium 与未来 Session 不进入当前开发，统一放入 [Parking Lot](../../Parking%20Lot（以后再做）/ParkingLot.md)。

## 关联文档

- [Session 01 - 重新开始](../Session%2001%20-%20重新开始/Session01_BeginAgain.md)
- [Products](../Products/Products.md)
- [Testing](../Testing/Testing.md)
- [Space Overview](../../Space/Space_Overview.md)
- [Brand Philosophy](../../Brand_Philosophy.md)
- [Project Rules](../../Project_Rules.md)

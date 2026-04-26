# Presentation

- 总计：4分40秒
<table border="1" style="margin: 0 auto;">
  <tr>
    <th style="text-align:center;">序号</th>
    <th style="text-align:center;">内容</th>
    <th style="text-align:center;">耗时/s</th>
    <th style="text-align:center;">完成情况</th>
  </tr>


  <tr>
    <td style="text-align:center;">1</td>
    <td style="text-align:center;"><a href="#开场白">开场白</a></td>
    <td style="text-align:center;">10</td>
    <td style="text-align:center;">已完成</td>
  </tr>
  <tr>
    <td style="text-align:center;">2</td>
    <td style="text-align:center;"><a href="#核心玩法演示">核心玩法演示</a></td>
    <td style="text-align:center;">90</td>
    <td style="text-align:center;">未完成</td>
  </tr>
  <tr>
    <td style="text-align:center;">3</td>
    <td style="text-align:center;"><a href="#其他玩法">其他玩法</a></td>
    <td style="text-align:center;">60</td>
    <td style="text-align:center;">未完成</td>
  </tr>
  <tr>
    <td style="text-align:center;">4</td>
    <td style="text-align:center;"><a href="#技术难点">技术难点</a></td>
    <td style="text-align:center;">90</td>
    <td style="text-align:center;">未完成</td>
  </tr>
  <tr>
    <td style="text-align:center;">5</td>
    <td style="text-align:center;"><a href="#迭代优化">迭代优化</a></td>
    <td style="text-align:center;">30</td>
    <td style="text-align:center;">未完成</td>
  </tr>
</table>

## 开场白

中文：
我们做的是一款基于“自我协作”的解谜游戏。

英文：
We made a puzzle game centered on self cooperation. 

## 核心玩法演示

- 直接进入第一关，不让老师做选择。
- 第一关是教学关卡，用来介绍录制与幻影合作的核心机制。
- 教学本身已经足够清晰，不需要额外讲解。
- 老师在做教学时，我们只需要轻微补充，不需要解释每一步。

## 其他玩法

- 介绍我们游戏的 **7 个核心机制**。
- 今天不会逐个展示，只需要告诉老师“我们有 7 个机制”即可。
- 原因：完整流程约 **1 小时**，而我们只有 **5 分钟**。


#### 强调 Puzzle Game 的本质（必须讲，但要短）
- Puzzle Game 的乐趣在于“思考”，不是快速通关。
- 如果老师很聪明，可能半小时就能通关；  
  但一般玩家平均需要 **1 小时**。
- 如果玩家不熟悉解谜游戏，可能会更久。
- 所以我们非常推荐老师之后自己完整体验，而不是只看 5 分钟的展示。

#### 强调“多解”设计（展示深度）
- 我们的关卡有不少 **多解**（多种解法）。
- 这些都是设计师的小巧思。
- 但今天没有时间让老师逐一体验。
---
我们需要运用录制回放这一核心机制，完成对应的 7 个游戏关卡。例如，其中 teleport 这一关（直接拉过来另一台电脑，提前准备好这一关的，指给老师说），就是充分运用核心机制与关卡机制来通关的；标题总结了关卡机制，“分身”也不受传送门使用状况的影响。

We need to use the core record-and-replay mechanic to finish the relevent 7-8 levels. For example, the teleport level fully shows how the core mechanic works together with this level-specific mechanics - use portal to other place. As title suggests, and the plantom - your 'Past Self', is not affected by whether the teleporters have already been used.



简单部分作为机制介绍，弄懂即可轻松过关，但困难部分就需要多动脑思考。但由于时间限制，我们无法一一展示。正常体验流程需要1-2小时。

Yeah, the easy part is relatively simple, mainly serve as an introduction to the mechanic, so once you understand it, they are quite easy to complete. However, The later levels, require more careful thinking and planning. Due to time limits, we can’t show all of them today. A full playthrough may typically take around one to two hours.



我们想强调的是，这个游戏本质上是一个 Puzzle Game，重点在于“思考”，你能够想出什么样的通关方式，主要考验游戏理解，策略规划，时机判断。这就需要玩家一边操作，一边规划路线，并开展头脑风暴——如何利用之前录下来的动作与当前角色形成配合。如果玩家理解很到位，组织很好，通关就比较容易；反之，可能会在同一地点长期卡关。

What we really want to highlight is that this game is essentially a puzzle game, focus on thinking. How you will solve problem depends on your understanding of the each level mechanics, your strategy, and your sense of timing. This need players to act while also planning ahead, constantly thinking about how to coordinate their current actions with the ones they previously recorded. If players have a good understanding and organize well, finishing the level is easy. Otherwise, they might get stuck in the same location for a long time.



此外，很多关卡是多解的，并非唯一。不同的录制顺序、不同的路线，甚至不同的协作思路，都可以成功通关。今天我们展示的只是一个很小的切面，更完整的乐趣还是需要玩家之后自己去体验。

What's more, many levels have lots of solutions rather than just one. Different recording orders, routes, and even collaboration strategies can all lead to success. What we are showing today is only a small snapshot. You need to explore the game on your own to truly experience all it has to offer.




## 技术难点

### 第一个技术难点：排行榜系统

#### 1. 开局登录流程
- 为了展示排行榜的完整功能，我们会先清空本地存储。
- 请老师以“游客模式”登录（无需注册，最快速）。
- 游客账号的成绩会保存在本地，并可随时转移到正式账号。

#### 2. 名字与改名机制
- 登录后需要输入一个名字。
- 名字可以随时修改，不会影响已上传的成绩。
- 改名后，排行榜会自动更新显示。

#### 3. 重名处理机制
- 排行榜允许玩家使用相同名字。
- 如果出现重名，系统会自动在名字后添加 `#数字`（例如：`Alex#1`、`Alex#2`）。
- 这样既保留玩家想用的名字，又避免记录冲突。

#### 4. 第一关结束后的展示流程
- 老师通关第一关后，会自动上传成绩到排行榜。
- 回到主页后，我们会展示排行榜的汇总界面：
  - 显示所有玩家的成绩排序。
  - 老师的成绩会高亮显示。
  - 戴皇冠的名字代表“注册账号”，游客账号没有皇冠。

#### 5. 账号绑定与数据转移
- 在排行榜旁边有“改名”“登录/注册”按钮。
- 如果老师愿意，可以将当前游客数据转移到正式账号。
- 系统会自动询问是否要把本地游客数据迁移到新账号中。

#### 6. 技术难点总结
- 需要处理本地存储与服务器数据同步。
- 需要解决重名冲突与自动编号规则。
- 实现成绩上传、排序、实时刷新。
- 需要支持游客账号与正式账号之间的数据迁移。
---
Our first technical challenge is the leaderboard system, you can see your game records after you clear each stage.

Our game also supports playing as either a registered player or a guest. We can see the difference in this small "crown". And these two account systems are fully separated. And the guest account can be updated to an official account at any time, with all game records being kept. Today we played as guests.

And our system allows players to use the same name. If there is a name conflict, the system will automatically add a hash number, so players can keep their preferred names while still avoiding conflicts

To implement these, we need to deal with synchronizing the data between the local storage and the server. And the name conflict and the automatic numbering for duplicate names. We also need to implement score uploading and real-time refreshing. Finally, we also managed to support the data migration between the guest account and the official account.

我们面临的首个技术挑战是排行榜系统，玩家在通关每个关卡后都能查看自己的游戏记录。

我们的游戏同时支持注册玩家和访客模式。通过这个小小的“皇冠”图标，可以区分这两种身份。这两种账号系统完全独立。访客账号可以随时升级为正式账号，所有游戏记录都会被保留。今天我们是以访客身份进行的游玩。

我们的系统允许玩家使用相同的昵称。如果出现昵称冲突，系统会自动添加一个哈希编号，这样玩家既能保留自己喜欢的昵称，又能避免冲突。

要实现这些功能，我们需要处理本地存储与服务器之间的数据同步，以及昵称冲突和重复昵称的自动编号问题。此外，我们还需要实现分数上传和实时刷新功能。最后，我们还成功实现了访客账号与正式账号之间的数据迁移。

---
### 第二个技术难点：关卡编辑器与共享

- 玩家可以创建自己的地图并上传到共享区。
- 技术难点主要在两点：
  1. **地图数据序列化与反序列化**  
     - 玩家编辑的地图需要转成数据格式上传  
     - 其他玩家下载后需要正确还原
  2. **兼容性与安全性**  
     - 地图必须保证不会破坏游戏逻辑  
     - 不能出现非法数据或崩溃情况

## 迭代优化

- 引入版本迭代
  - 打开选择过往游戏版本的界面，点开一个用来展现我们在整个开发周期中做出了大量的优化
---
在最后，我们想简单展示一下我们在整个开发周期中做过的迭代优化。
Finally, we want to briefly show the iteration and optimization process throughout our development.

我们准备了一个“版本选择界面”，可以看到从最早的 Demo 到现在的最终版本，我们经历了大量的功能扩展和性能优化。
We prepared a “version selection” interface, where you can see every major build from the earliest demo to the final release.

包括：录制系统的稳定性提升、碰撞系统的重构、UI 的重新设计、关卡机制的不断完善，以及排行榜和关卡编辑器等新功能的加入。
Across these versions, we made a large number of improvements — including stabilizing the recording system, rebuilding the collision engine, redesigning the UI, refining level mechanics, and adding major new features such as the leaderboard and the level editor.

通过对比不同版本，您可以很直观地看到我们是如何一步一步把游戏从一个原型，打磨成现在这个完整、稳定、可扩展的成品。
By comparing these versions side by side, you can clearly see how the game evolved step by step — from a rough prototype into a polished, stable, and fully expandable final product.

另外，我们在测试阶段收到很多玩家的反馈，说游戏的核心机制比较抽象，上手难度偏高，尤其是第一次接触录制与回放系统的玩家，会不知道该怎么开始。
During our testing phase, many players told us that the core mechanic felt abstract and the game was difficult to pick up, especially for those who were encountering the record‑and‑replay system for the first time and didn’t know how to get started.

针对这个问题，我们在最终版本中加入了 新手教学系统。这个功能显著降低了学习成本，也让第一次体验游戏的玩家能够更快进入状态。
To address this, we added a tutorial onboarding system in the final version. This significantly lowers the learning barrier and helps new players get into the game much more smoothly.
# -2048
### 功能说明

双人不同设备对战。对战形式为现时比赛，时间限制内可以任意步数，但如果一方棋盘进入死局，另一方可以在时间截止前继续进行操作。在常规2048游戏规则限制之外，还有额外的技能限制，主要是针对对方的技能，为负和博弈模式，技能使用有冷却时间以及费用。最终比赛的胜负由最终合成得分决定。

### 待实现技能

#### 软件本身

- [ ] 实现禁止用户操作的功能，主要用于释放技能等，注意预留接口
- [ ] 增加动态效果，实现方法为添加背景或者增加滑动遮罩
- [ ] 增加生成动态效果以及合成效果，初期考虑可以两次生成数字块实现
- [ ] 增加技能释放功能，注意与UI和网络部分协调接口

#### UI设计

- [ ] 增加对方棋盘缩略图，实时显示对方的棋盘状态（选择实现，如果决定实现注意预留接口）
- [ ] 增加技能按钮，先考虑3个技能，注意预留接口
- [ ] 释放技能效果，可先考虑冰冻效果

#### 网络部分

- [ ] 需要终局统计功能，计算两方的总得分，并给双方显示
- [ ] 需要技能信号传递功能，只需发送技能序号，本地自动识别序号后发动技能，注意接口
- [ ] 需要双方同步显示对方的棋盘内容，这部分需要棋盘状态、对方得分以及技能发动反馈

另有需求讨论后加上

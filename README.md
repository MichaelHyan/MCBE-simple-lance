# [add-on]长矛（超低配版）

对未来版本的拙劣模仿罢了（悲

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/laa.png)

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/lga.png)

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/lba.png)

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/lca.png)

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/lda.png)

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/lea.png)

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/lfa.png)

![](https://github.com/MichaelHyan/MCBE-simple-lance/blob/main/lancer/lha.png)

超低配版长矛，还原了普攻和人车功能

### 使用方式

下载lance.mcaddon并使用我的世界基岩版打开

适用于MCBE 1.18以上


长矛合成表与预告版本相同（矿石加两个木棍）

出于不会做长摁（悲），长矛使用双形态，使用交互键（鼠标右键）切换

普攻形态攻击范围比徒手稍大，范围伤害

人车形态分为三个伤害挡位

- 基础伤害：0<移动权值-上升速度<=5时触发（如走路跳跃），伤害最低
- 冲刺伤害：冲刺时触发，伤害稍高
- 坠落伤害：5<移动权值-上升速度时触发（自由落体），伤害最高

个人能力问题暂时没有设计耐久

p.s.目前原版不存在侦测走路速度的molang，仅有query.modified_move_speed(返回0-1的浮点数，表示是否输入移动指令)和query.vertical_speed(上升速度)，所以无法还原移速决定伤害，相对移动出伤等特性

（绿宝石长矛有彩蛋）
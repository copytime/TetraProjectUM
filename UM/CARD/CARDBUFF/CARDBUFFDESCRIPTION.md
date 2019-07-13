
%重写 buff 卡牌描述 description

；2019/5/13 上午 8:24:05
#描述
卡牌 description 是卡牌的描述，**会显示在游戏中**。
如果此格留空的话，卡牌描述会由游戏自动生成。
详情可参考 `Database 详解-Card-description`。
[Card-description](../../../DATEBASE/CARD/CARD-DESCRIPTION.html)
#操作
1、双击 `description` 表头列最后一行，输入自定义的 buff 描述。
#结果
在本例中，我们希望有一个简单明了的 buff 描述。
在此格输入 `每回合可以回复 1 HP;{credit:'就让时间来治愈一切吧~'}` 。
结果应该是这个样子：
![](cardbuffdescription~/Images~/CARDBUFFDESCRIPTION.png)

<1.5>上一步[填写卡牌 tagCode](CARDBUFFTAGCODE.html)
<1.5>下一步[编写 buff 卡牌指令 code](CARDBUFFCODE.html)
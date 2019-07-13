
%编写 buff 卡牌指令 code

；2019/5/13 上午 8:30:00
#描述
buff 卡牌指令 code 是 buff 的效果
详情可参考 `Database 详解-Card-code`，`原石计划code文档`。
[Card-code](../../../DATEBASE/CARD/CARD-CODE.html)
#操作
1、 双击 `code` 表头列最后一行，输入指令。
#结果
在本例中，卡牌效果为：每回合开始时回复 1 点 HP。
指令如下：
	evt.StartTurn:{Heal:1}
结果应该是这个样子：
![](cardbuffcode~/Images~/CARDBUFFCODE.png)


<1.5>上一步[重写 buff 卡牌描述 description](CARDBUFFDESCRIPTION.html)
<1.5>下一步[设定 buff 卡牌背景图片 backgroundId](CARDBUFFBACKGROUND.html)
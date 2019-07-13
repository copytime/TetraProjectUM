%编写装备卡牌指令 code

；2019/5/13 上午 8:30:00
#描述
装备卡牌指令 code 是装备的效果
详情可参考 `Database 详解-Card-code`，`原石计划code文档`。
[Card-code](../../../DATEBASE/CARD/CARD-CODE.html)
#操作
1、 双击 `code` 表头列最后一行，输入指令。
#结果
在本例中，卡牌效果为：无法叠加所有好 buff，减少运气 20%。
指令如下：
	evt.PreAddBuff:{If:{ArgCardHasTag:PosiBuff},{CreaserAvoidNext:AddBuff}};DecreaseChanceValue:20%;Equipment:
结果应该是这个样子：
![](cardeqmcode~/Images~/CARDEQMCODE.png)
<1.5>上一步[重写装备卡牌描述 description](CARDEQMDESCRIPTION.html)
<1.5>下一步[设定装备卡牌背景图片 backgroundId](CARDEQMBACKGROUNDID.html)
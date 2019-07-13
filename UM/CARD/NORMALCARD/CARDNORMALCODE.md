
%编写卡牌指令 code

；2019/5/11 下午 4:46:04

#描述
卡牌指令 code 是卡牌的效果
详情可参考 `Database 详解-Card-code`，`原石计划code文档`。
[Card-code](../../../DATEBASE/CARD/CARD-CODE.html)
#操作
1、 双击 `code` 表头列最后一行，输入指令。
#结果
在本例中，卡牌效果为：如果这个卡牌的目标是队友的话，给队友回复 1 点 HP，如果是敌人的话，给敌人造成 1 点伤害。
指令如下：
	If:{tgt.IsSameTeamWith:$user},{Heal:1},{TakeDamage:1}
结果应该是这个样子：
![结果](cardnormalcode~/Images~/CARDNORMALCODE1.png)
<1.5>[上一步设定卡牌最佳目标 perferredTargetTypeCode](CARDNORMALPERFERREDTARGETTYPECODE.html)
<1.5>[下一步设定卡牌背景图片 backgroundId](CARDNORMALBACKGROUNDID.html)
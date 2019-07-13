
%总览制作一张装备卡牌


#总览
在本例中，卡牌表格如下：
## excel-Card 表格
｜          表头          ｜                         值                         ｜
｜:----------------------:｜:--------------------------------------------------:｜
｜           id           ｜                        124                         ｜
｜      displayName       ｜                      恶魔诅咒                      ｜
｜         price          ｜                        -30                         ｜
｜      aimTypeCode       ｜                     SingleOnly                     ｜
｜perferredTargetTypeCode ｜                        self                        ｜
｜        tagCode         ｜                     Equipment                      ｜
｜          description          ｜在恶魔的诅咒下，运气值减少20%，并且无法叠加好 buff｜
｜      code       ｜   evt.PreAddBuff:{If:{ArgCardHasTag:PosiBuff},{CreaserAvoidNext:AddBuff}};DecreaseChanceValue:20%;Equipment:              ｜
｜      backgroundId      ｜                         4                          ｜

#测试
1、保存 Excel 表格。
2、修改 Cardset 子列表，让这张装备卡出现在 `原石加工器`。
![](cardeqmsummary~/Images~/CARDEQMSUMMARY1.png)
详情可参考 `Database 详解-Cardset`。
[Cardset 子列表](../../../DATEBASE/CARDSET/_CARDSET.html)
#结果
在本例中，结果应该是这个样子：
![](cardeqmsummary~/Images~/CARDEQMSUMMARY2.png)
点击可查看装备详情：
![](cardeqmsummary~/Images~/CARDEQMSUMMARY3.png)
装备详情如下：
![](cardeqmsummary~/Images~/CARDEQMSUMMARY4.png)
<1.5>上一步[测试卡牌](CARDET.html)
<1.5>[回到卡牌（Card）快速教程](../_CARD.html)


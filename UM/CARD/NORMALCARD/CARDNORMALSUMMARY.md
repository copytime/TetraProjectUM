
%总览制作一张普通卡牌

；2019/5/11 下午 5:00:20

#总览
在本例中，卡牌表格如下：
## excel-Card 表格
｜          表头          ｜                          值                          ｜
｜:----------------------:｜:----------------------------------------------------:｜
｜           id           ｜                         122                          ｜
｜      displayName       ｜                       自动处理                       ｜
｜         price          ｜                          10                          ｜
｜         energy         ｜                          1                           ｜
｜         range          ｜                          3                           ｜
｜      spreadRadius      ｜                          1                           ｜
｜      aimTypeCode       ｜               SingleOnly;NotAllowSelf                ｜
｜perferredTargetTypeCode ｜                       tmt;emy                        ｜
｜          code          ｜If:{tgt.IsSameTeamWith:$user},{Heal:1},{TakeDamage:1} ｜
｜      backgroundId      ｜                          2                           ｜
｜       effectCode       ｜                          6                           ｜

#测试
1、保存 Excel 表格。
2、选定当前卡牌所在行，并点击 `Alt + 4` 。
3、切回游戏中。
详情可参考 `Database 详解-附录-测试宏`。
[测试宏](../../../DATEBASE/VBA/_VBA.html)
#结果
在本例中，结果应该是这个样子：
![结果](cardnormalsummary~/Images~/CARDNORMALSUMMARY1.png)
<1.5>[上一步测试卡牌](CARDNORMALTEST.html)
<1.5>[回到卡牌（Card）快速教程](../_CARD.html)

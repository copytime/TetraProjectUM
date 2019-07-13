
%Card-perferredTargetTypeCode

；2019/5/13 下午 5:45:41
#描述
卡牌的首选目标，这会影响 AI 的运作。
#可用选项
+ 保持空
+ vis 可见的
+ visible 可见的
+ player 玩家可控制的
+ self 自己
+ emy 敌人
+ enemy 敌人
+ tmt 队友
+ teammate 队友
+ team 包括自己在内的整个队伍
+ lowHpP 低血量目标
+ lowestHpPercent 低血量目标
+ lowStaP 低体力目标
+ lowestStaminaPercent 低体力目标
+ died 已经死亡的目标
+ liv 还活着的目标
+ living 还活着的目标
+ cls 最近的目标
+ closest 最近的目标
+ rnd 随机目标
+ random 随即目标



region w { 注意
可以同时选用多个，之间用分号隔开。
} region

#示例
修改怪物卡牌的最佳瞄准目标为队友，让怪物自相残杀。
修改 id 为 82 号的喷射毒液的 `perferredTargetTypeCode` 表头列为 `tmt`。
![](card-perferredtargettypecode~/Images~/CARDPTTCSAMPLE1.png)
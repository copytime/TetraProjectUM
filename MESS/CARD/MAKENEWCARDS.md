
%新建一张普通卡牌

；2019/5/16 下午 10:27:19
#新建一张普通卡牌
所有卡牌的数据都在 `Database` 中的 `Card` 子列表中保存着，其中每一行都是一张卡牌。
我们想要新增一张卡牌，只需要新建一行即可。
region w {注意
新建的卡牌 id 不要和已有的 id 重复。
}
原理上来讲，此时这张卡已经可以被游戏内读取了，但是由于它既没有名字也没有任何指令代码，所以没有任何功能。
接下来是对这张新卡牌做数据和功能上的设定。
我们选一个例子作为教程的卡牌。
[
+ 新卡牌名字叫 `自动处理`
+ 新卡牌在 `原石加工器` 中的价格为 10
+ 新卡牌使用需要消耗 1 点能量
+ 新卡牌的使用范围（射程）为 5 格
+ 新卡牌没有 aoe 效果，只对单体有效
+ 新卡牌的目标是玩家或敌人
+ 新卡牌的最佳使用对象是玩家或敌人
+ 新卡牌的效果是：如果目标是敌人就造成 1 点伤害；是队友则回复 1 HP
+ 新卡牌使用黄色背景
]
我们采用从左至右的顺序，依次填写新建的这一行的各个列。
##第一列：id
id 就好像卡牌的专属身份证，游戏内的很多指令都会根据这个 id 来寻找对应卡牌。
**所以 id 不能和其他卡牌的 id 重复。**
这里请根据实际情况选择一个 id。
<1.5>后续内容因开发重点改变而暂时搁置，请谅解！
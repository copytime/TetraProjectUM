
%Cardset-characterId

；2019/5/14 下午 3:03:34

#描述
卡组角色 id。
只有存在这个角色的时候，这一行的卡牌才能出现在 `原石加工器` 里面。
#可用选项
+ Shared 任何角色都可以出现的卡牌
+ 所有 `Character 子列表` 中的 id
详情可参考 `Database 详解-Character-id`。
[Character-id](../CHARACTER/CHARACTER-ID.html)
#示例
如图：
![](cardset-characterid~/Images~/CARDSETCHARACTERIDSAMPLE1.png)
<br/>
红莲对应卡牌	--	燃烧炸弹
贝瑞对应卡牌	--	制冷
Shared 任意角色	--	孤注一掷
在游戏中我们使用 `红莲-费里克` 组合。
结果：
![](cardset-characterid~/Images~/CARDSETCHARACTERIDSAMPLE2.png)
由于有 `红莲` 角色存在，所以 `原石加工器` 刷新出来了 `燃烧炸弹`；
由于没有 `贝瑞` 角色存在，所以 `原石加工器` 不会出现 `制冷`；
由于 `Shared` 存在，所以无论我们选择哪一个角色组合，`孤注一掷` 都会出现。


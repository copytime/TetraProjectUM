
%Quote 和 qte

；2019/5/16 上午 9:10:52


[ 导航链接列表

/*Nav*/

]
# Quote 和 qte 指令

##描述
`qte` 为 `Quote` 指令的缩写，两者作用一致。
在卡牌描述右侧生成一张小卡，用于显示 `quoteDescription` 中的内容。
##参数



｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 字符串 ｜   否   ｜小卡的标题 ｜


##示例
### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试名字   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:  ｜
｜   …略…   ｜    ｜

### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  朋友听说过{qte:丽莎的记忆}嘛？  ｜
｜    quoteDescription    ｜  是Alive制作的一款独立游戏哦  ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](quote~/Images~/QUOTESAMPLE1.png)

<br/>
> *技巧：* 可以使用小卡对一些名词进行补充说明。


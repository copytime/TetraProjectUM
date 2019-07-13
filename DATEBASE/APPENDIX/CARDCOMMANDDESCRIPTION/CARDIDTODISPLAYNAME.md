
%CardIdToDisplayName 和 cn

；2019/5/16 上午 8:01:16

[ 导航链接列表

/*Nav*/

]
# CardIdToDisplayName 和 cn 指令

##描述
`cn` 为 `CardIdToDisplayName` 指令的缩写，两者作用一致。
把卡牌 id 换成卡牌的名字。
##参数



｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 从 Card 列表传递 ｜   否   ｜卡牌的 id ｜


##示例
### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试名字   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:150  ｜
｜   …略…   ｜    ｜

### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  id为{0}的卡牌名字是{cn:0}  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](cardidtodisplayname~/Images~/CITDNSAMPLE1.png)


##注意
指令组的参数要从 `Card 子列表` 的 `code` 列传递。
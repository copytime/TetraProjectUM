
%CharacterIdToDisplayName 和 cha

；2019/5/16 上午 8:31:28


[ 导航链接列表

/*Nav*/

]
# CharacterIdToDisplayName 和 cha 指令

##描述
`cha` 为 `CharacterIdToDisplayName` 指令的缩写，两者作用一致。
把角色 id 换成角色的名字。
##参数



｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 从 Card 列表传递 ｜   否   ｜角色的 id ｜


##示例
### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试名字   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:3  ｜
｜   …略…   ｜    ｜

### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  id为{0}的角色名字是{cha:0}  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](characteridtodisplayname~/Images~/CITDNSAMPLE1.png)

##注意
指令组的参数要从 `Card 子列表` 的 `code` 列传递。
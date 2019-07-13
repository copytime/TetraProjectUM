
%CardCommandIdToDescription 和 cmd

；2019/5/16 上午 8:34:16


[ 导航链接列表

/*Nav*/

]
# CardCommandIdToDescription 和 cmd 指令

##描述
`cmd` 为 `CardCommandIdToDescription` 指令的缩写，两者作用一致。
把指令组 id 换成指令组的描述。
##参数



｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 从 Card 列表传递 ｜   否   ｜卡牌的 id ｜


##示例
###示例一：
#### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试名字   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:MyCmdGroup  ｜
｜   …略…   ｜    ｜

#### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  id为{0}的指令组的描述是{cmd:0}  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](cardcommandidtodescription~/Images~/CCITDSAMPLE2.png)

###示例二：
#### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试名字   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:visClsLivTmt  ｜
｜   …略…   ｜    ｜

#### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  id为{0}的指令组的描述是{cmd:0}  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](cardcommandidtodescription~/Images~/CCITDSAMPLE1.png)

##注意
指令组的参数要从 `Card 子列表` 的 `code` 列传递。
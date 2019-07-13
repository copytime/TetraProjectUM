
%QuoteRemapCode 和 qteRmp

；2019/5/16 上午 9:23:20

[ 导航链接列表

/*Nav*/

]
# QuoteRemapCode 和 qteRmp 指令

##描述
`qteRmp` 为 `QuoteRemapCode` 指令的缩写，两者作用一致。
在卡牌描述右侧生成一张卡牌，用于显示根据 `remapCode` 自动生成的描述文字。
##参数



｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 字符串 ｜   否   ｜生成的卡牌的标题｜


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
｜description ｜  吃我一{qteRmp:拳}！ ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜  TakeDamage:3  ｜
｜   …略…   ｜    ｜
结果
![](quoteremapcode~/Images~/QUOTEREMAPCODESAMPLE1.png)





%optionalArg，opt 和 optN

；2019/5/16 上午 8:49:41


[ 导航链接列表

/*Nav*/

]
# optionalArg 和 opt 指令

##描述
`opt` 为 `optionalArg` 指令的缩写，两者作用一致。
如果有这个参数，就添加对应文字。
##参数



｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 判断的参数 ｜   否   ｜如果有这个参数就添加对应文字 ｜
｜2 ｜ 字符串 ｜   否   ｜要添加的描述文字 ｜



##示例
###示例一：
#### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试卡牌   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:'冰激凌'  ｜
｜   …略…   ｜    ｜

#### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  我{opt:1,'不'}要吃{0}  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](optionalarg~/Images~/OPTIONALARGSAMPLE1.png)
###示例二：
#### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试卡牌   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:'冰激凌','随便再传一个参数'  ｜
｜   …略…   ｜    ｜

#### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  我{opt:1,'不'}要吃{0}  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](optionalarg~/Images~/OPTIONALARGSAMPLE2.png)
##注意
指令组的参数要从 `Card 子列表` 的 `code` 列传递。








# optN 指令

##描述
如果没有这个参数，就添加对应文字
##参数

｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 判断的参数 ｜   否   ｜如果无这个参数就添加对应文字 ｜
｜2 ｜ 字符串 ｜   否   ｜要添加的描述文字 ｜
##示例
###示例一：
#### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试卡牌   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:  ｜
｜   …略…   ｜    ｜

#### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  {optN:0,'不给糖'}{optN:1,'就捣蛋'}   ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](optionalarg~/Images~/OPTIONALARGSAMPLE3.png)
###示例二：
#### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试卡牌   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:'随便传一个参数'  ｜
｜   …略…   ｜    ｜

#### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  {optN:0,'不给糖'}{optN:1,'就捣蛋'}  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](optionalarg~/Images~/OPTIONALARGSAMPLE4.png)


##注意
指令组的参数要从 `Card 子列表` 的 `code` 列传递。
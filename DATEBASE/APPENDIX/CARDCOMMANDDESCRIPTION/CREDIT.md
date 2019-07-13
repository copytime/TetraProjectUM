
%credit

；2019/5/16 上午 9:30:10


[ 导航链接列表

/*Nav*/

]
# credit 指令

##描述
把文字变成卡牌底部灰色小字。
**本来是用来写赞助者文字的，却被拿来写吐槽了。**
##参数

｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 字符串 ｜   否   ｜赞助者文字(或吐槽的话) ｜


##示例
### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ Alive   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:  ｜
｜   …略…   ｜    ｜

### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  会音乐  会画画  还会写代码 {credit:此卡由Alive独家赞助} ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](credit~/Images~/CREDITSAMPLE1.png)


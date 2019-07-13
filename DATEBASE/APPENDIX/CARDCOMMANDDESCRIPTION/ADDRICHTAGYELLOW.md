
%AddRichTagYellow，yellow 和 ylw

；2019/5/16 上午 8:41:29


[ 导航链接列表

/*Nav*/

]
# AddRichTagYellow，yellow 和 ylw 指令

##描述
`yle`，`yellow` 为 `AddRichTagYellow` 指令的缩写，三者作用一致。
让文字变黄。
##参数



｜序号｜ 参数 ｜是否可选｜          描述  ｜
｜:--:｜:----:｜:------:｜:--------:｜
｜1  ｜ 字符串 ｜   否   ｜需要变黄的文字 ｜


##示例
### excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试文字高亮   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:  ｜
｜   …略…   ｜    ｜

### excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  我怀疑你搞{ylw:黄色}，但是我又没有证据  ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果
![](addrichtagyellow~/Images~/ARTYSAMPLE1.png)

##注意
如果直接使用指令组传递的参数，则会自动加上黄色高亮。
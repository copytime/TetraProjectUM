
%参数

；2019/5/16 上午 8:16:47
#描述
`CardCommand 子列表` 的 `description` 可以获取到传给指令组的参数。
region w { 注意
最多可以获取四个参数
}
#示例
要想在 `description` 或 `quoteDescription` 中使用传给指令组的参数，需要通过 `{ }` 来获取。
## excel-Card 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜ 150(请根据实际情况填写)  ｜
｜displayName ｜ 测试参数   ｜
｜   …略…   ｜    ｜
｜    code    ｜  MyCmdGroup:'你','好','世','界'  ｜
｜   …略…   ｜    ｜

## excel-CardCommand 表格
｜    表头    ｜ 值 ｜
｜:----------:｜:--:｜
｜     id     ｜  MyCmdGroup  ｜
｜description ｜  第一个参数是{0};第二个参数是{1}; 第三个参数是{2}; 第四个参数是{3};   ｜
｜    quoteDescription    ｜    ｜
｜   …略…   ｜    ｜
｜ remapCode  ｜    ｜
｜   …略…   ｜    ｜
结果:
![](args~/Images~/ARGSSAMPLE1.png)


#注意
指令组的参数要从 `Card 子列表` 的 `code` 列传递。
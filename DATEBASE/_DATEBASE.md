
%Database 详解

；2019/5/11 上午 11:52:11


[ 导航链接列表

/*Nav*/

]

#描述
**原石计划** 采用了 Excel 表格作为数据结构，方便对各项数值和设定进行更改。
内置的 `Database.xls` 文件存放于
`游戏根目录\TetraProject_Data\StreamingAssets\Packages\Builtin\Database`
本文主要就是对此文件的结构组成进行的详细解读。

##子表格
`Database.xls` 共包含了 11 个子表格。如图：
![DatabaseSummary](_datebase~/Images~/DATABASESUMMARY.png)

|子表格名称|详细介绍|
|：-：|：-：|
|  Character   |   用于存放游戏内所有角色的信息，包括玩家角色，敌对角色，陷阱角色和中立角色   |
|  Card   |   用于存放游戏内所有卡牌的信息，包括普通卡牌，buff 卡牌，装备卡牌和特殊卡牌   |
|  CardCommand  |   用于存放卡牌指令组，也存放了描述重写和特效重写   |
|  Cardset  |   用于存放牌组流派   |
|  Stage  |   用于存放关卡信息，包括怪物种类   |
|  Effect  |   用于存放特效信息   |
|  Sound  |   用于存放音效信息  |
|  Music  |   用于存放音乐信息  |
|  Tester  |   只是拿来测试用的  |
|  Devlog  |   开发记录  |
|  ExcelConfig  |   用于存放表格的一些配置信息  |

；TODO： 研究 Cardset 和 Tester





/*SubLinksList*/




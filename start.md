# 创建行为包
本教程将教你如何创建行为包，在此之前，我建议你先学习一下如何制作资源包，因为这个教程很多方面涉及资源包．

## 所需时间
认真读完本教程大概需要１个小时，当然能否学会就是另一回事了XD

## 工具
＇工欲善其事必先利其器＇,选择一个适合自己的工具很重要．

笔者在Linux下完成这篇教程，所以我使用：
* Atom
* SublimeText

## JSON教程
你最好了解一下JSON的语法结构．好吧，这其实非常重要．如果你先前对JSON有深入研究，你可以跳过这一部分．

### JSON语法
JSON 语法是 JavaScript 对象表示语法的子集。
* 数据在名称/对象中
* 数据由逗号分隔
* 大括号保存对象
* 中括号保存数组

### JSON名称/值对
JSON 数据的书写格式是：名称/值对。
名称/值对包括字段名称（在双引号中），后面写一个冒号，然后是值：

`"name":"CAIMEO"`

等价于这条JS语句(如果你没学过JS,可以忽略这个，但我还是建议你看一看)：

`name = "CAIMEO"`

### JSON 值
* 数字：整数或浮点数
* 字符串:""
* 逻辑值：true / false
* 数组:[]
* 对象:{}
* null

### JSON文件
JSON文件的文件类型是'.json'

### 检验工具
很多时候我们可能因为少些了个逗号，括号而导致json不工作，就像Java的分号一样，很难看出来:(

幸好我们有一些工具来帮助我们检验json的合法性
[Bejson](https://www.bejson.com)

它会告诉你哪里出错了
## 开始
大部分抄袭自官方文档:)

我们先拿一份行为包：
`wget https://aka.ms/behaviorpacktemplate`

解压缩，列出目录，目录[点这里](addonslist.md)

我们先说说文件根目录的几个文件
- 
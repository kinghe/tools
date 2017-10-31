# tools
个人工具集(Personal Tool Set)
## note
模式：
1. 普通common模式 
+ 仅仅提供简单的查看，搜索，编辑功能

2. 表table/块block模式
+ 数据信息被划分为二维(或者更多维)数组，可以参照awk行段的划分方式，因此选择此模式时，需要先行选择划分模式.
+ 显示采用电子表格的方式。光标位置是行段值
+ 用户介入操作：可以逐个单元格进行编辑，也可以选择awk方式(提供二个窗体，一个显示规则，类似awk脚本，一个显示变更后的信息，用于和原文的比较)

3. 代码code模式 文本内数据可以划分若干单元，所有单元可以以树结构相互关联
+ 类似的文件有诸如c/java/python/javascript等编程语言代码,html/css/xml/json等结构化数据存储文件
+ 提供数据行折叠功能
+ 光标位置，树结构位置显示
+ 提供语法着色
+ 提供多个窗体，用于显示诸如关联代码，代码补全提示，代码doc等
+ 可以绑定代码的编译/运行工具

4. 章chapters节sections模式 即文章阅读模式
+ 提供章节索引窗体
+ 光标位置，所在章节信息，章节内进度(如百分比，已读/总行列数),用户可以根据喜欢自定义。
+ 提供书签功能，用于记录阅读感悟，纠错/补充
+ tts语音朗读功能？

5. bin模式 即非文本文件的阅读，用户必须提供此类文件的解析方法，将文件映射至上述三种模式中。
+ 具体功能需要，还没有想清楚，占个位置先

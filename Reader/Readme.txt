对程序某些功能的说明

一、主界面
    可以使用鼠标拖拽的方式对块的排列进行整理，默认的是位置交换操作(以网格线提示)，按住shfit键进行拖拽的话将执行插入操作（以竖线提示）
二、阅读界面
    (1)窗口上方的紫色方块是用来标明该文件被分成了多少个块，并且用黑色小方块来标明当前所在块。程序中块的大小被定义为400KB，也就是说，如果文件大小为1000KB，将会显示3个方块(400+400+200)。可以通过单击方块来直接跳转到文件的某个部分。也可以通过点击"<<"">>"按钮来进入上一个或者下一个文件块。现在还是将它作为一个污点的存在，所以没有进行美化。
    (2)进度显示并不准确，只能供参考。
    (3)书签功能暂不提供，当前存储文件格式混乱，得整理好在添加。
    (4)程序能够自动存储当前阅读位置，该位置是指当前页面的第一行的第一个字符。注意只有当程序正常关闭后，当前阅读位置才会更新到存储文件中。也可以通过直接修改存储文件来修改当前阅读位置。
三、程序设置
    已经尽可能多的提供自定义设置选项。但是现在还只支持以bmp格式的图片作为背景，不能调整文字间距，汉字和英文的字体未能分开设置。
三、存储文件
    (1)InformationOfFiles.txt 记录文件信息

---------------------------->|【"-->|"为标识符，表明下面是一个文件的信息】
9001.txt【文件名】
C:\Users\Administrator\Desktop\Reader\9001.txt【文件路径】
0 0【当前阅读位置，第一个数字是文件块的编号，从0开始算，第二个数字是阅读位置，从0开始算】
第一章 白狐 - 【预览信息】
(0,0)(0,0)(0,0)(0,0)(0,0)(0,0)(0,0)(0,0)(0,0)(0,0)【暂时无用，保持为0，共10组】
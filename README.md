# Ebbinghaus
在Mac上连接mysql，记录学习内容并且提醒复习

但是我这个目前没有**多线程**

使用了mysql并且，能够实时的输出在.xls文档上，输出文档在downloads里面

简单terminal**界面**

**注意** mysql必须多预留一列log*

---------------------------------------------------

在stage7_mysql这个版本中，更换了原来的xlwt，换成了openopyxl

因为在这个库中，可以无限次的设置每个Excel表格单元格大小

以及保存为.xlsx格式

原来的bug依然存在，就是在换月份的时候，因为计算时间的方式单一，所以，每个月都是按照30计算的

但是在不是30一个月的时候，就会出现复习内容错乱的情况，但是如果在一个月内就没有问题

**界面**依然是一个刚需，还有就是**移植性**,让他能够在Windows安装使用，而不是修改源代码。

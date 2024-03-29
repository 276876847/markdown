# markdown标记语言学习笔记

markdown作为一种轻量标记语言，具有语法简单能够快速的对文本进行简单排版，对于一些不需要很复杂排版格式的场景来说，很有应用价值。

初次接触原因：由于github上的文档格式都是md格式，基于对git的学习和使用，所以需要开始使用

其他应用场景：word作为一种二进制格式的文档，在git中无法很好的展示修改的内容，而txt文件，又由于是纯文本格式的软件（加上记事本本身在开头的编码方式中增加了16字节的起始片段，对有些代码的支持不友善），可读性和美观度不够，所以急需一种待标记的文本语言

使用软件：Typora

1. 标题

   \# title1 标题1

   \#\# title2 标题2

   \#\#\# title3 标题3

   从上边可知，只要是第几层的标题，就在前面加上多少个#号就可，且#号和文本间需要有一个空格

2. 加粗

   \*\*需要加粗的文本内容\*\*

   注意：星号和文本间不能有空格

3. 斜体

   \*需要设置为协调的文本\*

   注意：星号和文本间不能有空格

4. 有序序列

   1. 序号1

   2. 序号2

      注意：点号后有一个空格

5. 无序序列

   \- 列表1

   \+ 列表2

   \* 列表3

   以上三个符号后跟上一个空格，都可以实现

6. 删除线

   \~\~需要删除的文本\~\~

   波浪线和文本间不能有空格

7. 超链接

   * 第一种方式

     借用html的标记标签： \<www.baidu.com\>

   * 第二种方式

     \[超链接的文本\]\(URL\)

8. 插入图片

   \!\[图片标题\]\(图片所在的URL\)

9. 插入表格

   单元格之间用|隔开

   \|标题1\|标题2\|

   \|-\|-\|-\|

   第二行是用来隔离标题和内容的，其中可以设置对齐方式

   \|:-\|:为左对齐

   |-:|:为右对齐

   |:-:|:为居中对齐

10. 引用

    \>引用的内容

    \>\>二级引用

    \>\>\>三级引用

    从上面可知，第几级引用，就在前面增加多少个\>

11. 增加横线标记

    \---

    \***

    \+++

    以上三个符号都可以增加横线分割符

12. 程序代码

    \```代码的语言

    代码主体部分

    \```

    里面的代码会有浅色底纹，且根据第一行中的语言，会对关键字高亮显示

13. 
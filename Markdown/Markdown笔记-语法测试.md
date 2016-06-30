==正文==
---
# 1. Markdown是什么？

**Markdown**是一种轻量级**标记语言**，它以纯文本形式(易读、易写、易更改)编写文档，并最终以HTML格式发布。
**Markdown**也可以理解为将以MARKDOWN语言编写的语言转换成HTML内容的工具，最初是一个perl脚本Markdown.pl。

# 2. 谁发明了这么个东西？
它由Aaron Swartz和John Gruber共同设计，Aaron Swartz就是那位于去年（2013年1月11日）自杀,有着开挂一般人生经历的程序员。维基百科对他的介绍是：软件工程师、作家、政治组织者、互联网活动家、维基百科人。

他有着足以让你跪拜的人生经历：

**14岁**参与RSS 1.0规格标准的制订。   
**2004**年入读斯坦福，之后退学。   
**2005**年创建Infogami，之后与Reddit合并成为其合伙人。   
**2010**年创立求进会（Demand Progress），积极参与禁止网络盗版法案（SOPA）活动，最终该提案居然被撤回。   
**2011**年7月19日，因被控从MIT和JSTOR下载480万篇学术论文并以免费形式上传于网络被捕。
2013年1月自杀身亡。

# 3. 为什么要使用它？

它是易读（看起开舒服）、易写（语法简单）、易更改纯文本。处处体现着极简主义的影子。
兼容HTML，可以转换为HTML格式发布。
跨平台使用。
越来越多的网站支持Markdown。
更方便清晰的组织你的电子邮件。（Markdown-here, Airmail）
摆脱Word（我不是认真的）。

# 4. 怎么使用？

如果不算扩展，Markdown的语法绝对简单到让你爱不释手。

废话太多，下面正文，Markdown语法主要分为如下几大部分： **标题，段落，区块引用，代码区块，强调，列表，分割线，链接，图片，反斜杠 \，符号'`'**。

4.1 标题
---------------
两种形式：   
1）使用`=`和`-`标记一级和二级标题。

>一级标题   
`=========`   
二级标题   
`---------` 

The results above show that: 

一级标题   
===
二级标题
---

2）使用#，可表示1-6级标题。

> \# 一级标题   
\## 二级标题   
\### 三级标题   
\#### 四级标题   
\##### 五级标题   
\###### 六级标题   

The results above show that:
> 
# 一级标题   
## 二级标题   
### 三级标题   
#### 四级标题   
##### 五级标题   
###### 六级标题  

4.2 段落
------------
段落的前后要有空行，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用两个以上空格加上回车（引用中换行省略回车）。

The results above show that:   
> 1.这一句后面有空格还有回车键  
2.这一句一定换行了  
3.这一句没换行
4.这一句应该跟着上一句后面  

4.3 区块引用
---------
在段落的每行或者只在第一行使用符号>,还可使用多个嵌套引用，如：

>\> 区块引用  
\>> 嵌套引用

The results above show that:
> 区块引用  
>> 嵌套引用

4.4 代码区块
-----
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如
普通段落：   
void main()  
{   
printf("Hello, Markdown.");   
}   

代码区块：  

    void main()
    {
    printf("Hello, Markdown.");
    }

注意:需要和普通段落之间存在空行。

4.5 强调
-------
在强调内容两侧分别加上*或者_，如：

*斜体*，_斜体_  
**粗体**，__粗体__  

4.6 列表
-----------
使用`·`、`+`、或`-`标记无序列表，如:
>-（+*） 第一项 -（+*） 第二项 - （+*）第三项   

**注意**：标记后面最少有一个空格或制表符。若不在引用区块中，必须和前方段落之间存在空行。

The results above show that:   
>- 第一项    
>- 第二项    
>- 第三项

有序列表的标记方式是将上述的符号换成数字,并辅以`.`，如：
The results above show that:   
>1. 第一句
>2. 第二句
>3. 第三句

4.7 分割线
---
分割线最常使用就是三个或以上`*`，还可以使用`-`和`_`。

The first   
\***   
The Second   
\---   
The Third   
\______   

**The results above show that:  ** 

The first
***
The Second
---
The Third
______

4.8 链接
---
链接可以由两种形式生成：行内式和参考式。
行内式：

>`[younghz的Markdown库](https:://github.com/younghz/Markdown "Markdown")。`

**The results above show that:  ** 

[younghz的Markdown库](https:://github.com/younghz/Markdown "Markdown")。

参考式：

>`[younghz的Markdown库1][1]     
[younghz的Markdown库2][2]
[1]:https:://github.com/younghz/Markdown "Markdown"
[2]:https:://github.com/younghz/Markdown "Markdown"`

**The results above show that:  ** 

[younghz的Markdown库1][1]   
[younghz的Markdown库2][2]

[1]:https:://github.com/younghz/Markdown "Markdown"
[2]:https:://github.com/younghz/Markdown "Markdown"


注意：上述的
```
[1]:https:://github.com/younghz/Markdown "Markdown"
```
不出现在区块中。

4.9 图片
----
添加图片的形式和链接相似，只需在链接的基础上前方加一个`！`。   
>`![image](https://github.com/1plusc/Resource/blob/master/img/forexample.jpg?raw=true) `

**The results above show that:  ** 

![image](https://github.com/1plusc/Resource/blob/master/img/forexample.jpg?raw=true)  

4.10 反斜杠`\`
---
相当于反转义作用。使符号成为普通符号。   

4.11 符号'`'
---
起到标记作用。如：   
>\`ctrl+a`

**The results above show that:  ** 

>`ctrl+a`

# 5. 都谁在用？
---
Markdown的使用者：

GitHub   
简书   
Stack Overflow   
Apollo   
Moodle   

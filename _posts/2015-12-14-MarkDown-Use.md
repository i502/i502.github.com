#MarkDown的使用

##一.标题设置
在MarkDown中设置标题有两种形式

* 通过在文字下方添加“=”和“-”，他们分别表示一级标题和二级标题

1. 例子

    这是一级标题（'==='）
    ===========

    这是二级标题（'---'）
    -----------

* 在文字开关加上“#” 号，通过"#"数量表示几级标题（一共只有6级标题，1级标题最大）

2. 例子

    #一级标题('#')
   
    ##二级标题('##')
    
    ###三级标题('###')

##二、块注释(blockquote)

  通过在文字开头添加'>'表示快注释
    
##三、斜体
将需要设置为斜体的文字两端使用1个“*”或者“_”夹起来

##四、粗体
将需要设置为斜体的文字两端使用2个“*”或者“_”夹起来

##五、无序列表
在文字开头添加(*, +, and -)实现无序列表。但是要注意在(*, +, and -)和文字之间需要添加空格。（建议：一个文档中只是用一种无序列表的表示方式）

##六、链接
使用数字后面跟上句号。（还要有空格）
##七、链接
Markdown中有两种方式，实现链接，分别为内联方式和引用方式。
<pre>
内联方式：This is an [example link](http://example.com/).
引用方式：
I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3].  

[1]: http://google.com/        "Google" 
[2]: http://search.yahoo.com/  "Yahoo Search" 
[3]: http://search.msn.com/    "MSN Search"
</pre>
 [link](http://www.baidu.com)
 

##八、图片
图片的处理方式和链接的处理方式，非常的类似。
内联方式：![alt text](/path/to/img.jpg "Title")
引用方式：
![alt text][id] 

[id]: /path/to/img.jpg "Title"

![孕照片](http://pic.818today.com/imgsy/image/201511/17_104232yu.jpg "高高的")


##九、代码
实现方式有两种：
第一种：简单文字出现一个代码框。使用`<blockquote>`。（`不是单引号而是左上角的ESC下面~中的`）
第二种：大片文字需要实现代码框。使用Tab和四个空格。


##十、脚注

实现方式如下：
<pre>
hello[^hello]


[^hello]: hi
</pre>


##十一、下划线
在空白行下方添加三条“-”横线。（前面讲过在文字下方添加“-”，实现的2级标题）

* 世界人的佳能
* 加油

*斜体测试测试*

**粗体测试**

hello[^hello]

[^hello]: hi

`<blockquote>`

1. dddd
2. sssfa
3. sfasdfasdf
4. [link](http://www.baidu.com)
5. ![孕照片](http://pic.818today.com/imgsy/image/201511/17_104232yu.jpg "高高的")


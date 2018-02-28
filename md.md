[Toc]  
[Overview](#overview)
[Philosophy](#philosophy)
[huhuxxx](#huhu)
[huhuxxx](#huhu)
[huhuxxx](#huhu)

# 兼容 HTML #

这是一个普通段落。

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

这是另一个普通段落。




# 锚点 #

*   [Overview](#overview)
    *   [Philosophy](#philosophy)
        * [huhuxxx](#huhu)
        * [huhuxxx](#huhu)
        * [huhuxxx](#huhu)

# 特殊字符自动转换 #

4 < 5

4 &lt; 5


# 段落和换行 #

This is an H1
=============

This is an H2
-------------

# 这是 H1

## 这是 H2

###### 这是 H6
# 这是 H1 #
## 这是 H2 ##
### 这是 H3  ###
XXX
==
# 区块引用 Blockquotes

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.


> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");


# 列表
*   Red
*   Green
*   Blue

+   Red
+   Green
+   Blue

-   Red
-   Green
-   Blue

1.  Bird
2.  McHale
3.  Parish

<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>


1.  Bird
1.  McHale
1.  Parish

3. Bird
1. McHale
8. Parish


*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.


*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.

*   Bird
*   Magic


<ul>
<li>Bird</li>
<li>Magic</li>
</ul>

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.


*   This is a list item with two paragraphs.

    This is the second paragraph in the list item. You're
only required to indent the first line. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit.

*   Another item in the same list.


*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.


*   一列表项包含一个列表区块： 

        <代码写在这>

1986. What a great season.

1986\. What a great season.

# 代码区块

这是一个普通段落：

    这是一个代码区块。

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell


    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

<div class="footer">
    &copy; 2004 Foo Corporation
</div>

## 分隔线

* * *

***

*****

- - -

---------------------------------------

# 区段元素
## 链接
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

See my [About](/about/) page for details.

This is [an example][id] reference-style link.

This is [an example] [id] reference-style link.

[id]: http://example.com/  "Optional Title Here"


链接内容定义的形式为：

方括号（前面可以选择性地加上至多三个空格来缩进），里面输入链接文字
* 接着一个冒号
* 接着一个以上的空格或制表符
* 接着链接的网址
* 选择性地接着 title 内容，可以用单引号、双引号或是括弧包着

下面这三种链接的定义都是相同：
[foo]: http://example.com/  "Optional Title Here"
[foo]: http://example.com/  'Optional Title Here'
[foo]: http://example.com/  (Optional Title Here)

[id]: http://example.com/longish/path/to/resource/here
    "Optional Title Here"


[Google]: http://google.com/
Visit [Daring Fireball][] for more information.

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].
  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].
  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"


  # 强调
  *single asterisks*

_single underscores_

**double asterisks**

__double underscores__

<em>single asterisks</em>

<em>single underscores</em>

<strong>double asterisks</strong>

<strong>double underscores</strong>


un*frigging*believable

\*this text is surrounded by literal asterisks\*

## 代码

Use the `printf()` function.

``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

Please don't use any `<blink>` tags.

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

## 图片

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")

详细叙述如下：

* 一个惊叹号 !
* 接着一个方括号，里面放上图片的替代文字
* 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上 选择性的 'title' 文字。

参考式的图片语法则长得像这样：

![Alt text][id]

[id]: url/to/image  "Optional title attribute"


## 自动链接

<http://example.com/>

<a href="http://example.com/">http://example.com/</a>

<address@example.com>

## 反斜杠

\*literal asterisks\*

\   反斜线

`   反引号

*   星号

_   底线

{}  花括号

[]  方括号

()  括弧

#   井字号

+   加号

-   减号

.   英文句点

!   惊叹号




<h2 id="overview">Overview</h2>

#### Philosophy 

huhu
------



# 左边框目录

[Toc] 

* [Overview](#overview)
    * [Philosophy](#philosophy)
    * [huhuxxx](#huhu)
    * [huhuxxx](#huhu)
    * [huhuxxx](#huhu)


> 这是一级引用
>>这是二级引用
>>> 这是三级引用


1.9 表格

1.9.1 说明

具体使用方式请看示例。

为右对齐。
------:

为左对齐。
:------

为居中对齐。
:------:


为使用默认居中对齐。

1.9.2 示例
|         序号    |    交易名    |    交易说明    |    备注    |
|    ------: |    :-------:    |    :---------   |    ------    |
|    1    |    prfcfg    |    菜单配置    |    可以通过此交易查询到所有交易码和菜单的对应关系    |
|    2    |    gentmo    |    编译所有交易    |    |
|    100000    |    sysdba    |    数据库表模型汇总    |    |

作者：candyLong
链接：http://www.jianshu.com/p/1ccc5a7d5b1d
來源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。




1.常用标记
1.1 标题
1.1.1 说明
使用 #
表示标题，一级标题使用一个 #
，二级标题使用两个 ##
，以此类推，共有六级标题。
使用 =====
表示高阶标题，使用 ---------
表示次阶标题。
# 这是一级标题
## 这是二级标题
### 这是三级标题
###### 这是六级标题

这是一级标题
========

这是二级标题
--------------
这是一级标题
这是二级标题
这是三级标题
这是六级标题
这是一级标题
这是二级标题
1.1.3 注意
#

和标题之间最好加一个空格。不要问我为什么，貌似有时候不会被识别为标题？已经忘记自己为什么要加空格了，也许是任性。

和 ----
表示标题时，大于等于2个都可以表示。
我通常在标题分级时使用标题标记，这个的用处很明了了。

1.2 目录
1.2.1 说明
使用 [TOC]
生成目录。如一开始的目录所示。
1.2.2 示例

[TOC]
[TOC]
1.2.3 注意
如果你的标题都是按照Markdown语法书写的话，可以自动生成层级目录。
我常用 为知笔记 记笔记，可惜 为知笔记 不支持[TOC]标记，一个悲伤的故事。
[TOC]
标记可能只能放在一级标题的前面，视不同的编译器而定。

1.3 引用
1.3.1 说明
使用 >
表示引用， >>
表示引用里面再套一层引用，依次类推。
1.3.2 示例
例1：

> 这是一级引用
>>这是二级引用
>>> 这是三级引用

>这是一级引用
这是一级引用

这是二级引用

这是三级引用

这是一级引用

例2：

> 这是一级引用
>>这是二级引用
>>> 这是三级引用
>这是一级引用
这是一级引用

这是二级引用

这是三级引用这是一级引用
1.3.3 注意
如果 >
和 >>
嵌套使用的话，从 >>
退到 >
时，必须之间要加一个空格或者 >
作为过渡，否则默认为下一行和上一行是同一级别的引用。如示例所示。
引用标记里可以使用其他标记，如：有序列表或无序列表标记，代码标记等。
我通常在 引用别人的话或者某些时候做说明 时使用引用标记，其实我一直拿不准到底什么情况下使用引用标记才是正确的。 如果你知道，我只想说：请务必告诉我。

1.4 代码块
1.4.1 说明
使用```表示代码块。
1.4.2 示例

var canvas = document.getElementById("canvas");
var context = canvas.getContext("2d");

var canvas = document.getElementById("canvas");var context = canvas.getContext("2d");

.4.3 注意
`这个符号是在 Esc
 键下面，切换到英文下即可。
```后面的 javascript
 表示此段代码为javascript代码，Markdown会自行使用javascript代码颜色渲染。这里也可以不写。PS：谁能够提供一个完整的Markdown可以渲染的语言列表啊，比如：linux命令这里写什么？
本文档所有使用讲解Markdown语法标记示例的地方都是使用代码块标记的。

1.5 行内代码
1.5.1 说明
使用``表示行内代码。
1.5.2 示例
这是javascript代码

这是 javascript
 代码
1.5.3 注意
本页部分文字中间的英文字母就是使用行内代码标记标记的。
这个的使用场景我也有些模糊。我常在文字间有英文的时候使用，但有时又不知道该不该使用，困扰。 **如果你知道，请告诉我。**

1.6 导入图片
1.6.1 说明
使用 ![Alt text](/path/to/img.jpg "Optional title")
 导入图片。其中：
Alt text
 为如果图片无法显示时显示的文字；
/path/to/img.jpg
 为图片所在路径；
Optional title
 为显示标题。显示效果为在你将鼠标放到图片上后，会显示一个小框提示，提示的内容就是 Optional title
 里的内容。

1.6.2 示例



1.6.3 注意
导入的图片路径可以使用绝对路径也可以使用相对路径，建议使用相对路径。
我通常的做法是Markdown文档的同级目录下建立一个pictures文件夹，里面放置所有所需的图片，如果图片多的话，你也可以在pictures文件夹里建立子文件夹归类。

1.7 列表
1.7.1 说明
使用 1. 2. 3.
 表示有序列表，使用 *
 或 -
 或 +
 表示无序列表。
1.7.2 示例

例1：有序列表

1. 第一点
2. 第二点
4. 第三点
第一点
第二点
第三点

例2：无序列表
呵呵
嘉嘉
嘻嘻
吼吼
嘎嘎
桀桀
哈哈
```
1.7.3 注意
无序列表或有序列表标记和后面的文字之间要有一个空格隔开。
有序列表标记不是按照你写的数字进行显示的，而是根据当前有序列表标记所在位置显示的，如示例1所示。
无序列表的项目符号是按照实心圆、空心圆、实心方格的层级关系递进的，如例2所示。通常情况下，同一层级使用同一种标记表示，便于自己查看和管理。
无序列表和有序列表标记的使用场景也很明了，故不多说。

1.8 粗体和斜体
1.8.1 说明
使用 *
或者 __
表示粗体。
使用 
或者 _
表示斜体。

1.8.2 示例

 **粗体1**    __粗体2__
 *斜体1*    _斜体2_
粗体1 粗体2
斜体1 斜体2

1.8.3 注意
前后的 
或 _
与要 *加粗或倾斜 的字体之间不能有空格。
我通常在强调时使用加粗标记，在和一行中的加粗区分且也表示强调时使用倾斜标记，这里的倾斜标记的使用场景不明确。 如果你知道：请务必告诉我。**

1.9 表格
1.9.1 说明
具体使用方式请看示例。
------:
为右对齐。
:------
为左对齐。
:------:

为居中对齐。

为使用默认居中对齐。

1.9.2 示例

|         序号    |    交易名    |    交易说明    |    备注    |
|    ------: |    :-------:    |    :---------   |    ------    |
|    1    |    prfcfg    |    菜单配置    |    可以通过此交易查询到所有交易码和菜单的对应关系    |
|    2    |    gentmo    |    编译所有交易    |    |
|    100000    |    sysdba    |    数据库表模型汇总    |    |

99.png
1.9.3 注意
每个Markdown解析器都不一样，可能左右居中对齐方式的表示方式不一样。

1.10 分割线
1.10.1 说明
使用 ---
或者 *
或者 *
表示水平分割线。
1.10.2 示例

---

***

* * *
1.10.3 注意
只要 *
或者 -
大于等于三个就可组成一条平行线。
使用 ---
作为水平分割线时，要在它的前后都空一行，防止 ---
被当成标题标记的表示方式。

1.11 链接
1.11.1 说明
使用 
表示行内链接。其中：
[]
内的内容为要添加链接的文字。
link
为链接地址。
Optional title
为显示标题。显示效果为在你将鼠标放到链接上后，会显示一个小框提示，提示的内容就是 Optional title
里的内容。

参考式链接如例所示。
1.11.2 示例
例1：行内链接

这就是我们常用的地址：[Baidu](www.baidu.com "百度一下，你就知道" )
这就是我们常用的地址：Baidu

例2：参考式链接

这就是我们常用的地址：[Baidu][1]

[1]:www.baidu.com "百度一下，你就知道"
这就是我们常用的地址：Baidu
1.11.3 注意
参考式链接和行内链接的效果是一样的，各有利弊。行内连接清晰易懂，可以清楚的知道链接的地址，但是不便于多次利用。参考式链接可以重复使用，但不能即刻知道链接的地址。
使用场景很明了，不多说。

1.11 反斜杠
1.11.1 说明
使用 \
表示反斜杠。在你不想显示Markdown标记时可以使用反斜杠。
1.11.2 示例

\*这里不会显示斜体\*
这里不会显示斜体
1.11.3 注意
无。
1.12 空格
1.12.1 说明
Markdown语法会忽略首行开头的空格，如果要体现出首行开头空两个的效果，可以使用 全角符号下的空格 ，windows下使用 shift+空格
切换。
1.12.2 示例
无。

1.12.3 注意
无。

次常用标记
2.1 标签分类

2.1.1 说明
使用 标签:
或者 Tags:
表示标签标记。
2.1.2 示例
标签: 数学 英语
Tags: 数学 英语
标签: 数学 英语Tags: 数学 英语
2.1.3 注意
标签:
或者 Tags:
的冒号要使用半角冒号。
基本没使用过这个标记，不过应用场景应该是归类。便于快速了解文章分类。难道可以通过某种方式来遍历到标签标记？不甚了解。 如你知道：请告诉我。

2.2 删除线
2.2.1 说明
使用 ~~
表示删除线。
2.2.2 示例

~~这是一条删除线~~
这是一条删除线2.2.3 注意
注意 ~~
和 要添加删除线的文字之间不能有空格。
我常使用在显示的告诉自己这行文字是要删除的。

2.3 注脚
2.3.1 说明
使用 [^footer] 表示注脚。
2.3.2 示例

这是一个注脚测试[1]。
这是一个注脚测试[^footer1]。
2.3.3 注意
我常在需要解释一个名词，或者一本书，或者一个人时使用脚注标记。

不常用标记
3.1 实现页内跳转
3.1.1 说明
使用html代码实现页内跳转。在要跳转到的位置定义个锚 <span id = "jump">hehe</span>
，然后使用 你好
将 你好
设置为一单击即跳转到 hehe
所在位置的效果。
3.1.2 示例
[你好](#jump)<span id = "jump">hehe</span>
你好
hehe

3.1.3 注意
无。

专项使用标记
4.1 流程图
以后在总结吧，现在的我完全没有使用上，没有需求就先不总结了。
4.2 LaTeX公式
以后在总结吧，现在的我完全没有使用上，没有需求就先不总结了。
写在后面的话
[TOC]不支持呀不支持，看不到效果了。
谁有什么好的方式在博客园中更好的显示Markdown，像 作业部落 一样。
以上都是我学习到的，然后经过几个月的使用总结的，针对我的常用非常用分类。如果有描述的不对的地方，欢迎批评指正，共同进步。

[1]:这是一个测试，用来阐释注脚。 ↩



-------------------------


判断是否手机登陆
>1.手机登陆=》跳转到手机版页面
>2.手机版显示模板
    >>1.菜单<BR>
    >>2.个人中心<BR>
    >>3.退出<BR>
    >>
>3.采购回复
    >>1.主表<br>
    >>2.明细列表
    >>>详情
    >
>4.正式订单
    >>1.主表<br>
    >>2.明细列表
    >>>详情
    >
 
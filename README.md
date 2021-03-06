markdown测试
=======
#标题

区块引用
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

区块引用 在整个段落的第一行最前面加上 >
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

区块引用，嵌套
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

列表。无序列表

*	red
*	blue
*	yellow

有序列表

1.  apple
2.	orange
3.	peach

有序列表

1.	java
1.	python
1.	object-c


列表项目可以包含多个段落

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

如果你很懒惰

>1.   This is a list item with two paragraphs.
>
>   This is the second paragraph in the list item. You're
>only required to indent the first line. Lorem ipsum dolor
>sit amet, consectetuer adipiscing elit.
>
>2.   Another item in the same list.


1.   This is a list item with two paragraphs.

    This is the second paragraph in the list item. You're
only required to indent the first line. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit.

2.   Another item in the same list.

如果要在列表项目内放进引用，那&lt;就需要缩进：

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.


如果要放代码区块的话，该区块就需要缩进两次，也就是 8 个空格或是 2 个制表符：

*   一列表项包含一个列表区块：

		public static String getNameByEn(String enName){
			return enNameMap.get(enName);
		}


换句话说，也就是在行首出现数字-句点-空白，要避免这样的状况，你可以在句点前面加上反斜杠。

1986\. What a great season.

代码区块
---------

这个每行一阶的缩进（4 个空格或是 1 个制表符），都会被移除，例如：

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell
    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

分隔线上

----
分隔线下

链接
---------

This is [Markdown语法](http://wowubuntu.com/markdown/ "使用语法") inline link.

[Markdown语法](http://wowubuntu.com/markdown/) has no title attribute.
[idmarkdown]: http://wowubuntu.com/markdown/  "Markdown语法"
This is [列表项目可以包含多个段落] [idmarkdown] reference-style link.

强调
-----------
*single asterisks*

如果要标记一小段行内代码，你可以用反引号把它包起来（\`），例如：

Use the `printf()` function.

反斜杠
-----------
\*literal asterisks\*

\\   反斜线

\`   反引号

\*   星号

\_   底线

\{\}  花括号

\[\]  方括号

\(\)  括弧

\#   井字号

\+   加号

\-   减号

\.   英文句点

\!   惊叹号
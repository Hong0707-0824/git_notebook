# <center>MarkDown 语法

# 1.Markdown 标题语法
要创建标题，请在单词或短语前面添加（#）。#的熟料代表了标题得级别，例如，添加三个#表示创建一个三级标题（h3）
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

### 1.1可选语法
还可以在文本下方添加任意数量的==号来表示一级标题，或者--号来表示二级标题

# 2.Markdown 段落
要创建段落，请使用空白行将一行或多行文本进行分割。
# 3.Markdown换行语法
在一行的末尾添加两个或多个空格，然后按回车健即可创建一个换行（<br>）
# 4.Markdown强调语法
通过将文本设置为粗体或斜体来强调其重要性。
## **粗体**
要加粗文本请在单词和短语前后添加两个*或(_)。
## *斜体*
要用斜体显示文本，请在单词或短语前后添加一个星号（asterisk）或下划线（underscore）。要斜体突出单词的中间部分，请在字母前后各添加一个星号，中间不要带空格。
# 5.Markdown 引用语法
要创建块引用，请在段落前添加一个（>）符号。
>例如引用这句话
## 5.1多个段落的块引用
块引用可以包含多个段落为段落之间的空白行添加一个>符号  
如下  
>多行应用  
>是这样的  
## 5.2嵌套块引用
块引用可以嵌套。要在嵌套的段落前添加一个>>符号
>lookthis
>>andthis 
## 5.3带有其他元素的块引用
块引用可以包含其他的markdown格式的元素。并非所有元素都可使用，你可以尝试以查看那些元素有效。
>  sdasdasd  
>  sdasdas  
>  asdasda
>-  asdasd
>- asd
>- as  
> dsassdsd
# Markdown 列表语言
可以将多个条目组织成有序或无序列表。
## 有序列表
要创建有序列表，请在每个列表前添加数字并紧跟一个英文句点。数字不必按章数学顺序排列，但是列表应当以数字1起始。
1. firstitem
2. second item 
4. sdsd
5. sd
6. sd
## 无序列表
要创建无序列表，请在每个列表项前添加（-），（*）或（+）。缩进一个或等多个列表项可创建嵌套列表。
- first item
- seconditem 
* third item
+ forth item
## 在列表中嵌套其他元素
*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.
## 引用块
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.
## 代码块
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
            <head>
                <title><test></title>
            </head>
        <html>

3.  Update the title to match the name of your website.

# marketdown 代码语法
要将单词或短语为代码请将其包裹在反引号（）内。
`比如这个`
## 转义反引号
如果你要表示为代码的单词或短语中包含一个或多个饭引号，泽可以通过将单词或短语包裹在双反引号中。
## 代码块
要创建代码块
，请将代码块的每一行都缩进至少四个空格或一个制表符。
# Markdown分割线语法
要创建分割线，请在一行上使用三个或多个（*）（-）（_），并且不能包含其他内容。
***
---
___
# markdown链接语法
链接文本放在括号内，链接地址放在后面的括号中链接title可选  
超链接语法：[超链接显示名](超链接地址"超链接title")

对应html代码：<a href="超链接地址" title="超链接title">超链接显示名</a>

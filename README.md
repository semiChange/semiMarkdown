# semiMarkdown

## Markdown 基本语法
	常用的标记符号不超过十个,不到半小时就能完全掌握。
## Markdown 标题语法
创建标题需要添加 "# "号, #号数量代表标题级别
# 一级标题     
## 二级标题   
###### 六级标题  

建议:#号后面加一个空格



## Markdown 段落语法
要创建段落,只需要空白一行或多行

我是段落

我是段落

建议: 段落头部不要用空格或Tab缩进

## Markdown 换行语法
只需要在行尾添加2个或多个空格, 然后回车即可

建议: 使用`<br>`也是可以的


示例:  
我要换行  
我要换行


## Markdown 强调语法
强调就是加粗文字  
使用 **加粗的文字**  
使用 __加粗的文字__

建议: 推荐使用星号（asterisks）

斜体, 只需加一个*或_即可  



*我是斜体*


粗斜体 使用 3个*

***我是粗斜体***



## Markdown 引用语法
引用块只需在前面加上>即可

> 我是引用块
>> 我是嵌套的引用块   
> 我是引用块  
> - 引用块中也可以使用列表
> - 引用块中也可以使用列表
> - 引用块中也可以使用列表




## Markdown 列表语法
要创建数字列表,只需加上数字和英文小数点即可  

1. 我是列表
2. 我是列表
1. 我是列表


无序列表
在前面添加  +,-,* 都可以


附: 在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符


## Markdown 代码语法
只需要用 `代码` 包裹即可


`this is a code`


代码块, 每一行缩进4个空格或tab

	<html>
      <head>
      </head>
    </html>


## Markdown 分隔线语法
在单独一行上 使用三个或多个星号 (***)、破折号 (---) 或下划线 (___) 



---

***

___







## Markdown 链接语法
语法代码：
`[超链接显示名](超链接地址 "超链接title")`

[我是一个链接](http://www.google.com "鼠标hover标题")  


使用< >尖括号可以变成链接  
<https://markdown.com.cn>  
<fake@example.com>
  


## Markdown 图片语法
图片和链接一样, 只需要多加一个!

语法 `![图片alt](图片链接 "图片title")`

带超链接的语法 `[同上](图片的点击http://超链接)`

[![我是图片替代文本,加载失败时显示](https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg "图片提示")](http://g.com)

## Markdown 转义字符语法
要显示markdown里面使用的符号,需要\反斜杠

\****


## Markdown 内嵌 HTML 标签

可以行内标签可以直接使用

块元素需要上下空一行

This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.



---
layout:     post
title:      Learning series about HTML
subtitle:   HTML_1
date:       2019-09-25
author:     Shirley
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - HTML
---

最近由于一些原因，所以想学一下html。发现了如果想要学习这些IT类的东西，其实可以还是借助很多工具的，比如说，各种training
app或者网页。

在尝试Mimo and Py learn to code 的软件。感觉这种交互式的应用对于自学其实帮助挺大的，尤其是在国外的教学模式下。
有了这种软件，其实整体的学习效率就会快很多。感觉适合初学，并且非常方便。不过这个实际上就是归属于教育部分，细分
的话，应该是职业发展教育模块，所以，app主要取决于课程设计。

国内来说，实验楼也不错。当然，还有存在于各大公众号上的课程。

## what is HTML 

HTML是一种标记语言，包含一套markup tages. 它可以对pages的信息进行描述。pages由HTML tags and 文本内容决定。
一般而言，HTML文档中需要对文档所使用的HTML语言版本进行声明。HTML文档的后缀可以是.html/.htm。

```
HTML 5申明: <!DOCTYPE HTML> 

<!-- -->用于表示注释。
```

## Pages

web pages由`<html>`开始，直到`</html>`结束。一般pages包含两部分，头部"`<head>`...`</head>`"和"`<body>`...`
</body>`". `<head>..</head>` is a container for metadata, including document title, character set, styles,
scripts, and other meta information. `<head>...</head>`部分在最终页面中并不显示。
For example:

```
<!DOCTYPE html>
<html>
<head>
<title>菜鸟教程(runoob.com)</title>
<meta charset="utf-8"> 
<!--一般这边会需要这个，然后设计GBF-->
</head>
<body>
 
<h1>我的第一个标题</h1>
 
<p>我的第一个段落。</p>
 
</body>
</html>
```

<!DOCTYPE html>
<html>
<head>
<title>菜鸟教程(runoob.com)</title>
<meta charset="utf-8"> 
<!--一般这边会需要这个，然后设计GBF-->
</head>
<body>
 
<h1>我的第一个标题</h1>
 
<p>我的第一个段落。</p>
 
</body>
</html>

## HTML Tags

Tag:"<"+signs+">". HTML tags are insensitive to upper- or lowercases.

双标签：
opening tag: "<"+name+">", eg:`<html>`
closing tag: "<"+"/"+name+">", eg:`</html>`
Element: opening tag+content+closing tag

单标签：
"<"+signs+"/"+">" HTML tags with no element are empty elements, which do not have an end tag.
```
Eg:
<br/> This tag is for breaking a line
```

标签之间可以存在嵌套关系也可以存在并列关系。

## HTML Attributes

The additional information the element contains, called html attributes, is included in the start tag.
These attributes come in name/values pairs.

Common attributes:
Style attribute is used to specify the stying of an element, like color, font, size etc.

### Heading

一共有六种标题格式方法分别为：

```
<h1>...</h1>
<h2>...</h2>
<h3>...</h3>
<h4>...</h4>
<h5>...</h5>
<h6>...</h6>
```
具体显示的时候是以下这个样子：
<h1>This is the h1 heading</h1>
<h2>This is the h2 heading</h2>
<h3>This is the h3 heading</h3>
<h4>This is the h4 heading</h4>
<h5>This is the h5 heading</h5>
<h6>This is the h6 heading</h6>

可以指定某种heading的显示大小，这种格式通过style attribute, using font-size property。
For example:
```
<h1 style="font-size:60px">Heading</h1>
```

### Paragraph
`<p>...</p>` defines a paragraph

```
Eg:
<p>This is a paragraph</p>
```
**注：**

* `<p>...</p>`之中的内容的空格会被自动忽视。所以，如果需要在显示时呈现一定格式可以使用`<br/>`进行换行回车。
* `<hr>`用于添加大横线，可以用于段落之间的分割。


### Links
`<a>....</a>` defines a link.

### Images
`<img>` defines a Image

### Buttons
'<button>...</button>` defines a button.

### Lists

`<ul>..</ul>` defines an unordered list with bullets.`<li> `follows a list content.

```
For example:
<ul>
 <li> listcontent1
</ul>
```

`<ol>...</ol>' defines an ordered list with numbers. '<li>' follows a list content.

```
For example:
<ol>
 <li> listcontent1
</ol>
```























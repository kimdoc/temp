###1.标题
\# 一级标题...\###### 六级标题

###2.区块元素
>一个引用
>>引用内的引用，想换行，行末尾加两个空格。  
>>结束引用，需要有空行。
>
>#####引用内部也可以用markdown语法
>加空行，结束引用段落

###3.列表
无序列表：*/+/-，列表符后加空格
* red
+ green
- blue

有序列表：**段落前需要有空行**

1. first
2. second
3. third

###4.分割线：
三个以上符号，生成分隔线。  
星号，星号（空格），下划线，下划线（空格），减号（空格）
***
* * *
- - -
_ _ _

###5.链接
行内链接：[显示的文字](link "title")
This is [an example](http://example.com/ "Title") inline link.
This is [BaiDu](http://baidu.com "abc") link.

参考式链接：
First is [BaiDu][1], second is [soso][2] link, third is [google][] WebSite.
[1]: http://baidu.com "BaiDuSearch"
[2]: http://baidu.com (BaiDuSearch)
[google]: http://g.cn (google)
* 参考式链接更易读；
* id可以省略，直接用链接名；
* title可以用双引号或括号。

###6.图片
链接前加“!”：![无图显示文字][/img/head.jpg "title"]  
图片链接也可以使用参考式链接。

###7.强调
*斜体*  
**粗体strong**

###8.代码
键盘左上角的**反引号**，不是引号。  
行内代码段：Use the `printf()` function.  

代码段：前后行加```；或者前后空行，内容缩进四个空格。
```
<html>
  <head></head>
  <body></body>
</html>
```

    <html>
      <head></head>
      <body></body>
    </html>

###9.网址&邮箱
<http://baidu.com>
转换为：<a href="http://baidu.com">http://baidu.com</a>  
<kimdoc@163.com>
转换为：十六进制编码

###10.转译：\
\ 反斜线` 反引号* 星号_ 底线{} 花括号[] 方括号() 括弧# 井字号+ 加号- 减号. 英文句点! 惊叹号

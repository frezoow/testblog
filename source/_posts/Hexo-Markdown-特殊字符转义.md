---
title: Hexo Markdown 特殊字符转义
date: 2017-05-16 17:51:55
tags: 
    - hexo
    - 技巧
categories: 工具技巧
---
{% blockquote 一张假钞的真实世界 http://zhang-jc.github.io/2017/03/30/Hexo-Markdown-%E7%89%B9%E6%AE%8A%E5%AD%97%E7%AC%A6%E8%BD%AC%E4%B9%89/ Hexo-Markdown-特殊字符转义 %}
{% endblockquote %}

在使用 Markdown 编写 Hexo 的 Blog 时，对于特殊字符使用“\”转义有时会不成功，最好的方式是直接使用特殊字符的编码，对应如下：

<!-- more -->
```
- &#45; &minus; — 减号
! &#33; — 惊叹号Exclamation mark 
” &#34; &quot; 双引号Quotation mark # &#35; — 数字标志Number sign $ &#36; — 美元标志Dollar sign 
% &#37; — 百分号Percent sign 
& &#38; &amp; Ampersand 
‘ &#39; — 单引号Apostrophe 
( &#40; — 小括号左边部分Left parenthesis 
) &#41; — 小括号右边部分Right parenthesis 
* &#42; — 星号Asterisk 
+ &#43; — 加号Plus sign 
< &#60; &lt; 小于号Less than 
= &#61; — 等于符号Equals sign 
> &#62; &gt; 大于号Greater than 
? &#63; — 问号Question mark 
@ &#64; — Commercial at 
[ &#91; --- 中括号左边部分Left square bracket 
\ &#92; --- 反斜杠Reverse solidus (backslash) 
] &#93; — 中括号右边部分Right square bracket 
{ &#123; — 大括号左边部分Left curly brace 
| &#124; — 竖线Vertical bar 
} &#125; — 大括号右边部分Right curly brace 
```
<!-- 方法来自博客： [一张假钞的真实世界](http://zhang-jc.github.io/2017/03/30/Hexo-Markdown-%E7%89%B9%E6%AE%8A%E5%AD%97%E7%AC%A6%E8%BD%AC%E4%B9%89/) -->

---
<div style="text-align:center;color: #636363;font-size:14px;letter-spacing: 10px">本文结束啦<i class="fa fa-bell"></i>感谢您的阅读</div>
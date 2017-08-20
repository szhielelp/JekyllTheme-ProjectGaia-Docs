<h1 align="center">
  <a href="https://docsify.js.org">
    Project Gaia
  </a>
</h1>

<p align="center">
  个人无聊的时候乱写的Jekyll主题, 通过Bootstrap 4 + JQuery 3实现
</p>


## 实例 

![](    _media/1.jpg  )
![](    _media/2.jpg  )
![](    _media/3.jpg  )
![](    _media/4.jpg  )


## 用法

1. [   给我捐款   ](http://szhshp.org/about.html)
1. Fork 然后 give me a star!
1. **Important** 记得把 `_config.yml` 文件中的 `baseurl` 改成实际使用的URL

## 插件

### 代码高亮

通过这玩意实现的 : [    syntaxhighlighter/syntaxhighlighter](https://github.com/syntaxhighlighter/syntaxhighlighter)

在普通的多行代码前后加一个`<pre>`并且类名里面写上对应的语言

```html
<pre class="brush: js">
  var szhshp = 'cool';
</pre>
```

高亮示例：

![](      _media/X3.png )

### TOC目录

通过这玩意实现的: [    jgallen23/toc  ](https://github.com/jgallen23/toc)

![](     _media/X2.png   )

同样`Jquery.ready`时自动运行

### md-post-header-collapse

通过这玩意实现的: [    szhielelp/md-post-header-collapse  ](https://github.com/szhielelp/md-post-header-collapse)

Post加载完毕后运行`$.headerCollapseRobot()`

```js
    /*header collapsible*/
    $.headerCollapseRobot(
      arr_Id_CollapseEnds =  new Array("end"),                       
      arr_Collapsible_Tag = new Array("H1","H2","H3"),                       
      arr_ExcludeElemPrefix_InCollapsible  = new Array("comment-"),      
      arr_ExcludeElemPrefix_InCollapsing = new Array("sidebar-toc-Ik4D-")
    )
```

![](     _media/X1.png   )

点击标题旁边的加减号即可将章节段落进行收缩/展开

### 文章置顶

Post的header里面加个参数`stickie: true`即可

header示例:

```
layout: post
title: blablablalala
category : Comic
tags : [Comic, 10101]
stickie: true
```

然后这篇文章就会出现在所有文章的前面


### 阅读进度条

灵感来自于 [http://es6.ruanyifeng.com/#docs/promise](http://es6.ruanyifeng.com/#docs/promise)

![](   _media/X4.png   )

显示阅读进度的一个进度条而已

### 三方评论框

建议使用纯JS的三方评论，这样不会改变文章页面的总体结构

给所有文章页面添加三方评论插件，只需要修改**_includes/comment-full.html**里面的内容。

## 遇到问题

你可以在[项目页面 ]( https://szhielelp.github.io/JekyllTheme-ProjectGaia/) 或者 [我的博客 ](http://szhshp.org ) 留言，我一般回回复并且提供一些解决方案

## 开源协议

MIT

## 捐款

[  支付宝    ](http://szhshp.org/about.html)

## 更新历史

[ 更新历史   ](https://github.com/szhielelp/JekyllTheme-ProjectGaia#readme)
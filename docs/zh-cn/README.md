<h1 align="center">
  <a href="https://docsify.js.org">
    Project Gaia
  </a>
</h1>

<p align="center">
  Jekyll 主题, 通过 Bootstrap 4 + JQuery 3 实现
</p>


>
># News (2020-08)
>
>**当前主题未来不再维护** 来试试新的模板吧: -->> [Project Titan](https://github.com/szhielelp/NextJS-BlogTemplate-ProjectTitan) <<--
>
>**Project Titan** 通过 **NextJS** x **Material UI** x **Typescript** 实现, 和 **Project Gaia** 拥有完全相同的风格和设计.
>
>你可以从 **Project Gaia** 无缝迁移到 **Project Titan** (大概吧...)
>
>可以通过下方两个站点查看两者的区别:
>
>- Project Titan: [https://szhshp.org](https://szhshp.org)
>- Project Gaia: [https://legacy.szhshp.org](https://legacy.szhshp.org)


## 实例 


![](    ../_media/demo/1.png  )
![](    ../_media/demo/2.png  )
![](    ../_media/demo/3.png  )
![](    ../_media/demo/4.png  )


## 用法

1. [   给我捐款   ](http://szhshp.org/about.html)
1. Fork 然后 give me a star!
1. 重要: 记得把 `_config.yml` 文件中的 `baseurl` 改成实际使用的 URL

## Whats New in Version 2.0?

1. 新的折叠侧边栏设计
1. 新的文章分类页面设计
1. 新的代码高亮插件。
1. 集成最新版本的 Bootstrap
1. 添加动画效果
2. SCSS + ES6


## 插件

### 文章置顶

Post 的 header 里面加个参数`stickie: true`即可

header 示例:

```
layout: post
title: blablablalala
category : Comic
tags : [Comic, 10101]
stickie: true
```

然后这篇文章就会出现在所有文章的前面

![]( ../_media/post/stickyPost.png )

### 三方评论框

建议使用纯 JS 的三方评论，这样不会改变文章页面的总体结构

给所有文章页面添加三方评论插件，只需要修改`_includes/comment-full.html`里面的内容。


## 文章插件

你可以在 `js/post.js`开启或关闭某些插件

```javascript
    let config = {
      activeHighlight: true,
      activeHeaderCollapse: true,
      activeHeaderNumber: true,
      activeLightbox: true,
      activeReadingProgressBar: true,
    }
```

### 代码高亮

代码块将会自动识别语法:

    ```
      var szhshp = 'cool';
    ```


如果想要手动设置语法, 可以如下编写:

    ```js
      var szhshp = 'cool';
    ```


### 段落标题

给文章的各级标题前添加段落编号

![]( ../_media/post/headerNumber.png )

>总觉得 header 前面加个数字看起来会整齐一些

### md-post-header-collapse

通过这玩意实现的: [    szhielelp/md-post-header-collapse  ](https://github.com/szhielelp/md-post-header-collapse)

Post 加载完毕后运行`$.headerCollapseRobot()`

```js
    $.headerCollapseRobot('#page-content', ['h1', 'h2', 'h3'], ['blockquote']);
```

![]( ../_media/post/headerCollapse.png )

点击标题旁边的加减号即可将章节段落进行收缩/展开



### 阅读进度条

灵感来自于 [http://es6.ruanyifeng.com/#docs/promise](http://es6.ruanyifeng.com/#docs/promise)

![]( ../_media/post/progressbar.png )

某日我心情很好于是就做了这个东西


### Lightbox

一个方便图片展示的插件, 同时可以将一组图片逐个显示。

![]( ../_media/post/lightbox.png )


## 遇到问题

你可以在 [项目页面 ]( https://szhielelp.github.io/JekyllTheme-ProjectGaia/) 或者 [我的博客 ](http://szhshp.org ) 留言，我只要闲的没事的时候就会去看看

## 开源协议

MIT

## 捐款

[  支付宝    ](http://szhshp.org/about.html)

## 更新历史

[ 更新历史   ](https://github.com/szhielelp/JekyllTheme-ProjectGaia#change-log)

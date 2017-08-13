<h1 align="center">
  <a href="https://docsify.js.org">
    Project Gaia
  </a>
</h1>

<p align="center">
  Personal Jekyll theme, Powered Bootstrap 4, JQuery 3
</p>


## Demo 

![](    _media/1.jpg  )
![](    _media/2.jpg  )
![](    _media/3.jpg  )
![](    _media/4.jpg  )


## Usage

1. Fork and give me a star!
1. Donate me please!
1. **Important** Please change the `baseurl` value in  `_config.yml` to your repo name

## Plugins

### SyntaxHighlighter

Realized with this repo: [    syntaxhighlighter/syntaxhighlighter](https://github.com/syntaxhighlighter/syntaxhighlighter)

Put  `<pre>` tag with specific class name between code blocks:

```html
<pre class="brush: js">
  var szhshp = 'cool';
</pre>
```

Here is code snippet example:

![](      _media/X3.png )

### Table of Content

Realized with this repo: [    jgallen23/toc  ](https://github.com/jgallen23/toc)

![](     _media/X2.png   )

Auto-enable when page loaded.

### md-post-header-collapse

Realized with this repo: [    szhielelp/md-post-header-collapse  ](https://github.com/szhielelp/md-post-header-collapse)

Run **$.headerCollapseRobot()** after post loaded.

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

You can try clicking on the icons near titles.

### Stickie Post

Just put a attribute in header of the specific post:

 <pre class="brush: html; highlight: [5]">
layout: post
title: blablablalala
category : Comic
tags : [Comic, 10101]
stickie: true
</pre>

Then current post will show ahead of other posts.

### Reading Progressbar

Inspired from [http://es6.ruanyifeng.com/#docs/promise](http://es6.ruanyifeng.com/#docs/promise)

![](   _media/X4.png   )

It will show your reading progress for current post.

## License

MIT

## Donate

[   Donate via Alipay    ](http://szhshp.org/about.html)

## Change Log

- __May 30th, 2017__
  
  Added reading progressbar for post page.
  
- __May 6th, 2017__
  
  Updated font page
  Added global font style
  
- __April 3nd, 2017__
  
  Added new font
  
- __Mar 5th, 2017__
  
  Style updated
  
- __Mar 1st, 2017__
  
  TOC plugin updated
  
- __Feb 28th, 2017__
  
  Rebuild to include **Bootstrap 4-Alpha** and **JQuery 3**
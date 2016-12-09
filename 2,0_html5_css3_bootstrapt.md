title: 新世：HTML5、CSS3、BootStrapt
speaker: bugzhang
url: https://github.com/CSU-Apple-Lab/Slides-for-Web-Class
description：中南大学苹果实验室web开发教程
transition: slide3
files: /css/theme.moon.css
theme: moon
highlightStyle: monokai_sublime
date: 2016年12月3日

================================================================
[slide]

## Web开发系列——第二节
## `新世：HTML5、CSS3、BootStrapt`


[slide]
## 1.1 HTML5简介
>HTML5是HTML最新的修订版本，2014年10月由W3C完成标准制定。
HTML5的设计主要目的是为了在移动设备上支持多媒体。在此之前，这个工作一直由Flash完成。
<br>**HTML5加入的新特性**:
<br>-绘图
<br>-视频与音频媒体
<br>-布局元素
<br>-表单控件属性
<br>-本地存储
<br>-本地sql数据
<br>-web应用
<br>-支持CSS3
<br>-支持WebSocket


[slide]
## 1.2 HTML5新元素
- `<article>`	定义页面独立的内容区域。
- `<aside>`	定义页面的侧边栏内容。
- `<dialog>`	定义对话框，比如提示框
- `<footer>`	定义 section 或 document 的页脚。
- `<header>`	定义了文档的头部区域
- `<nav>`	    定义导航链接的部分。
- `<section>`	定义文档中的节（section、区段）。
- `<time>`	定义日期或时间。
- `<video>`   定义视频
- `<audio>`   定义音频

[slide]
## 1.3 HTML5游览器支持
>五大游览器:
<br>-`Safari`：完全支持
<br>-`Chrome`：完全支持
<br>-`Firefox`：完全支持
<br>-`Opera`：完全支持
<br>-`IE`：9部分支持，10以上完全支持

所以之后开发，以HTML5为标准，不考虑其他老旧版本。


[slide]
## 2.1 CSS3简介
>CSS 用于控制网页的样式和布局。
 CSS3 是最新的 CSS 标准。
 CSS3 被拆分为一个个模块，一个模块负责一类样式。
<br>**CSS3的重要模块**:
<br>-选择器
<br>-盒模型
<br>-背景和边框
<br>-文字特效
<br>-2D/3D转换
<br>-动画
<br>-多列布局
<br>-用户界面
<br>-图片
<br>-分页


[slide]
## 2.2 定位
> 为了让网页中的元素，在我们html中更加合理的分布和展示。我们需要使用position属性，对其进行定位。例如很多网页中的提示语浮动层，一些特殊情况的形状见的拼合。
<br>**定位种类**:
><br>-`static`：无特殊定位---默认
<br>-`absolute`：绝对定位---对象从文档流中脱离（不再占位），使用left，right，top，bottom等属性进行绝对定位。其层叠展示，使用z-index来定义。
<br>-`relative`:相对定位---可以使用left，right，top，bottom等属性进行位置调整，但是，原有位置，依然被其占据。

[slide]
## 2.3 盒子模型
> 所有HTML元素可以看作盒子，CSS盒模型封装周围的HTML元素，它包括：边距，边框，填充，内容。
  盒模型允许我们在其它元素和周围元素边框之间的空间放置元素。
<div class="columns2">
    <div><img src="/assets/img/class2/box-model.gif" height="300"></div>
    <div>
        Margin(外边距)：清除边框外的区域，外边距是透明的。
        Border(边框)：围绕在内边距和内容外的边框，不透明的。
        Padding(内边距)：清除内容周围的区域，内边距是透明的。
        Content(内容)：内容。
    </div>
</div>


[slide]
## 2.4 
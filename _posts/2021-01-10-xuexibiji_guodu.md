---
title: 用好CSS3过渡，可以让你的网页瞬间不一样
date: 2021-01-09
excerpt_separator: "<!--more-->"
categories:
     - 学习笔记
---

在我看来，过渡是一件很有趣的事情，可以网页实现简单的动画效果，在网页设计中我认为也是不可缺少的一部分
<!--more-->

## 为什么要用transition
1.通过过渡transition，我们不需要javascript就可以实现动画效果

2.过渡比较平滑，可以从一个状态立马切换到另一种状态

## 该怎样设置过渡呢
#### transition-property
1.过渡属性，可应用于所有元素

2.transition-property初始值是all，表示指定元素所有支持transition-property属性的样式

3.语法：: none|all| property（ CSS 属性名称）;比如transition-property: width;
#### transition-duration
1.过渡持续时间，可应用于所有元素

2.初始值为0s，若把属性值设为0则为无效值

3.语法：transition-duration: time;比如transition-duration: 1s; 
#### transition-delay
1.过渡延迟时间，可应用于所有元素

2.初始值为0s，若为负值则无延迟效果，若把属性值设为0则为无效值

3.语法：transition-duration: time;比如transition-delay: 0s; 
#### transition-timing-function
1.过渡时间函数，可应用于所有元素

2.初始值为ease

3.定义速度变化速度变化如ease、linear、 ease-in、ease-out、ease-in-out或者cubic-bezier，具体使用可见[ **runoob** ](https://www.runoob.com/cssref/css3-pr-transition-timing-function.html)

4.语法：transition-timing-function: linear|ease|ease-in|ease-out|ease-in-out|cubic-bezier(n,n,n,n);比如transition-timing-function: ease; 

5.若不使用预设好的，要用cubic-bezier，可参考[ **缓动函数速查表** ](http://www.xuanfengge.com/easeing/easeing/)

## 多值如何设定
#### transition:transition-property transition-duration transition-timing-function transition-delay；
1.若都仅有一个值，可以这样设置<br>transition: all 1s ease 0s; 

2.若只是transition-property值不同，而其他三个都相同，可以这样设置<br>transition: width 2s linear 200ms,background 2s linear 200ms;

3.若transition-property值的个数多于对应的其他三个的值时，可以这样设置<br>transition: width 2s linear 200ms,background 500ms ease 0s,opacity 2s linear 200ms;

<br>
<br>
<br>
<br>
<br>
<br>
<br>
###### 本人学术不精，就只能写到这了




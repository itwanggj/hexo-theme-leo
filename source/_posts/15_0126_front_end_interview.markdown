---
layout: post
title:  世界各地程序员共同总结的前端面试题
date:   2015-01-26 08:24:00
category: [面试题]
---
## 常规问题
* 最近你学了什么？
* 是什么激发你对编程的兴趣？
* 你最近在挑战什么新技术、你是怎么解决遇到的问题？
* 当你在构建Web应用程序或网站时，你会考虑什么样的用户界面、安全性、性能、SEO、可维护性、选用的技术？
* 谈谈你首选的开发环境（系统、编辑器或IDE、浏览器、工具等）
* 你熟悉什么版本控制系统？
* 请描述一下你创建一个网页的工作流程？

<!--more-->

* 如果有5个不同的样式表，怎样最好地整合到网站里？
* 请描述一下渐进增强和优雅降级的区别？
* 如何优化一个网站的资源？
* 传统上，为什么网站资源来自多个域会更好？
* 浏览器能同时下载某个域的多少资源？
    * 例外情况是什么？
* 说出3个减少页面加载时间的方法（主观和客观负荷时间）。
* 如果你加入了一个项目，他们使用tab键进行格式化，而你使用空格键，你会做什么？
* 写一个简单的幻灯片
* 你使用什么工具来测试代码性能？
* 如果你今年能掌握一门技术，它会是什么？
* Long-Polling（长轮询）、Websockets、SSE之间的差异是什么？
* 解释标准的重要性。
* FOUC是什么？如何避免FOUC？
* 尽量详细地描述从输入一个网站的URL到页面完成加载的过程。
* 解释什么是ARIA和screenreaders，和提高网站可读性的办法。
* 比较一下CSS动画和JavaScript动画优、缺点的
* 解释下面的请求和响应头：
    * Expires、Date、Age、If-Modified- 的区别
    * DNT
    * Cache-Control
    * Transfer-Encoding
    * ETag
    * X-Frame-Options

#HTML 问题
* 什么是`doctype`？
* 标准模式和兼容模式之间的区别是什么？
* XHTML页面的局限性是什么？
* 页面使用application/xhtml+xml有什么问题？
* 如何解决网站多语言问题？
* 开发复杂网站必须考虑哪些事情？
* `data-`属性有好处？
* HTML5作为一个开放的网络平台。HTML5的基石是什么？
* 描述cookies、localStorage、sessionstorage之间的差异。
* 解释GET和POST的区别
* 描述`<script>`、`<script async>`、`<script defer>`之间的差异。

#CSS 问题
* CSS 的 class 和 id 的有什么区别？
* 描述 `reset` CSS文件的作用和好处。
* 描述什么是`Floats（浮动）`和它们是如何工作的。
* 描述`z-index`属性和叠加的内容如何显示。
* 描述各种清除浮动的方法和适合的场景
* 解释 CSS sprites，你是如何在网站中使用的？
* 你最喜欢的图片替代技术什么是，什么时候使用？
* CSS属性的hack技术有哪些？
* 你是如何处理对新技术有限制的浏览器？
    * 你用了什么技术、处理方式？
* 在视觉上隐藏内容（并使其可用于屏幕阅读器）的方法有哪些？
* 你使用过的网格系统（grid system）吗？如果用过，你喜欢什么？
* 你有使用过适合媒体查询或移动特定的布局吗？
* 对SVG有什么认识？
* 如何优化网页打印？
* 编写高效的CSS有什么“陷阱”？
* 使用CSS预处理器的优点/缺点是什么？（Sass, Compass, Stylus, LESS）
    * 描述你喜欢和不喜欢的CSS预处理器。
* 你将如何使用非标准的字体实现一个网页设计的排版？
* 解释浏览器如何对元素与CSS选择器匹配。
* 解释你对盒模型的理解。你如何通过CSS告诉浏览器使用不同的盒模型来渲染你的布* 局。
* `* { box-sizing: border-box; } `有什么用？它的优点是什么？
* `display`属性有哪些值？
* `inline` and `inline-block`之间的区别是什么？
* `relative`、`fixed`、`absolute`、`static`定位的区别？
* CSS的“C”代表Cascading。如何确定指定样式的优先级（举一些例子）？怎么利用这* 个规则？
* 学过或在项目中用过什么CSS框架？（Bootstrap、 PureCSS、Foundation等）
    * 如果可以，你会怎样改变/改善它们？
* 有没有用过新的CSS Flexbox或网格布局？
* 响应设计和自适应设计有什么不同？
* 是否用过视网膜图形？
    * 使用了什么技术？
    
## JS问题
* 解释事件委托（event delegation）
* 解释JavaScript的`this`如何工作的
* 解释原型如何实现继承
* 你如何去测试JavaScript？
* AMD与CommonJS
* 解释为什么下面的函数不是IIFE（Imdiately Invoked Function Expression 立即执行的函数表达式）：`foo() {}（）`
    * 怎样改成IIFE？
* 变量null、undefined、undeclared的区别
    * 你如何检查这些状态？
* 闭包是什么，以及如何使用、为什么使用？
* 一个匿名函数的典型用例是什么？
* 你如何组织你的代码？（模块、模式、经典传继承？）
* 宿主对象（host objects）和本地对象（native objects）的区别是什么？
* 比较下面写法的区别：`function Person(){}`, `var person = Person()`, `var person = new Person()`
* `.call` 和 `.apply`的区别 
* 解释`function.prototype.bind`。
* 你什么时候优化你的代码？
* 你什么时候用`document.write()`？
* 解释特性检测（feature detection）、特征推理（feature inference）、UA字符串（UA string）的不同之处
* 详细解释AJAX。
* 解释JSONP如何工作（以及它为什么不是Ajax）。
* 你有没有使用JavaScript模板？
    你用什么库？（Mustache.js、Handlebars等）
* 解释“hoisting”。
* 描述事件冒泡（event bubbling）。
* “attribute”和“property”的区别是什么？
* 为什么扩展内置的JavaScript对象不是一个好主意？
* document load事件和document ready事件之间的区别？
* `==` 和 `===`的区别？
* 解释JavaScript的同源策略
* 实现这个功能：
```
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
* 什么是`三元表达式`，`三元`意味着什么？
* 什么是“use strict（使用严格的）”？它的优点和缺点是什么？
* 创建一个循环，循环到100，当数字是3的倍数时输出“fizz”，是5的倍数和同时是3和5的倍数时输出“FizzBuzz”
* 为什么一般来说，不要随便创建全局变量？

#jQuery 问题
* 解释“chaining(链式)”。
* 解释“deferreds（延时）”。
* 你知道哪些jQuery特定的优化？
* `end()`有什么用？
* 说出4种可以传给jQuery方法的值。
    * Selector (string), HTML (string), Callback (function), HTML element, object, array, element array, jQuery Object等等。
* `.get()`、`[]`、`.eq()`的区别是什么？

## 编程问题

* 实现
```
add(2, 5); // 7
add(2)(5); // 7
```
* 返回什么值？
```
"i'm a lasagna hog".split("").reverse().join("");
```

* window.foo的值是什么
```
( window.foo || ( window.foo = "bar" ) );
```    

* 会alert什么值？
```
var foo = "Hello"; 
(function() { 
  var bar = " World"; 
  alert(foo + bar); 
})(); 
alert(foo + bar);
```

* foo.length的值是多少
```
var foo = [];
foo.push(1);
foo.push(2);
```

#有趣的问题
* 你最近在做什么有意思的项目？
* 你喜欢哪些开发工具？
* 你有做业余项目吗？什么样的？
* 你最喜欢Internet Explorer的什么功能？
* 你喜欢什么样的咖啡？

> 项目地址：[Github][1]

> 本文是我为 [SegmentFault](http://segmentfault.com/a/1190000002513251) 所译

  [1]: https://github.com/h5bp/Front-end-Developer-Interview-Questions

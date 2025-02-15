#前端开发面试题 （题目列表页）


## <a name='list'>目录</a>

  1. [前言](#preface)
  1. [HTML部分](#html)
  1. [CSS部分](#css)
  1. [JavaScript部分](#js)
  1. [其他问题](#other)
  1. [前端学习网站推荐](#web)



## <a name='preface'>前言</a>

 [前言](https://github.com/markyun/My-blog/tree/master/Front-end-Developer-Questions "前言")

## <a name='html'>HTML</a>

- Doctype作用？严格模式与混杂模式如何区分？它们有何意义?

- HTML5 为什么只需要写 <!DOCTYPE HTML>？

- 行内元素有哪些？块级元素有哪些？ 空(void)元素有那些？

- 页面导入样式时，使用link和@import有什么区别？

- 介绍一下你对浏览器内核的理解？

- 常见的浏览器内核有哪些？

- html5有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分 HTML 和
HTML5？

- 简述一下你对HTML语义化的理解？

- HTML5的离线储存怎么使用，工作原理能不能解释一下？

- 浏览器是怎么对HTML5的离线储存资源进行管理和加载的呢？

- 请描述一下 cookies，sessionStorage 和 localStorage 的区别？

- iframe有那些缺点？

- Label的作用是什么？是怎么用的？（加 for 或 包裹）

- HTML5的form如何关闭自动完成功能？给不想要提示的input是设置autocomplete=off即可

- 如何实现浏览器内多个标签页之间的通信? (阿里)

- 如何使用websocket？如何兼容低浏览器？(阿里)

- 页面可见性（Page Visibility）API 可以有哪些用途？

- 如何在页面上实现一个圆形的可点击区域？

## <a name='css'>CSS</a>

- 介绍一下标准的CSS的盒子模型？与低版本IE的盒子模型有什么不同的？

- CSS选择符有哪些？哪些属性可以继承？
 
- CSS优先级算法如何计算？ 

- CSS3新增伪类有那些？

- 如何居中div？如何居中一个浮动元素？

- display有哪些值？说明他们的作用。position的值relative和absolute定位原点是？

- CSS3有哪些新特性（包含哪些模块）？

- 请解释一下CSS3的Flexbox（弹性盒布局模型）,以及适用场景？

- 用纯CSS创建一个三角形的原理是什么？

- 一个满屏 品 字布局 如何设计?

- li与li之间有看不见的空白间隔是什么原因引起的？有什么解决办法？

- 经常遇到的浏览器的兼容性有哪些？原因，解决方法是什么，常用hack的技巧 ？

- 为什么要初始化CSS样式。

- absolute的containing block计算方式跟正常流有什么不同？

- CSS里的visibility属性有个collapse属性值是干嘛用的？在不同浏览器下以后什么区别？

- position跟display、margin collapse、overflow、float这些特性相互叠加后会怎么样？

- 对BFC规范的理解？

- CSS权重优先级是如何计算的？

- 请解释一下浮动和它的工作原理？清除浮动的技巧

- 移动端的布局用过媒体查询吗？

- 使用 CSS 预处理器吗？喜欢那个，Why？

- CSS优化、提高性能的方法有哪些？

- 浏览器是怎样解析CSS选择器的？

- 在网页中的应该使用奇数还是偶数的字体？为什么呢？

- margin和padding分别适合什么场景使用？

- 元素竖向的百分比设定是相对于容器的高度吗？

- 全屏滚动的原理是什么？用到了CSS的那些属性？

- 什么是响应式设计？响应式设计的基本原理是什么？如何兼容低版本的IE？

- 视差滚动效果，如何给每页做不同的动画？（回到顶部，向下滑动要再次出现，和只出现一次分别怎么做？）

- ::before 和 :after中双冒号和单冒号 有什么区别？解释一下这2个伪元素的作用。

- 如何修改chrome记住密码后自动填充表单的黄色背景 ？

- 你对line-height是如何理解的？

- 设置元素浮动后，该元素的display值是多少？（自动变成display:block）

- 怎么让Chrome支持小于12px 的文字？

- 让页面里的字体变清晰，变细用CSS怎么做？（-webkit-font-smoothing: antialiased;）

- font-style属性可以让它赋值为“oblique” oblique是什么意思？

- position:fixed;在android下无效怎么处理？

- 如果需要手动写动画，你认为最小时间间隔是多久，为什么？（阿里）

- display:inline-block 什么时候会显示间隙？(携程)

- overflow: scroll时不能平滑滚动的问题怎么处理？

- 有一个高度自适应的div，里面有两个div，一个高度100px，希望另一个填满剩下的高度。

## <a name='js'>JavaScript</a>

-  用原生JavaScript的实现过什么功能吗？

-  介绍JavaScript的基本数据类型。

-  说说写JavaScript的基本规范？

-  请解释一下JavaScript原型(prototype)? 每个JS对象都有原型属性吗？

-  JavaScript有几种类型值？（堆：原始值和 栈：引用值），你能画一下他们的内存图吗？

-  Javascript如何实现继承？

-  如何创建一个对象? （画出此对象的内存图）

-  谈谈This对象的理解。

-  eval是做什么的？

-  什么是window对象? 什么是document对象?

-  null，undefined的区别？

-  写一个通用的事件侦听器函数(机试题)。

-  ["1", "2", "3"].map(parseInt) 答案是多少？

-  关于事件，IE与火狐的事件机制有什么区别？ 如何阻止冒泡？

-  什么是闭包（closure），为什么要用它？

-  "use strict";是什么意思 ? 使用它的有什么好处或坏处？

-  如何判断一个对象是否属于某个类？

-  new操作符具体干了什么呢?

-  Javascript中，有一个函数，执行时对象查找时，永远不会去查找原型，这个函数是？

-  对JSON的了解？

-  `[].forEach.call($$("*"),function(a){
  a.style.outline="1px solid #"+(~~(Math.random()*(1<<24))).toString(16)
})` 能解释一下这段代码的意思吗？

-  js延迟加载的方式有哪些？

-  ajax是什么，解释一下它的工作原理?

-  同步和异步的区别?

-  如何解决跨域问题?

-  JS模块化开发怎么做？

-  requireJS的核心原理是什么？（如何动态加载的？如何避免多次加载的？如何
缓存的？）

-  谈一谈你对ECMAScript6的了解？

-  ECMAScript6 怎么写class么，为什么会出现class这种东西? 

-  AMD（Modules/Asynchronous-Definition）、CMD（Common Module Definition）规范区别？

-  异步加载的方式有哪些？

-  .call() 和 .apply() 的区别？

-  JavaScript中的作用域与变量声明提升？

-  如何编写高性能的Javascript？

-  那些操作会造成内存泄漏？

-  JQuery的源码看过吗？能不能简单概况一下它的实现原理？

-  jQuery.fn的init方法返回的this指的是什么对象？为什么要返回this？

-  jquery中如何将数组转化为json字符串，然后再转化回来？

-  jQuery 的属性拷贝(extend)的实现原理是什么，如何实现深拷贝？ 

-  jquery.extend 与 jquery.fn.extend的区别？

-  jQuery 的队列是如何实现的？队列可以用在哪些地方？

-  谈一下Jquery中的bind(),live(),delegate(),on()的区别？

-  JQuery一个对象可以同时绑定多个事件，这是如何实现的？

-  jQuery 是通过哪个方法和 Sizzle 选择器结合的？（jQuery.fn.find()进入Sizzle）

-  针对 jQuery性能的优化方法？

-  Jquery与jQuery UI有啥区别？

-  jQuery和Zepto的区别？各自的使用场景？

-  Zepto的点透问题如何解决？

-  jQueryUI如何自定义组件?

-  需求：实现一个页面操作不会整页刷新的网站，并且能在浏览器前进、后退时正确响应。给出你的技术实现方案？

-  如何判断当前脚本运行在浏览器还是node环境中？（阿里）

-  移动端最小触控区域是多大？

-  jQuery 的 slideUp动画 ，如果目标元素是被外部事件驱动, 当鼠标快速地连续触发外部元素事件, 动画会滞后的反复执行，该如何处理呢?
-  把 Script 标签 放在页面的最底部的body封闭之前 和封闭之后有什么区别？浏览器会如何解析它们？

-  移动端的点击事件的有延迟，时间是多久，为什么会有？ 怎么解决这个延时？（click 有 300ms 延迟,为了实现safari的双击事件的设计，浏览器要知道你是不是要双击操作。）

-  知道各种JS框架(Angular, Backbone, Ember, React, Meteor, Knockout...)么? 能讲出他们各自的优点和缺点么?
-  Underscore 对哪些 JS 原生对象进行了扩展以及提供了哪些好用的函数方法？

-  Node.js的适用场景？

-  (如果会用node)知道route, middleware, cluster, nodemon, pm2, server-side rendering么?
-  解释一下 Backbone 的 MVC 实现方式？

-  什么是“前端路由”?什么时候适合使用“前端路由”? “前端路由”有哪些优点和缺点?

-  知道什么是webkit么? 知道怎么用浏览器的各种工具来调试和debug代码么?

- 如何测试前端代码么? 知道BDD, TDD, Unit Test么? 知道怎么测试你的前端工程么(mocha, sinon, jasmin, qUnit..)?

- 前端templating(Mustache, underscore, handlebars)是干嘛的, 怎么用?

- 简述一下 Handlebars 的基本用法？

- 简述一下 Handlerbars 的对模板的基本处理流程， 如何编译的？如何缓存的？

- 用js实现千位分隔符?(来源：[前端农民工](http://div.io/topic/744)，提示：正则+replace)

## <a name='other'>其他问题</a>

- 原来公司工作流程是怎么样的，如何与其他人协作的？如何夸部门合作的？

- 你遇到过比较难的技术问题是？你是如何解决的？

- 设计模式 知道什么是singleton, factory, strategy, decrator么?

- 常使用的库有哪些？常用的前端开发工具？开发过什么应用或组件？

- 页面重构怎么操作？

- 列举IE与其他浏览器不一样的特性？

- 99%的网站都需要被重构是那本书上写的？

- 什么叫优雅降级和渐进增强？

- WEB应用从服务器主动推送Data到客户端有那些方式？

- 对Node的优点和缺点提出了自己的看法？

- 你有用过哪些前端性能优化的方法？

- http状态码有那些？分别代表是什么意思？

- 一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么？（流程说的越详细越好）

- 除了前端以外还了解什么其它技术么？你最最厉害的技能是什么？

- 你用的得心应手用的熟练地编辑器&开发环境是什么样子？

- 对前端界面工程师这个职位是怎么样理解的？它的前景会怎么样？

- 你怎么看待Web App 、hybrid App、Native App？

- 你移动端前端开发的理解？（和 Web 前端开发的主要区别是什么？）

- 你对加班的看法？

- 平时如何管理你的项目？

- 每个模块的代码结构都应该比较简单，且每个模块之间的关系也应该非常清晰，随着功能和迭代次数越来越多，你会如何去保持这个状态的？

- Git知道branch, diff, merge么?

- 如何设计突发大规模并发架构？

- 当团队人手不足，把功能代码写完已经需要加班的情况下，你会做前端代码的测试吗？

- 说说最近最流行的一些东西吧？平时常去哪些网站？

- 知道什么是SEO并且怎么优化么? 知道各种meta data的含义么?

- 移动端（Android IOS）怎么做好用户体验?

- 你在现在的团队处于什么样的角色，起到了什么明显的作用？

- 你认为怎样才是全端工程师（Full Stack developer）？

- 介绍一个你最得意的作品吧？

- 你有自己的技术博客吗，常去那些博客？

- 对前端安全有什么看法？

- 最近在学什么东西吗？

- 能谈谈你未来3，5年给自己的规划吗？

## 有趣的问题


- .A、B两人分别在两座岛上。B生病了，A有B所需要的药。C有一艘小船和一个可以上锁的箱子。C愿意在A和B之间运东西，但东西只能放在箱子里。只要箱子没被上锁，C都会偷走箱子里的东西，不管箱子里有什么。如果A和B各自有一把锁和只能开自己那把锁的钥匙，A应该如何把东西安全递交给B？


	    答案：A把药放进箱子，用自己的锁把箱子锁上。B拿到箱子后，再在箱子上加一把自己的锁。
	    箱子运回A后，A取下自己的锁。箱子再运到B手中时，B取下自己的锁，获得药物。

- Amazon主页的左上角有一个商品分类浏览的下拉菜单 没有延迟，而且子菜单也不会在不应该的时候消失。它是怎样做到这一点的呢？

	 	 答案是通过探测鼠标移动的方向和轨迹，具体查看Khan Academy工程师 Ben Kamens 写的 jQuery插件
![这是 Khan Academy工程师 Ben Kamens 写的 jQuery插件](http://a.36krcnd.com/photo/3f716d75a80cdce23c803fc6f088846e.png)


## <a name='web'>前端学习网站推荐</a>
	
	1. 极客标签：     http://www.gbtags.com/

	2. 码农周刊：     http://weekly.manong.io/issues/
	
	3. 前端周刊：     http://www.feweekly.com/issues
	
	4. 慕课网：       http://www.imooc.com/
	
	5. div.io：		 http://div.io 
	
	6. Hacker News： https://news.ycombinator.com/news
	
	7. InfoQ：       http://www.infoq.com/
	
	8. w3cplus：     http://www.w3cplus.com/
	
	9. Stack Overflow： http://stackoverflow.com/
	
	10.w3school：    http://www.w3school.com.cn/

	11.mozilla：     https://developer.mozilla.org/zh-CN/docs/Web/



## <a name='web'>文档推荐</a>

	
1. [jQuery 基本原理](http://docs.huihoo.com/jquery/jquery-fundamentals/zh-cn/index.html "jQuery 基本原理")


2. [JavaScript 秘密花园](http://bonsaiden.github.io/JavaScript-Garden/zh/)


3. [CSS参考手册](http://css.doyoe.com/)



###更新时间:  2015/7/24


	
	资料答案不够正确和全面，欢迎欢迎Star和提交issues。我的微博：http://weibo.com/920802999

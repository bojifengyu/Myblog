我是怎么开始的

自从学习前端开始,就有自己搭建网站的想法,

有了一个目标之后,一切努力都变得顺其自然

于是图书馆埋头苦肝,每天十个小时,

连续奋战一个多月之后

我现在的状态是这样的==>眼眶发黑,头发茂密,面色憔悴

嗯,是程序猿没错了

不过在这一个月里我也对web端到服务端都有了一定的了解,

也具备了搭建一个小型网站的一些技术栈,

于是就开始了浩浩荡荡的面向百度编程项目.

在图书馆和咖啡厅和思源楼(起太晚,图书馆九点就没位置了)奋战N日,

消耗N杯咖啡之后,这个网站终于成型了;

NO wordpress , NO hexo .

It's Slartbartfast'sBlog.

 

网站长什么样
 

前端页面
首页(滚动截屏有一部分图像撕裂了 ) 
![Markdown](http://i1.bvimg.com/658595/aff9cda004c0a4e1.png)


分类页
<img src='http://i1.bvimg.com/658595/327da64aa3a85c1b.png'>


音乐盒 主要是视差效果

![Markdown](http://i1.bvimg.com/658595/ed255702b3b4722ct.jpg)

豆瓣
![Markdown](http://i1.bvimg.com/658595/0e666bf2ef9cb4d2t.jpg)


留言板
![Markdown](http://i1.bvimg.com/658595/f9a3b23bf9e4c779.png)


后台管理系统
登录页
![Markdown](http://i1.bvimg.com/658595/c4e7239e6b7eed10.jpg)


仪表盘
![Markdown](http://i1.bvimg.com/658595/4cf64ec5f7ceca21.jpg)


文章管理
![Markdown](http://i1.bvimg.com/658595/896f1c5a8d95b6d3.jpg)


文章发布

![Markdown](http://i1.bvimg.com/658595/c39a359606d59fd5.jpg)

评论管理
![Markdown](http://i1.bvimg.com/658595/86454361b8125f2e.jpg)


其他的还有 首页轮播图设置 文章编辑页 分类添加 编辑页 以及音乐上传和管理,

都长一个样就不一一列举了

总结用到的技术栈
前端:

主要还是bootstrap和jquery,bootstrap刚开始用的不太熟,

导致重构比较麻烦,现在的页面代码还比较凌乱,不过借用老罗的一句话:又不是不能用.....

等以后学习更深入再把整个网站重构一下吧

有时间,或者学了VUE之后再把整个页面都重构一下

语言:HTML CSS JavaScript

框架:Bootstrap 4.0

语言库:jquery 3.3

模板引擎:jsrender

动画:一部分是自己写的,一部分使用的animate.css和wow.js

分页器和留言系统:自己写的,留言功能没有邮箱提醒,待完善

代码高亮:highlight.js

富文本编辑器:wangEditor

后端:

整个后端完全PHP手撕,没有用框架,以后一定再深入学习,

毕竟一个好的框架能节省不少时间

服务器:Linux Centos 6.0

服务器软件:Apache 2.4

服务端语言:PHP 7.2

数据库:MYSQL 8.0

图表:Echarts

富文本编辑器:wangEditor

页面呈现:

主页 和后端一部分管理页渲染:用PHP进行数据库条件查询

登录页头像预览和评论管理:AJAX

豆瓣影讯:利用豆瓣提供的API 发送跨域请求jsonp用jsrender渲染

感受
我的学习的东西还远远不够,代码的质量也亟待改进,debug的习惯也不是很好,

为一个错误抓耳挠腮半天结果发现是写错一个字母的情况屡屡发生,

页面也是充斥着直男的审美观(以后一定一定一定学习设计)

但是作为自学完成的第一个像样的项目来说,心中还是有些许的成就感的

希望我对技术的这份热情能持续下去吧.

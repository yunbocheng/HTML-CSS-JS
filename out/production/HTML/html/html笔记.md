
## 1. 当前的系统结构有哪些？

存在两种结构 ：

- C/S结构：

  ![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616095108.png)

- B/S结构 ：

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616095214.png)

注释快捷键 ： CtrL+ Shift + /

在HBuilder中，Ctrl + D 删除一行。

缩进 ：往右缩进Tab 往左缩进 ：Shift + Tab

下边这段代码是告知浏览器采用哪一种字符编码方式打开当前文件，这里采用的是UTF-8；

生成注释的快捷键 ：

> ctrl + shift + /

````html
<!--因为我们书写的html代码是以UTF-8进行编码的，如果修改会产生编码异常。-->
<!--由于当前idea工具采用的是字符编码方式是UTF-8-->
<!--所以打开方式也要采用UTF-8的方式-->
<!--总之，这里的字符编码方式一定要和文件自身的编码方式相同才可以-->
<!--编码方式不同可能产生乱码-->

<meta charset="UTF-8">

````

## 2.java工程师的方向

Java软件工程师主要走的是B/S结构的系统。

JavaEE(Java企业版，专门为企业提供解决方案的。)

企业内部的系统一般都是基于B/S结构的。

Java软件工程师以后主要进行java web开发(web指的是网站：企业级的web站点)

对于Java工程师来说主要是对服务端开发，也就是Server端的开发。
但是我们Java软件工程师也要对web前端的技术有所了解。甚至也可以精通web前端，做一个全栈工程师。

运行在Browser(浏览器)中的语言包括哪些？

- HTML
- CSS
- JavaScript

## 3.什么是HTML？

Hyper Text Markup Language ：超文本标记语言。

超文本 ：不是普通文本，例如 ：图片、声音、视频等流媒体数据。（HTML支持流媒体）

标记语言 ：标记语言一般都是由一对一对的标签组成。

成对出现 ：
> <html></html>

以上就是HTML的跟标签。

HTML中大部分的标签都是由开始标签和结束标签组成的，都是成对出现的。

你编写代码的时候也要成对出现，养成好习惯，

所有的结束标签开始的第一个字符都是正斜杠：/ 

## 4.HTML怎么开发，怎么运行

怎么开发 ：

- 只要创建一个xxx.html 或者 xxx.htm 文件，

怎么运行 ：

- 然后使用记事本打开，直接编写代码即可。

HTML开发有没有很棒的集成开发环境 ？

- 网页制作三剑客之一：DreamWeaver
- HBuilder 也是一个不错的前端开发工具
- WebStorm 也是一个不错的前端开发工具
- IntelliJ IDEA 工具也可以进行前端的开发。

## 5.开发第一个HTML页面 

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616102408.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616104211.png)

## 6.HTML笔记

6.1 什么是HTML？

   Hyper Text Markup Language  超文本标记语言。

   超文本：超级文本，例如：流媒体、声音、视频、图片等。

   标记语言：这种语言是由大量的标签组成。

   	任何一个标签都有开始标签和结束标签，例如：
   	
   	<标签> 	： 开始标签
   	
   	</标签>	:	结束标签
   	
   	HTML严格意义上来说只能说是一种规范，一种在浏览器上的规范。

   标签语言，不能称为编程语言，因为HTML中没有变量、数据类型、控制语句if、for。



6.2 HTML运行在哪里？
   运行在浏览器上。

6.3 世界上五大主流浏览器：

  - IE：微软的

  - FireFox：火狐（FF）

  - Chrome：谷歌
  - Opera：欧朋
  - Safari：MAC os专用（苹果专用的浏览器）

6.4 国内前端程序员主要安装的三个：

  - IE
  - FF
  - Chrome

   前端的程序员开发完成之后需要在不同的浏览器上运行程序，以便发现兼容问题。

6.5 HTML怎么开发？

   新建一个.html或者.htm结尾的文件。

   使用记事本打开就能开发，浏览器打开就能运行，不需要编译。

6.6 什么是web？

  - web前端程序员：

    需要精通：html  css javaScript

    web前端主要负责的是：前端浏览器展示的效果，客户要求：要炫酷、要震撼...

    web前端页面展示的时候，是需要动态的数据的，这些都是后台java程序或者C++程序

  - web后台程序员：
    需要精通：这个不一定，后台有可能是C语言，也可能是C++，也可能是Java，也能是PHP

6.7 这种系统架构被称为：B/S结构系统。

   B : Browser（浏览器）

   S : Server（服务器）

6.8 HTML是哪个组织制定的标准呢？

W3C组织是对网络标准制定的一个非盈利组织，W3C是World Wide Web Consortium（万维网	联盟）的缩写。
像HTML、XHTML、CSS、XML的标准就是由W3C来定制。

tim berners-lee 万维网联盟创始人（万维网之父）。

以为有了他才有了现如今的互联网时代，他让我们可以上网了。

HTTP协议：超文本传输协议，也是w3c制定的。

HTTP协议是一种什么协议？
    浏览器和web服务器传消息的协议。

6.9 B/S架构的原理（粗略的描述一下，三步骤）：

 1. 用户在浏览器地址栏上输入URL。（例如：http://www.baidu.com）

 2. 回车（这一步相当于通过浏览器向服务器发送一个请求）

    请求：request   Browser--> Server （请求是浏览器向服务器发送数据）

 3. 服务器会给浏览器一个响应，最终响应一段HTML代码给浏览器，浏览器对HTML代码进行展示一个结果。

    响应：response  Server --> Browser （响应是服务器向浏览器发送数据）

    

**重点**： 到目前为止，浏览器向服务器发送请求有两种方式：

- 用户直接在浏览器的地址栏输入URL，回车。
- 用户直接在网页上点击超链接。

以上两种方式在本质上是没有区别的，但是第二种方式更加简单，傻瓜式。



## 7.HTML中的基本标签

7.1 段落标记
<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616104755.png" style="zoom: 50%;" />

7.2 标题标记
<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616104955.png" style="zoom:50%;" />

显示的结果(在网页中的显示)
<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616105045.png" style="zoom:50%;" />

7.3 换行

<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616105722.png" style="zoom:50%;" />

显示的结果(在网页中的显示) ：
<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616105747.png" style="zoom:50%;" />

7.4 水平线

<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616110205.png" style="zoom:50%;" />

显示的结果(在网页中的显示) ：
![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616110326.png)

7.5 预留格式 

<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616110500.png" style="zoom:50%;" />

显示结果(在网页中的显示) ：
<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616110538.png" style="zoom:50%;" />

7.6 字体格式 ：

<img src="https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616111033.png" style="zoom:50%;" />

显示结果(在网页中显示)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616111058.png)

## 8.实体标签 

8.1 空格

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616111943.png)

显示结果(在网页中显示)
![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616111911.png)

8.2 大于小于符号

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616112048.png)

显示结果(在网页中显示)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616112141.png)

8.3 基本表格 

表格的样子以及 列的简称与单元格中数据的简称

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616113145.png)

在HTML代码中创建一个表格

此时创建的是一个3行3列的表格
![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616122128.png)

显示结果(在网页中显示)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616113416.png)

8.4 单元格合并

原理以及合并的方法名称 ：

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616123130.png)

行合并 ：

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616123158.png)

列合并 ：

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616123329.png)

显示的结果(在网页中显示)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616123423.png)

8.5 th标签

这个没有使用th标签

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616124813.png)
![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616124944.png)


这个是没有使用th标签是的显示结果

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616124626.png)

这个是使用th的标签，将表格中的第一列改为th标签

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616125017.png)

显示结果(在网页中显示)
![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616125117.png)

8.6 表的三部分
<tbody> <tfoot> <thead>标签

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616171220.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616171305.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616171348.png)

8.7 背景颜色和图片

如果图片太小，一张不够铺满整个网页背景，会拼接好几张图片，把背景铺满。

注意 ：此时的图片是嵌入到背景当中，不会跟随网页界面浮动
![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616172243.png)

8.8 图片 

此时的图片是插入进去的，不是背景图片，会随着网页进行浮动，

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616174631.png)

显示的结果(在网页上显示)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616174708.png)

8.9 HTML的超链接

超链接在 HTML 中非常的重要 :
![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210616175249.png)

8.10 HTML超链接2

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210617101758.png)

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210617101825.png)

8.11 超链接target属性

笔记见 htmlTestO4.html 和 htmlTest05.html

HTML页面中的id：

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210621112925.png)

HTML文档：

文档对应的单词是 ：docunment

所以说HTML文档又叫做：DOM树。

javascript可以对DOM树上的节点进行增删改查操作。

div（盒子）布局：

DIV盒子独占一行。

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210621121805.png)

SPAN盒子不会独自占用一行

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210621122525.png)


方便操作是因为每个盒子(div)存在位置元素，及坐标，X轴与Y轴，输入坐标值之后，

这个盒子(div)的位置就不会移动，就去顶在网页中的某一个位置。可以在任意的位置进行插入盒子，灵活。

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210621115312.png)

还可以叠加在一起进行嵌套

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210621120336.png)


以前的table布局 ：

只能按照提前画好的表格的格子里进行填写，不能压线进行创建，不灵活，不可以随意位置创建。

![](https://gitee.com/YunboCheng/imageBad/raw/master/image/20210621115604.png)








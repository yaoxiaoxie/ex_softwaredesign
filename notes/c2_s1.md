# 组件技术

## 计算机学院

耿军雪

Component-Oriented Programming 西安工業大學

XIAN TECHNOLOGICAL UNIVERSITY

## JAVA EE WEB学习重点

## Java应用程序基础

1．Java语言基础

2．Java面向对象编程

3．Java多线程编程

4．Java图形界面与事

件响应

B／S Web开发基础

5．网页前台1

Applet/JavaScript

6．网页后台

JSP

Servlet

7．数据库连接

JDBC

8. JavaBeans

9．网页前台2-Ajax

10．EL／JSTL标签

### Web开发主流框架

11. Struts2.x

12.Hibernate

13. Spring

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/3a116655527d03bf)

B／S编程模式简介

HTML和HTTP

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/e3904afcd8f157bf)

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/83606c1819ca0cd9)

动态web编程

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/31beaf57af52a3e3)

Servlet基础

Servlet开发

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/d51c4077cc4d9d6f)

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/0ea9c7dfc7d39c7e)

会话技术

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

### 软件编程体系

B／S结构 C／S结构

(Brower/Server) (Client/Server)

浏览器端：HTML／CSS／


<table border="1" ><tr>
<td colspan="1" rowspan="1">C／S结构：VB/VC/VC#/Delphi/Java/.NET系列</td>
</tr></table>

JavaScript/VBScript

服务器端：

ASP(.NET)PHP/JSP

数据库支持：SQL Server／Oracle／Sybase／MySQL／Informix

两大语法体系：

Basic系：VB／VBScript／ASP（VBScript）／VB.NET／VBA

C系：Java／JavaScript／C＋＋／C＃／PHP／JSP／ASP（JScript）

Component-Oriented Programming 西安工黄大學XIAN TECHNOLOGICAL UNIVERSITY

C／S结构：即Client／Server结构，指应用程序由服务器端程序和客户端程序两部分构成，客户端具有独立的处理功能，同时可以通过网络与服务器端通信，进行协同处理。

C／S结构的优势：C／S结构程序的主要处理功能一般是在客户端，充分发挥了分布式计算的优势，服务器端一般不会成为性能的瓶颈；客户端由用户定制开发，可以实现任意复杂的处理功能。

C／S结构的劣势：客户端需要专门安装，对于不熟悉计算机操作的用户来说难度很大；升级很不方便，一旦程序发生变动，所有客户端都需要升级，维护工作量很大。

<!-- 客户端 TCP Socket UDP Socket 服务器 端程序  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/71bf4b8e95b1c196)

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY/

### B／S架构编程体系

B／S结构：即Browser／Server结构，应用程序同样由客户端和服务器端两部分组成；但客户端一般使用通用的浏览器，只负责用户与服务器的交互，处理能力有限；绝大多数处理功能都运行在服务器端。

B／S结构的优势：B／S结构程序的主要处理功能都运行在服务器端，客户端一般不需要安装特别的软件，只要使用通用的Web浏览器即可（例如IE）；软件升级时只需在服务器端更新程序即可，不需考虑客户端。

B／S结构的劣势：由于绝大多数处理功能都由服务器端承担，所以服务器的负担沉重，容易成为性能的瓶颈；客户端使用了通用的软件，功能十分有限，很多在Client中很容易实现的功能却很难在Browser中实现（例如绘图）；另外，B／S结构程序的运行效率一般都不高。

<!-- 客户端 浏览器 HTTP WEB 服务器 HTTP 客户端 浏览器 服务器 端程序  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/93bf8b8c9995ffec)

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

### B／S架构编程体系

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/916b1c7f958ae9f0)

### B／S结构的编程语言

## 浏览器端编程语言

·HTML（Hypertext Markup Language，超文本标记语言）

·CSS （Cascading Style Sheets，层叠样式表单）

·JavaScript语言

·VBScript语言

 服务器端编程语言

·ASP、JSP和PHP

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

B／S编程模式简介

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/495dab0d65655124)

# Web服务器

Web服务器接收客户端的请求并将结果返回客户端

结果：HTML页面、图片、文件、.....

<!-- 客户端请求包括其想要的 东西的名字和地址（URL） 服务器上有许多可 以传送到客户端的 request “内容”，如wel页 Web 面、图片、文件等 browser response Client Server 服务器响应中包含客户端想 要的文档或一个错误代码（如 果服务器无法处理请求）  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/da4666953c770996)

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

# B／S编程模式简介

## Web客户端

 Web客户端可以使用户向服务器提出请求，并向用户展现请求的结果

 浏览器知道如何与服务器通信，并能够解释HTML代码并展现Web页。

<!-- 用户在浏览器 服务器查找 上点击链接 浏览器格式化请求 相应的页面 click 并传送至服务器 浏 览器获得H7M＿ Browser Server 并展示给用户 服务器格式化响应并 发送至客户端浏览器 Browser Component-Oriented Programming Server  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/8e43a9803c32eb0f)

<!-- 西安工業大學 XIAN TECHNOLOGICAL UNIVERSITY/  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/a62edc8e0b04c4e1)

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/d4cd7d6e33e3517a)

请求／响应方式（地址栏、超链接、表单请求）

HTML告诉浏览器怎样为用户显示内容

 HTTP是客户端和浏览器在Web上通信的协议

 服务器使用HTTP向客户端发送HTML

<!-- 建立连接 发出请求信息 回送响应信息 关闭连接 客户机 服务器  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/b144d44db76caa04)

HTML (Exercise)

HTTP

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/fc8cf81c70a92aaa)

是TCP／IP协议集中的一个应用层协议，用于定义WEB浏览器与WEB 服务器之间交换数据的过程以及数据本身的格式.

·Http1.0的会话方式：

会话过程分四个阶段 会话的特点：无状态

1）客户机打开到服务器的连接

2）客户机向服务器发出请求request

1）浏览器与WEB服务器的连接过程是短暂的，每次连接只处理一个请求和响应。对每一个页面的访问，浏览器与WEB服务器都要建立一次单独的连接。

3）服务器响应该请求response

4）连接关闭

2）浏览器到WEB服务器之间的所有通讯都是完全独立分开的请求和响应对。 西安工業大學

Component-Oriented Programming

XIAN TECHNOLOGICAL UNIVERSITY

## ·Http1.1会话：

在一个TCP连接上可以传送多个HTTP请求和响应

多个请求和响应过程可以重叠进行

<!-- 建立连接 发出第1次请求 发出第n次请求 回送第1次响应 回送第n次响应 发出关闭连接请求 关闭连接 客户机 服务器  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/d69fd3ebda0733d2)

增加了更多的请求头和响应头

 HTTP请求包括：HTTP方法（执行的动作）、访问的页面URL、表单参数

 请求消息结构：

一个请求行、若干消息头、以及实体内容。其中的一些消息头和实体内容都是可选的，消息头和实体内容之间要用空行隔开

##  HTTP 1.1 method

·告诉服务器请求的类型，剩余的消息是如何被格式化的

·GET,PUT, POST, TRACE, DELETE, OPTIONS, HEAD,CONNECT

·GET

-是最简单的请求，它向服务器获取一个资源并将之发回

-可以用HTTPGET向服务器发送少量的数据

-一个GET例子

## Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

In a GET request, parameters lif there ar any) are appended to the The path The protocol version he path to the first part of the request URL,resource on the that the web browser starting with a "?". Parameters are web server. is requesting.separated with an ampersand "&".

The HTTP

The Request line.Method.

GET/select/selectBeerTaste.jsp?color=dark&taste=malty HTTP/1.1

Host:www.wickedlysmart.com

User-Agent: Mozilla/5.0 (Macintosh; U; PPC Mac OS X Mach-O;en-US;rv:1.4) Gecko/20030624 Netscape/7.1

The Request headers. Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/

plain;q=0.8,video/x-mng,image/png,image/jpeg,image/gifq=0.2,*/*;q=0.1

Accept-Language: en-us,en;q=0.5

Accept-Encoding: gzip,deflate

Accept-Charset: ISO-8859-1,utf-8$;q=0.7;^{*};q=0.7$

Keep-Alive:300

Connection: keep-alive

Component-Oriented Programming 西安工業大學

XIAN TECHNOLOGICAL UNIVERSITY

## HTTP GET

<!-- 嘿，服务器给我get一下这个 主机上的一个页面，地址是 ／select／selectBeerTaste.jsp，哦 ，对了，这有一些给你的参数 ，还有请快一点 好的，我会去拿那个页面 ，也谢谢你提供的参数。 不过有一点要说明，“快 一点”可不是HTTP协议的 要求 客户 HTTP 请求 (GET) 服务器 Component-Oriented Programming 西安工業大學  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/7bbf144699acd0ff)

XIAN TECHNOLOGICAL UNIVERSITY

# ·POST

## -向服务器请求资源，同时可以发送一些表单数据

<!-- -一个POST例子 The HTTP The protocol version Method. The path to the resource that the web on the web server. browser is requesting. The Request line. POST/advisor/selectBeerTaste.do HTTP/1.1 Host:www.wickedlysmart.com User-Agent: Mozilla/5.0 (Macintosh; U; PPC Mac OS X Mach-O; en-US; rv:1.4) Gecko/ The Request 20030624 Netscape/7.1 headers. Accept: text/xml,application/xml,application/xhtml+xml,text/html; q=0.9,text/ plain;q=0.8,video/x-mng,image/png,image/jpeg,image/gif ;q=0.2,*/*;q=0.1 Accept-Language: en-us,en;q=0.5 Accept-Encoding: gzip,deflate Accept-Charset: ISO-8859-1,utf-8;q=0.7,*;q=0.7 Keep-Alive:300 Connection: keep-alive This time, the parameters are down here The message body, in the body, so they aren't limited the sometimes called color=dark&taste=malty way they are if you use a GET and have the "payload". to put them in the Request line. Component-  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/84d27e0103e51e7e)

<!-- 西安フ烹ナ XIAN TECHNOLOGICAL UNIVERSITY  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/b23cb7fef525621a)

<!-- 嘿，服务器请把这个请求 POST到下面的资源，地址是 /advisor/selectBeerTaste.do, 不要忘了看看消息体，里面有 我发送的一些重要数据。 好的，我会去找那个资源 （其实这是一个小应用） ，等我找到了，我会把你 在请求体里发送的数据提 供给它 HTTP 请求 客户 (POST) 服务器 Component-Oriented Programming 西安工業大學  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/da2d68fa8a367d9d)

XIAN TECHNOLOGICAL UNIVERSITY

示例

<!-- factors of 25.0: 1525  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/dd39e45cf23c5c11)


<table border="1" ><tr>
<td colspan="1" rowspan="1">http://localhost:8080/MyServletApp/ComputerFactorandPrimNumber</td>
</tr></table>


<table border="1" ><tr>
<td colspan="1" rowspan="1">25</td>
<td colspan="1" rowspan="1">提交输入一个数，提交给 servlet（G</td>
</tr><tr>
<td colspan="1" rowspan="1">25</td>
<td colspan="1" rowspan="1">提交</td>
</tr></table>

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/f3c6fd1db0f2bd0e)

http://localhost:8080/MyServletApp/ComputerFactorandPrimNumber?number=25

Primnumbers less 25.0 :

1 2 3 5 7 11 13 17 19 23

Component Object Model 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

## ·http请求小结：

通过地址栏发出的请求总是Get请求

Form表单的请求分两种情况：

Method="Get"

Method="Post"

-示例：

- &lt;form name="frmLogin” method="get"action="chklog.jsp"&gt;

- &lt;form name="frmLogin”method="post" $\arctan="chk\log.jsp^{\prime\prime}>$

## ·发送数据用POST不用GET的理由

-数据大小：GET中的字符量按服务器不同有限制

-安全性：用GET发送的数据被附加到URL后面，任何人可以看到。不适于发送敏感数据

## Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

HTTP响应包括：状态码（请求是否成功）、内容类型（text／picture／HTML，etc）、内容（实际的HTML，image，etc）

The protocol version that The HTTP status status code the web server is using. for the Response. A text vext version of

the status code.

HTTP/1.1 200 OK

Set-Cookie: JSESSIONID=0AAB6C8DE415E2E5F307CF334BFCA0C1; Path=/testEL

HTTP Content-Type: text/html

Response Content-Length: 397 value is known as a MIME type. The The content-type response head pe response header's headers. Date: Wed, 19 Nov 2003 03:25:40 GMT MIME type tells the browser what kind of data the browser is about to receive so that the browser will know how to render it.

Server: Apache-Coyote/1.1

Connection: close

body holds the The body holds t &lt;html&gt;HTML, or other ···content to be &lt;/html&gt;rendered...

Component-Oriented Programming 西安工業大學

XIAN TECHNOLOGICAL UNIVERSITY

## ·响应状态码：

响应状态码用于表示服务器对请求的各种不同处理结果和状态，它是一个三位的十进制数。响应状态码可归为5种类别，使用最高位为1到5来进行分类，如下：

1）100～199：表示成功接收请求，要求客户端继续提交下一次请求才能完成整个处理过程。

2）200～299：表示成功接收请求并已完成整个处理过程。

3）300～399：为完成请求，客户需进一步细化请求。例如，请求的资源已经移动一个新地址。 200-OK

4）400～499：客户端的请求有错误。

5）500～599：服务器端出现错误。

<!-- 301- Moved Permanently 400 - Bad Request 401 - Unauthorized 状态码 403-Forbidden 404- Not Found 405- Method Not Allowed 500- Internal Server Error 503-Service Unavailable  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/06eddeafebe4c14a)

## Component-Oriented Programming

# 常见的两种动态Web需求

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/fc45e85261573d31)

 动态内容

 在服务器上储存数据

Web服务器应用程序“看到”该请求是给一个帮助程序的，所以web服务器加载并执行该程序。Web服务器应用程序同时以GET 或POST形式发送参数web server machine

# 基本原理

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/bce123053c1d670b)

<!-- 用户点击一个URL链接 到一个web服务器应用程 序，而不是静态页面 ① ② Web browaer params HPb ④ web server Client app helper app </et 关闭帮助程序，客户端获得 ③ HTML页面，显示动态内容  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/8856f79d0d6de210)

帮助程序构建页面并以

HTML发送回服务器

## Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

## 静态页面

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/6dd4885ade66a991)

服务者尽可能将信息发布给所有用户

信息以静态HTML页面形式传递给用户

》所有用户只能看到相同内容

Network

<!-- Client Web Browser HTTP Response  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/a633b64ac6029d48)

<!-- HTTP Request Server Web Server File System  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/ada5e5c2260dde8b)

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

# 基于Applet的动态页面

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/6dd9e46d83f75ee9)

# 可为不同用户提供不同数据

不能访问后台系统数据

<!-- Client Network Server Web Browser HTTP Request with JVM HTTP Response Web Server File System  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/9ed38e217905b107)

Component-Oriented Programming 西安工業大學XIAN TECHNOLOGICAL UNIVERSITY

# Web应用程序的演化

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/a75be9c92cd2da96)

## Servlet

Web容器可提供服务器端部件来生成动态内容

Servlet不能将业务逻辑和表示逻辑很好分离

<!-- Client HTTP Request Server Web Browser Network Web Server Plugin Requests Requests for HTTP for static dynamic resources resources Response Dynamic Web Server response 它可以读取客户端发送来的显式数据，比如表单数据 可以读取客户端发送来的隐式数据，比如请求报头 File System Web Container  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/bbcd5832703327f9)

可以产生纯文本信息（这个功能不常用）

生成相应结果

发送显式数据给客户（HTML；XML）

发送隐式数据给客户（状态代码；响应报头）

Component-Oriented Programming 西安工業大學XIANTECHNOLOGICAL UNIVERSITY

# Web应用程序的演化

<!-- 由于Servlet内部以线程方式提供 客户端 服务器端 服务，不必对于每个请求都启动一 个进程，并且利用多线程机制可以 同时为多个请求服务，因此 HTTP请求 Servlet的效率非常高。 Web 浏览器 请求动态资源 Web服务器插件 请求静态资源 动态响应 HTTP响应 Web 服务器 Web容器 Java Servlet也是利用输出 HTML语句来实现动态网页的 ，如果用它来开发整个网站 ，动态部分和静态页面的整 文件系统 合过程将变得无法想象。  -->
![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/0c995bedaaf5ef55)

C 工業大學

![](https://textin-image-store-1303028177.cos.ap-shanghai.myqcloud.com/external/54ffe3fd475f2821)

XIAN TECHNOLOGICAL UNIVERSITY


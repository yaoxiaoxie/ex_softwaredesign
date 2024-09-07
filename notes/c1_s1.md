# 组件技术



## 程序设计思想的演化



1）结构化程序设计思想：

（1）自顶向下、逐步求精

（2）语句结构化：顺序、分支、循环语句

（3）模块化

2）面向对象的程序设计思想：

抽象，封装，继承，多态

JAVA，C＋＋语言；

3）事件驱动的程序设计思想：

可视化，事件驱动

仅适用于windows系列操作系统： VB,VC

4）逻辑式对象程序设计思想：

人工智能

Prolog、LISP;

5）并行程序设计思想：

操作系统、优化编译方面的有关知识。

基本的计算要素：任务、进程、线程等基本概念、同步机制和通信操作等。

Pascal,Ada

6）组件技术：

ejb,corba,com/dcom

7）面向方面的编程技术（Aspect Oroented Programming，AOP）消除代码重复的一种方法

AOP实际是GoF设计模式的延续

目前程序设计思想的发展主要是以组件技术和面向方面的编程技术为主要技术。

## 课程简介

组件技术是一种软件开发思想，目前有多种组件技术实现方案，本课程在软件工程理论、高级程序设计语言的基础上，掌握基于Java EE的企业级开发环境、架构和开发技术，掌握面向对象和面向组件的编程思想，熟悉各种面向对象的软件设计模式。

教学目的：拓宽眼界，了解组件这种软件开发思想，学会使用组件的思想、方法指导软件开发.能自主开发或改写一个基于JAVAEE平台的开源组件系统。

## 课程目标

立足于企业级的JAVA EE架构技术，基于组件的软件开发思想。

讲授系统级的开发方法，从需求分析到设计及实现。

通过工程化训练，构筑一个完整的软件系统，实现JAVA EE软件开发全过程

开发基于Struts／Spring／Hibernate／Ajax的网上信息发布平台 

开发基于JSP／Servlet／JavaBean的网上交易系统

使用JSP开发Web应用系统 

使用Java实现面向对象编程 

使用Java语言理解程序逻辑 

HTML JavaScript 数据库 


## 课程内容组织结构

本课程讲授J2EE平台的基本原理及利用J2EE开发企业级应用程序的方法，主要包括如下内容：登录＋注册＋购物车

组件技术基础

Web应用基础 一、1、正确的表单提交

2、带用户名到购物主页

Servlet 二、3、显示上次访问时间，并记录访问次数

JSP 4、session：防止用户非法登录购物主页

Javabean 5、cookie：两周内免登录

JDBC 6、图片验证

MVC设计模式 三、7、JSP＋SERVLET＋JSP

8、注册（复选框获取）

EL和JSTL 四、9、Javabean实现注册

监听器和过滤器 五、10、JDBC（登录＋注册）

多线程 六、11 MVC＋DAO＋JDBC（登录＋注册＋购物）

设计模式基础 七、计数器的四种实现方式

八、留言板（不限实现技术）



总学时40＝32（课堂）＋8（实验）

平时（30％）＋实验（20％）＋期末考试／项目（50％）

## 用一种新的思路来看待问题

多年的发展证明了OO符合软件的规律

## 对象技术的发展需要开发工具和开发语言的支持

在中小规模的软件中，对象和对象之间的协作关系就能够满足需要。但是当软件规模扩大，复杂度上升的时候，面向对象技术强调的协作却表现出另一个极端的特点-耦合度太高导致的复杂度。这时候就需要有一种新的方法来弥补面向对象技术的弱点。

大规模软件主要特点是复杂度。比较典型的例子是集成性的项目。软件系统需要将各种各样的硬件、遗留系统、外部接口整合起来。其间可能遇到不同的硬件接口，不同的操作系统，不同的语言，不同的平台，不同的数据库，不同的消息中间件，不同的网络介质。这些都使得系统变得非常的复杂


# 软件复用（Software Reuse）

软件复用：是将已有软件的各种有关知识用于建立新的软件，以缩减软件开发和维护的费用。

## 代码级别

代码拷贝、粘贴，子程序和函数库，类，类库（不强调关系）

## 设计级别

类层次（类库，强调类之间的关系）、设计模式（设计思想）、设计框架（设计结果）

软件体系结构风格（软件体系结构：构件，连接件，风格）、架构（软件体系结构）

(Design Patterns, Frameworks, Architecture, Style,Component,Connector)


## 需求级别

功能描述（用例use cases模式）

# 子系统级别（组件）

一个独立或相对独立的系统或子系统中的部分功能，体现为组件形式（体系结构中的构件可以是组件，但组件不一定是构件，构件可以是程序模块，组件强调标准的组成形式）（component）


# 软件集成（Software Integration）

软件复用的一种手段

组件技术是基础

已经成为软件生产的一种主要方式

（基于组件的技术）Component Based Technology

90年代软件业的重要进展

复用和集成手段构造新的软件系统

以面向对象方法为基础


基于组件技术的软件开发

软件系统不再是固化的整体系统，灵活性

组件技术是一种社会化的软件开发技术

 不同平台、语言

 不同供应商

## 组件技术必须解决的问题

 复用：功能能被多个系统使用

 集成：不同来源的组件协调工作，完成更复杂的任务

组件技术是继模块化、结构化，面向对象开发方法之后，发展起来的又一个软件开发方法。

 结构化程序设计-以数据为中心

 面向对象程序设计--以对象为中心

 组件程序设计-以组件为中心


## 组件化设计思想

组件的特点什么，优势又是什么，它能带给软件开发者哪些新鲜空气


组件是执行特定处理功能的电路或装置，或可独立运作的软件单元

相同职责、接口的组件可具有不同的内部实现

不同职责的组件结合在一起，可以组成新的组件，而新的组件又可被组织起来，形成新的组件

组件通常会暴露出通用的、标准的、规范的接口，与外界通讯，或供第三方使用

具有同样接口的组件，可以被替换或升级

作为一种独立的产品，组件可被复制，并可在不同的应用中复用

<!-- A 接ロA-C C 接口A-B 接口C-D B Component-Oriented Programming 接口B-E 接口B-D 接口D-E E  -->

组件可被复制、重复利用，降低成本（例如：上传文件或下载文件的java组件，文字编辑器等）

减少异构系统相互集成的难度

由业界专业组织提出开放性标准，具有可扩展性、兼容性

在同一标准的前提下，有利于鼓励不同中间件厂家市场竞争

不同的厂家各尽其责，利用各自优势开发通用的组件


基本概念

组件

 组件的用户：使用组件提供的功能，不需了解组件的具体实现

 组件的设计者：按照组件规范，提供组件的具体实现.

组件框架：组件必须由某个外部代理加载和执行，而且必须向组件提供I／O和通信服务.

 组件必须能够与环境、其他组件进行交互.

 组件框架的设计定义了组件技术的基本特性.

□组件框架的用户：使用框架，创建新应用程序。

很少知道框架的实现，使用框架规范来建立所需的组件交互。

□组件框架的设计者：完全熟悉框架和组件的实现细节。

## 容器：是一个实体，它实现了组件框架并对一个或多个组件集进行维护.

□组件交互：1）组件与容器：交互机制已经标准化



# 组件，框架和容器之间的关系

<!-- 客户端 请求 容器 事件 框架 UI组件 事件处理 流程组件 框架的作用 调用 业务处理 为组件运行提供基 逻辑组件 础服务 数据访问请求 为组件开发提供基 础类 数据组件 调用 数据处理 实现了组件之间的 隔离 支持组件间的协作 管理组件生命周期 数据库 运行于容器之内 Component-Oriented Programming  -->

<!-- 西安工業大學 XIAN TECHNOLOGICAL,UNIVERSITY  -->

## 组件技术的关键特性

（1）组件必须是--个独立编译的程序。它不能是函数库或源代码

（2）必须能够集成组件以创建一个更大的程序，而且无需访问组件的源代码。（说明：如果没有特性（1）和特性（2），那就是在研究函数库技术，而非研究组件技术）

（3）组件必须能够嵌入容器，而且容器必须为组件与容器之间提供通信机制。说明：如果没有特性（3），那就是在研究应用程序，而非研究组件；

（4）组件技术必须支持属性、方法和事件，或者某种等价的通信方法说明：如果没有特性4，则组件技术毫无用处，因为此时无法与组件进行通信；

（5）组件技术应支持持久性属性。在设计时应能够设置属性值，并在激活组件时，能够将设置值作为属性的初始值。

（6）组件应描述其自身接口。应能够通过查询组件来确定它所支持的属性、方法和事件。

（7）组件应可以在各种不同的环境中使用。说明：特性（5）、特性（6）和特性（7）不是组件的本质特性，但如果没有它们，组件编程变得非常困难。


# 组件：定义框架与实现技术

A component model is a definition of properties that components must satisfy, methods and mechanisms for the composition of components.

During the last decades, researchers and practitioners have proposed several component models with different characteristics. A classification of the existing component models is given in 'A Classification Framework for Software Componen tModels**.Examples of component models are:EnterpriseJavaBeans (EJB) model, Component Object Model (COM)model, .NET model, and Common Object Request Broker Architecture (CORBA) component

Model.

IEEE TRANSACTIONS ON SOFTWARE ENGINEERING, VOL. 37, NO. 5, SEPTEMBER/OCTOBER 

<!-- SUN Java Platform Java Bean/EJB CORBA Web Services .NET COM/DCOM/COM+ Microsoft.Net Platform Microsoft Win32 Platform  -->

Component-Oriented Programming

<!-- 西安工業大學 XI'AN TECHNOLOGICAL UNIVERSITY  -->


<table border="1" ><tr>
<td colspan="1" rowspan="1">特性</td>
<td colspan="1" rowspan="1">J2EE</td>
<td colspan="1" rowspan="1">.NET</td>
</tr><tr>
<td colspan="1" rowspan="1">技术类型</td>
<td colspan="1" rowspan="1">标准规范</td>
<td colspan="1" rowspan="1">产品</td>
</tr><tr>
<td colspan="1" rowspan="1">编程语言</td>
<td colspan="1" rowspan="1">Java</td>
<td colspan="1" rowspan="1">C＃、VB、VC＋＋等</td>
</tr><tr>
<td colspan="1" rowspan="1">开发工具</td>
<td colspan="1" rowspan="1">Eclipse、JBuilder等</td>
<td colspan="1" rowspan="1">Visual Studio</td>
</tr><tr>
<td colspan="1" rowspan="1">运行时环境</td>
<td colspan="1" rowspan="1">JVM</td>
<td colspan="1" rowspan="1">CLR</td>
</tr><tr>
<td colspan="1" rowspan="1">动态web网页</td>
<td colspan="1" rowspan="1">Servlet、JSP</td>
<td colspan="1" rowspan="1">ASP.NET</td>
</tr><tr>
<td colspan="1" rowspan="1">中间层组件</td>
<td colspan="1" rowspan="1">JavaNean、EJB</td>
<td colspan="1" rowspan="1">.NET管理组件</td>
</tr><tr>
<td colspan="1" rowspan="1">数据库存取</td>
<td colspan="1" rowspan="1">JDBC</td>
<td colspan="1" rowspan="1">ADO.NET</td>
</tr><tr>
<td colspan="1" rowspan="1">中间供应商</td>
<td colspan="1" rowspan="1">30+</td>
<td colspan="1" rowspan="1">Microsoft</td>
</tr></table>


基于组件的软件开发

作为一种软件设计思想：细粒度、可重用、易部署、低成本。

作为一种软件实现框架：CORBA，COM，COM＋（DCOM），EJB,Web Service。

作为一种软件应用途径：二次开发控件、插件；接口、对象、库。

Java 2 Platform, Enterprise Edition 

面向组件编程的缩写是COP。COP是对OOP的补充，帮助实现更加优秀的软件结构。组件的粒度可大可小，需要取决于具体的应用。

在COP中有几个重要的概念：

 服务：服务（Service）是一组接口，供客户端程序使用。例如，验证和授权服务，任务调度服务。服务是系统中各个部件相互调用的接口；

 组件：组件（Component）实现了一组服务，此外，组件必须符合容器订立的规范，例如，初始化，配置、销毁

COP是对一种组织代码的思路，尤其是服务和组件这两个概念。在Spring框架中，就采用了COP的思路，将系统看作一个个的组件，通过定义组件之间的协作关系（通过服务）来完成系统的构建。这样做的好处是能够隔离变化，合理的划分系统。而框架的意义就在于定义一个组织组件的方式。

Component-Oriented Programming



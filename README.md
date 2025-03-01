# 0000springboot在线拍卖系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)


### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV16ia6epENY?p=1)

### [其他项目](https://github.com/GraduationProject-springboot) 包安装运行

# 系统概述
## 1.1 概述
`　`随着社会的快速发展，计算机的影响是全面且深入的。人们的生活水平不断提高，日常生活中人们对在线拍卖系统方面的要求也在不断提高，在线拍卖受到广大用户的关注，使得在线拍卖系统的开发成为必需而且紧迫的事情。在线拍卖系统主要是借助计算机，通过对在线拍卖系统所需的信息管理，增加用户选择，同时也方便对广大用户信息的及时查询、修改以及对用户信息的及时了解。在线拍卖系统对用户带来了更多的便利, 该系统通过和数据库管理系统软件协作来满足用户的需求。
## 1.2课题意义
随着全球信息化的发展，人们的生活节奏越来越快，对信息的时效性越来越重视。以传统的宣传方式为载体的传统媒介早已不能满足用户对获取信息的方式、便捷性的需求。所以在线拍卖系统渐渐成为用户关注的焦点。首先，在线拍卖系统，网上获取信息的实时性、便捷性要远远高于传统媒介。系统一经上线，无论用户在世界的哪个角落，只要能够连接互联网，就能在第一时间获得想要的信息。

以往的在线拍卖系统相关信息管理，都是工作人员手工统计。这种方式不但时效性低，而且需要查找和变更的时候很不方便。随着科学的进步，技术的成熟，计算机信息化也日新月异的发展，社会也已经深刻的认识，计算机功能非常的强大，计算机已经进入了人类社会发展的各个领域，并且发挥着十分重要的作用。

计算机技术在现代管理中的应用，使计算机成为用户应用现代技术的重要工具。能够有效的解决获取信息便捷化、全面化的问题，提高效率。
## 1.3 主要内容
在线拍卖系统从功能、数据流程、可行性、运行环境等方面进行需求分析。对在线拍卖系统的数据库、功能进行了详细设计。分析了主要界面设计和相关组件设计，对在线拍卖系统的具体实现进行了介绍，从而达到对在线拍卖系统的管理。

详细内容介绍，将在以下六章中详细阐述：

第一章、绪论，介绍了研究课题选择的背景及意义、研究现状，简要介绍了本文的章节内容。

第二章、引入技术知识，通过引入关键技术进行开发，向系统中涉及直观表达的技术知识。

第三章、重点分析了系统的分析，从系统强大的供需市场出发，对系统开发的可行性，系统流程以及系统性能和功能进行了探讨。

第四章、介绍了系统的详细设计方案，包括系统结构设计和数据库设计。

第五章、系统设计的实现，通过对系统功能设计的详细说明，论证了系统的结构。

第六章、系统的整体测试，评判系统是否可以上线运行。

采用Java语言，从数据库中获取数据、向数据库中写入数据，实现系统直接对数据库进行各种操作，在网页中加入动态内容，从而实现在线拍卖系统所需要的各种基本功能。


# 2 系统开发环境
## 2.1相关技术
在线拍卖系统是在Java + MySQL开发环境的基础上开发的。Java是一种服务器端脚本语言，易于学习，实用且面向用户。全球超过35％的Java驱动的互联网站点使用Java。MySQL是一个数据库管理系统，因为它的体积小但速度快，成本低，或者开源受到中小型网站的青睐。因此，Java + MySQL作为一个成熟的开发环境，可以满足在线拍卖系统设计和开发所需的稳定性，安全性和可扩展性要求。
## 2.2 JAVA技术
JAVA语言是目前软件市场上应用最广泛的语言开发程序。可以在多种平台上运用的，兼容性比较强，适应市面上大多数操作系统，不会出现乱码的现像，其扩展性和维护性都更好，具有分析问题和解决问题的能力，是面向过程的程序设计方便我们编写的代码更强壮。

JAVA相对其它语言来说，比较简单，编译起来更方便一些，安全可靠性高。不完全统计，现在全世界大约有2000多万人在使用它，JAVA既可以镶嵌使用又可以独力的使用。JAVA大致可以分成两个部分，一种部分是JAVA负责的编译，另一种是JAVA负责的运行。JAVA和C++语言很相像，但JAVA在编程时是一种以对象为导向的方式来进行编译的，使得编出来的软件可以单机使用，也可以在互联网上使用，检查出错更为方便。JAVA分布式、体系结构中立的特点也使得其存储更快，编议更简单。面向对象包括四个特点，一是封装，就是说在定义类的时候可以实现一定的功能和属性。二是抽象，属于类的一种，可以把一个具有共同属性的类封装在一个抽象里，便于简单编议。三是继承，顾名思义就是带有前者的特性。还有一个就是多态的特点，可以多种一起运用，表现了它可扩展性好。
## 2.3 MySQL数据库
数据库是系统开发过程中不可或缺的一部分。 在WEB应用方面，MySQL AB开发了一个具有很大优势的MySQL关系数据库管理系统。 MySQL可以将数据存储在不同的表中，这非常灵活，并且还可以提高系统在实际应用中的速度。 数据库访问最常用于标准SQL语言，MySQL用于SQL语言，因此它具有高度兼容性。数据库的操作是必不可少的，包括对数据库表的增加、删除、修改、查询等功能。现如今，数据库可以分为关系型数据库和非关系型数据库，Mysql属于关系性数据库，Mysql数据库是一款小型的关系型数据库，它以其自身特点：体积小、速度快、成本低等，Mysql数据库是目前最受欢迎的开源数据库。
## 在WEB应用技术中， Mysql数据库支持不同的操作系统平台，虽然在不同平台下的安装和配置都不相同，但是差别也不是很大，Mysql在Windows平台下两种安装方式，二进制版和免安装版。安装完Mysql数据库之后，需要启动服务进程，相应的用户就可以连接数据库，用户可通过命令行或者图形界面工具登录数据库。
## 2.4 Tomcat介绍
Tomcat 虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML页面的运行提供技术支持，Tomcat 的任务则是运行Servle和Java 页面。Tomca也具有一定的HTML页面处理功能。Tomcat属于一种轻型的服务器，所以说在中小企业中并不具有普适性。但是当程序员需要开发或调试Java 程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML 页面进行访问。Tomcat是非常受欢迎的服务器，因为它具有较好的扩展性，而且在运行的时候不需要太多的系统资源，拥有程序员所需要的收发邮件功能，还能够支持负载平衡，该程序能够不断的更新，程序员能够根据自己的需要增加新的功能。

## 2.5 SpringBoot框架
Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。
Spring Boot特点：
1、创建一个单独的Spring应用程序；
2、嵌入式Tomcat，无需部署WAR文件；
3、简化Maven配置；
4、自动配置Spring；
5、提供生产就绪功能，如指标，健康检查和外部配置；
6、绝对没有代码生成和XML的配置要求；
`  `安装步骤：
`   `最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。 为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。 可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。 更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。 可以从GVM命令行GVM install springboot安装Boot及其CLI。 在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brew tap pivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。



# 3 需求分析
## 3.1技术可行性：技术背景     
在线拍卖系统是在Windows操作系统中进行开发运用的，而且目前PC机的各项性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用Java开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得网站运行更具有稳定性和安全性，从而完成实现网站的开发。

（1）硬件可行性分析

系统管理及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开网站必须顺畅，不能停顿太长时间；性价比高；安全性高。

（2）软件可行性分析

开发整个系统使用的是云计算，流量的可扩展性和基于流量的智能调整云计算的优点就是流量的可扩展性和基于流量的智能调整，保障了数据信息能够得到及时的备份，整个系统可以安全有效的运行。 

因此，我们从两个方面进行了可行性研究，可以看出系统的开发没有问题。
## 3.2经济可行性
在在线拍卖系统开发之前所做的市场调研及与其相关的其他管理系统，都是没有任何费用的。所有的调查研究都是通过开发者自己的努力，所有的工作也都是自己亲力亲为的。在碰到自己比较难以解决的问题时，大多数是通过指导老师和同学的帮助进行相关问题的解决。所以对于在线拍卖系统的开发在经济上是完全可行的，没有任何费用支出的。 

使用比较成熟的技术，系统是基于Java的开发，采用Mysql数据库。所以系统在开发人力、财力方面的要求不高，具有经济可行性。

## 3.3操作可行性： 
可操作性主要是对在在线拍卖系统设计完成后，用户的使用体验度，以及管理员可以通过系统随时管理相关的数据信息，并且对于管理员、用户二个权限角色，都可以简单明了的进入到自己的系统界面，通过界面可以简单明了地操作功能模块，方便用户信息的操作需求和管理员管理数据信息。对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以在线拍卖系统的可操作性是完全可以的。本系统的操作使用的也是界面窗口进行登录，所以操作人员只要会简单的电脑操作就完全可以的。
## 3.4系统设计规则
本在线拍卖系统采用Java技术，Mysql数据库开发，充分保证了系统稳定性、完整性。 

在线拍卖系统的设计与实现的设计思想如下： 

1. 操作简单方便、系统界面安全良好：简单明了的页面布局，方便查询管理的相关信息。

2、即时可见：对在线拍卖系统信息的处理将立马在对应地点可以查询到，从而实现“即时发布、即时见效”的系统功能。 

3、功能的完善性：管理员；首页、个人中心、用户管理、商品类型管理、拍卖商品管理、历史竞拍管理、竞拍订单管理、留言板管理、系统管理，用户；首页、个人中心、历史竞拍管理、竞拍订单管理、留言板管理，前台首页；首页、拍卖商品、竞拍公告、留言反馈、个人中心、后台管理模块的修改和维护操作。

## 3.5系统流程和逻辑
系统业务流程图，如图所示：

![](/md/blog.001.png)

图3-1登录流程图

![](/md/blog.002.png) 

图3-2添加信息流程图

![](/md/blog.003.png) 

图3-3注册信息流程图


# 4系统概要设计
## 4.1 概述
在线拍卖系统基于Web服务模式，是一个适用于Internet环境下的模型结构。只要用户能连上Internet,便可以在不受时间、地点的限制来使用这个系统。在线拍卖系统工作原理图，如图4-1所示：

![](/md/blog.004.png)

图4-1  系统工作原理图
## 4.2 系统结构
本系统架构网站系统，本系统的具体功能如下：

在线拍卖系统登录界面

用户登录

密码正确

管理员界面

用户界面

![](/md/blog.005.png)

图4-2系统功能结构图

管理员功能结构图，如图4-3所示：

![](/md/blog.006.png)

图4-3 管理员功能结构图

前台首页功能结构图，如图4-4所示：

![](/md/blog.007.png)

图4-4 前台首页功能结构图

用户功能结构图，如图4-5所示：

![](/md/blog.008.png)

图4-5用户功能结构图

## 4.3. 数据库设计
### 4.3.1 数据库实体
管理员信息结构图，如图4-6所示：

![](/md/blog.009.png)

` `图4-6 管理员信息实体结构图

拍卖商品管理实体属性图，如图4-7所示：

![](/md/blog.010.png)

图4-7拍卖商品管理实体属性图

用户管理实体属性图如图4-8所示。

![](/md/blog.011.png)

图4-8用户管理实体属性图

历史竞拍管理实体属性图如图4-9所示。

![](/md/blog.012.png)

图4-9历史竞拍管理实体属性图

### 4.3.2 数据库设计表
## 4.4 数据表
将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表1：jingpaidingdan表

|列名|数据类型|长度|约束|
| - | - | - | - |
|id|bigint|19|NOT NULL|
|addtime|varchar|2000|`  `NULL DEFAULT |
|dingdanbianhao|tinyint|2|`  `NULL DEFAULT |
|shangpinmingcheng|decimal|2|NOT NULL|
|shangpinleixing|varchar|2|NOT NULL|
|chengjiaojiage|varchar|2|NOT NULL|
|faburiqi|varchar|2|NOT NULL|
|yonghuming|varchar|2|NOT NULL|
|xingming|varchar|2|NOT NULL|
|shouji|varchar|2|NOT NULL|
|youxiang|varchar|2|NOT NULL|
|dizhi|varchar|2|NOT NULL|

表2：lishijingpai表

|列名|数据类型|长度|约束|
| - | - | - | - |
|id|int|11|NOT NULL|
|addtime|varchar|255|NOT NULL|
|shangpinmingcheng|varchar|255|NOT NULL|
|shangpinleixing|varchar|2|NOT NULL|
|riqi|varchar|2|NOT NULL|
|jiage|varchar|2|NOT NULL|
|yonghuming|varchar|2|NOT NULL|
|xingming|varchar|2|NOT NULL|
|shouji|varchar|2|NOT NULL|
|dizhi|varchar|2|NOT NULL|
|sfsh|varchar|2|NOT NULL|
|shhf|varchar|2|NOT NULL|

表3：paimaishangpin表

|列名|数据类型|长度|约束|
| - | - | - | - |
|id|` `int|9|NOT NULL |
|addtime|char|5|NOT NULL|
|shangpinmingcheng|char|5|NOT NULL|
|shangpinleixing|char|5|NOT NULL|
|tupian|char|5|NOT NULL|
|jiage|char|5|NOT NULL|
|shangpinxiangqing|char|5|NOT NULL|
|huodongshijian|char|5|NOT NULL|
|huodongzhuangtai|char|5|NOT NULL|

表4：yonghu表

|列名|数据类型|长度|约束|
| - | - | - | - |
|id|` `int|9|NOT NULL |
|addtime|char|5|NOT NULL|
|yonghuming|char|5|NOT NULL|
|mima|char|5|NOT NULL|
|xingming|char|5|NOT NULL|
|xingbie|char|5|NOT NULL|
|touxiang|char|5|NOT NULL|
|shenfenzheng|char|5|NOT NULL|
|shouji|char|5|NOT NULL|
|youxiang|char|5|NOT NULL|
|dizhi|char|5|NOT NULL|



# 第5章 系统详细设计
## 5.1管理员功能模块
管理员登录，管理员通过输入用户名、密码、角色等信息进行系统登录，如图5-1所示。

![](/md/blog.013.png)

图5-1管理员登录界面图

管理员登录进入在线拍卖系统可以查看首页、个人中心、用户管理、商品类型管理、拍卖商品管理、历史竞拍管理、竞拍订单管理、留言板管理、系统管理等内容，如图5-2所示。

![](/md/blog.014.png)

图5-2管理员功能界面图

修改密码，在修改密码页面可以填写原密码、新密码、确认密码等内容，并可根据需要对修改密码进行详情，修改或删除等操作，如图5-3所示。

![](/md/blog.015.png)

图5-3修改密码界面图

用户管理，在用户管理页面可以填写用户名、密码、姓名、性别、头像、身份证、手机、邮箱、地址等内容，并可根据需要对用户管理进行，修改或删除等操作，如图5-4所示。

![](/md/blog.016.png)

图5-4用户管理界面图



商品类型管理，在商品类型管理页面可以填写商品类型等进行修改，删除或查看详细内容等操作，如图5-5所示。

![](/md/blog.017.png)

图5-5商品类型管理界面图

拍卖商品管理，在拍卖商品管理页面可以查看商品名称；商品类型、图片、价格、活动时间、活动状态等内容，并可根据需要对拍卖商品管理进行详情，修改，删除或详细内容等操作，如图5-6所示。 ![](/md/blog.018.png)

图5-6拍卖商品管理界面图

竞拍公告 ，在竞拍公告页面可以查看标题、简介、图片等内容，并可根据需要对竞拍公告进行详情，修改，删除或详细内容等操作，如图5-7所示。

![](/md/blog.019.png)

图5-7竞拍公告界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图5-8所示。

![](/md/blog.020.png)

图5-8轮播图管理界面图

历史竞拍管理，在历史竞拍管理页面可以查看商品名称；商品类型、日期、价格、用户名、姓名、手机、地址、审核回复、审核状态、审核等内容，并可根据需要对历史竞拍管理进行详情，修改，删除或详细内容等操作，如图5-9所示。

![](/md/blog.021.png)

图5-9历史竞拍管理界面图

竞拍订单管理，在竞拍订单管理页面可以查看订单编号、商品名称；商品类型、成交价格、发布日期、用户名、姓名、手机、邮箱、地址、是否支付等内容，并可根据需要对竞拍订单管理进行详情，修改，删除或详细内容等操作，如图5-10所示。

![](/md/blog.022.png)

图5-10竞拍订单管理界面图


留言板管理，在留言板管理页面可以查看用户名、留言内容、回复内容等内容，并可根据需要对留言板管理进行详情，修改，删除或详细内容等操作，如图5-11所示。

![](/md/blog.023.png)

图5-11留言板管理界面图



## 5.2用户功能模块
用户登录进入在线拍卖系统可以查看首页、个人中心、历史竞拍管理、竞拍订单管理、留言板管理等内容，如图5-12所示。

![](/md/blog.024.png)图5-12用户功能界面图

历史竞拍管理，在历史竞拍管理页面可以查看商品名称；商品类型、日期、价格、用户名、姓名、手机、地址、审核回复、审核状态、审核等内容，并可根据需要对历史竞拍管理进行详情，修改，删除或详细内容等操作，如图5-13所示。

![](/md/blog.025.png)

图5-13历史竞拍管理界面图


留言板管理，在留言板管理页面可以查看用户名、留言内容、回复内容等内容，并可根据需要对留言板管理进行详情，修改，删除或详细内容等操作，如图5-14所示。

![](/md/blog.026.png)

图5-14留言板管理界面图

竞拍订单管理，在竞拍订单管理页面可以查看订单编号、商品名称；商品类型、成交价格、发布日期、用户名、姓名、手机、邮箱、地址、是否支付等内容，并可根据需要对竞拍订单管理进行详情，修改，删除或详细内容等操作，如图5-15所示。

![](/md/blog.027.png)

图5-15竞拍订单管理界面图







## 5.3前台首页功能模块
用户登录进入在线拍卖系统可以首页、拍卖商品、竞拍公告、留言反馈、个人中心、后台管理等内容，如图5-16所示。

![](/md/blog.028.png)图5-16前台首页功能界面图

登录、用户注册，在用户注册页面通过填写用户名、密码、姓名、身份证、手机、邮箱、地址等信息进行注册、登录，如图5-17所示。

![](/md/blog.029.png)


![](/md/blog.030.png)

图5-17用户注册、登录界面图

拍卖商品，在拍卖商品页面可以填写商品名称；商品类型、图片、价格、活动时间、活动状态等内容，进行竞拍，如图5-18所示。

![](/md/blog.031.png)

图5-18拍卖商品界面图

留言反馈，在留言反馈页面可以填写留言内容等内容，并可根据需要对留言反馈进行立即提交操作，如图5-19所示。

![](/md/blog.032.png)

图5-19留言反馈界面图

竞拍公告，在竞拍公告页面可以填写公告信息等内容，并可根据需要对竞拍公告进行提交操作，如图5-20所示。

![](/md/blog.033.png)

图5-20竞拍公告界面图













# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm658基于ssm框架的少儿编程在线培训系统+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Tm8QeZE4a?p=57)


# 课题背景及研究内容
# 课题背景
随着科技的发展，计算机的应用，人们的生活方方面面都和互联网密不可分。计算机的普及使得人们的生活更加方便快捷，网络也遍及到我们生活的每个角落，为我们的学习、生活和工作带来了极大的方便。随着计算机技术的发展以及计算机网络的逐渐普及，互联网成为人们查找信息的重要场所，二十一世纪是信息的时代，信息的交换和信息流通显得特别重要。
## 1.2 开发目的和意义
软件的开发总是顺应了时代的发展要求，软件的到来让我们的日常办公变得越加容易，每天处理的信息内容超过手工办公好几倍，利用软件办公更加能够确保输入信息的正确性。本次开发的少儿编程在线培训系统针对的领域就是物业管理领域，这款软件可以帮助物业管理管理人员进行新闻公告的管理，能够管理房产，业主等信息。少儿编程在线培训系统的出现就让物业管理信息管理开始进入新的信息管理的模式，所有信息的增删改查都基于电脑操作，系统访问无时间地点限制，数据信息保存时间长，安全性高。软件投入物业管理领域进行运行，完全替代了物业管理工作人员手记脑记的办公方式。
# 2 相关技术和应用
## 2.1 VUE技术
VUE它是由HTML代码，配上嵌入在HTML代码里面的Java代码组成的应用于服务器端的语言，使用VUE进行开发能够更加容易区分网页逻辑以及网页设计内容，让程序员开发思路更加清晰化，VUE在设计组件时，它是可以重用的，这样一来，我们在开发Web程序的时候，速度也会提高很多，开发过程也简单多了。VUE通常在服务器端执行任务，这方面跟Java Servlet相同，执行完之后把HTML文件返回到客户端，所以我们的用户在客户端通过浏览器就可以查看浏览程序。VUE的基础技术就是Java Servlet，我们生活中经常看见的比较大型的Web程序是VUE技术搭配Java Servlet才能够成功开发出来，可以说VUE技术很简单易学，它跟平台并不存在多大关系，并且它还很可靠。VUE的运行原理图如下图：

![22f9](/md/blog.006.jpeg "22f9")

图2-1 VUE的运行原理图
## 2.2 Mysql数据库简介
数据库就是用来存放数据的，要是以存储方式划分数据库的话，我们就会发现数本次开发系统用MySQL数据库来保存数据信息，MySQL实质是RDBMS，他的源代码开放高，在网上随便都能搜到，数据库管理的语言采用SQL（结构化查询语言）进行数据管理，下面我们就简单介绍SQL语句的一些常用用法。通常我们要创建一个数据库时就会使用“CREATE DATABASE ”命令开头，使用某个数据库时就会以“use+数据库名称”命令，如果想要查看数据库里面数据表就会使用到“SHOW TABLES”命令，当然我们在操作数据表内容时也会使用到某些命令，比如删除就用“drop”，清空就用“delete from”，更新数据就用“update”，需要加入数据的话可以用“insert into ”等命令，这些就是SQL查询语句的惯用语法。这次采用mysql数据库还是源于它备受关注的实用性和可靠性，它里面的大部分功能一般的系统都还用不完，况且mysql小巧但它功能比较齐全，是一般系统软件的开发首选。MySQL开放的源代码通过360安全浏览器可以快速下载下来，程序员可以对这些免费的代码根据自身需求进行个性化定制操作。为了我们能够更好地使用MySQL，平时我们需要多加维护，有空的时候还是多多查看一些二进制日志、错误日志、常规查询日志等日志，它们能够帮助我们进行性能分析以及DBA检查，除了这个还需要注意每间隔一定时间就要更新缓冲区和缓存，这样能够降低碎片，利用OPTIMIZETABLE命令让数据表进行重新组织，还能节省许多空间避免空间浪费。
## 2.3 SSM框架简介
本次系统开发在系统框架设计上面采用了目前主流的企业级的SSM框架，相比SSH框架来说，SSM框架在现实应用中也运用得很广泛，SSM框架其实是Spring和Spring MVC以及MyBatis这三个部分首字母的缩写，SSM框架在搭建许多比较大型的企业级别的系统时基本能够胜任。Spring在2003年的时候比较流行，他是一个基于Java开发的轻量级别的开源框架，它主要能够简化企业在进行应用程序开发上面的复杂步骤，通常Spring在进行Java应用开发过程中大多数都是基于服务器端进行开发操作。Spring MVC能够支持Spring的特性，让开发变得更加简单规范。 Spring MVC通过简单分离控制器，分派器，模型对象还有进行程序处理对象的角色这四部分内容，使得它们变得更加容易进行定制处理。MyBatis其实是Java开发上面的持久层框架，这个框架它能够帮助开发者进行数据信息的增加，删除，修改，查询的管理操作。下面将展示SSM与三层架构的关系图。

![](/md/blog.007.png)

图2-2 SSM与三层架构的关系图
## 2.4 Eclipse简介
系统开发平台就是在Eclipse开发平台上面进行的，Eclipse的源代码在网上都能随便找到，Eclipse本身其实是框架和服务的组合体，Eclipse构建的开发环境是通过插件组件进行构建的，不过Eclipse它还包括了一个比较标准的插件集合，这里面也包含了关于Java的开发工具。在Eclipse里面，可以说几乎每种东西都属于插件。Eclipse是运用Java语言进行系统开发的，但是它也对PHP语言，Android编程语言等许多编程语言提供插件支持，使用Eclipse框架还可以作为其他应用程序的基础，这些程序是跟软件开发并无任何联系的应用程序，像内容管理系统就是一个例子。
## 2.5 B/S系统架构
B/S（浏览器/服务器）结构是目前主流的网络化的结构模式，它能够把系统核心功能集中在服务器上面，可以帮助系统开发人员简化操作，便于维护和使用。只需要用户在客户端安装360浏览器、谷歌浏览器、QQ浏览器等当前大众浏览器，在电脑里面安装sqlserver、mysql数据库等数据库。安装好的浏览器与服务器端的数据库进行信息数据的交互。很多专门软件能够做到的事情，采用B/S结构模式也能实现，它能够结合Web浏览器技术，ActiveX技术以及多种脚本语言等技术。帮助程序开发者节约了不少开发成本。目前B/S结构成为程序开发主流结构，它最好的地方就是没有地点限制还不用专门安装软件，笔记本或者电脑能够上网就能访问系统。系统使用B/S进行开发在后期系统维护上面就会很省事，不用什么问题都在服务器上面操作，简单的客户端处理就解决部分问题，开发出来的程序跟用户交互性上面也会增强，还可以实时刷新浏览器进行程序局部的数据信息更新。B/S模式它是属于三层架构的模式，B/S模式三层结构图如图2-3所示。

![](/md/blog.008.png)

图2-3 B/S模式三层结构图


##
# 3 系统分析
## 3.1可行性分析
系统进行开发，不能省去了系统的可行性分析，可行性分析主要就是分析系统开发的必要性，从技术，经济，时间等方面来进行分析论证。
### 3.1.1技术可行性
系统开发使用到的技术包含了VUE技术，Mysql数据库技术等内容，由于自己是计算机专业的学生，大学几年下来，我对编程技术知识也有一定的存储量，在开发程序的时候还是能够派上用场，就算出现比较具有深度的技术问题，我可以通过计算机网络平台进行知识查找，或者是在学校图书馆查看资料，也可以向周边的老师或者是同学求助，所以技术上面我还是比较有把握能够完成系统开发任务。
### 3.1.2经济可行性
系统开发使用的软件我都是在官方软件平台上面进行下载下来的，下载下来之后根据安装视频进行一步步操作安装，全程都是自己单独完成，利用自己的笔记本连上宿舍WIFI就可以完成软件下载安装操作了，由于自己经常使用谷歌浏览器，所以我的电脑上一直都有浏览器，关于系统开发的硬件配置，我的笔记本都能满足要求，所以程序开发在经济上几乎没有任何支出。
### 3.1.3操作可行性
平时我们在学校学习知识，完成老师布置的各种作业，以及操作各种软件，我们会发现软件的操作逻辑以及使用习惯都来源于用户，所以软件开发最重要的一点就是站在用户立场思考问题，因此本系统开发我会参考许多成品网站，分析总结他们的操作的逻辑以及功能设置，然后把他们优秀的地方运用到自己的网站系统上面来，让使用者在运行操作我开发出来的系统时，会感觉到系统操作流畅，界面清晰，操作逻辑严密，运行使用基本无大碍。就算使用者第一次访问系统，也不会觉得这是个高难度的程序。他们简单看看或者是经人指点也就会操作了。
### 3.1.4 时间可行性
作为学生，最多的就是时间，虽然临近毕业，但是学校预留的毕业论文撰写的时间还是很充足的，半年时间用来完成毕业程序及对应论文的工作，时间上都会产生剩余，所以系统开发时间安排上不用担心。

经过上面的简单分析，我们发现系统开发操作上不用担心，经济上面无需支出，技术上面有保障，时间还有多余，因此少儿编程在线培训系统的开发可以进行。
## 3.2 系统性能分析
本次开发的系统要求系统数据内容信息能有相应的安全机制，不能让非系统用户轻松进入系统，对于数据信息的增改查删操作也要进行严格控制以及管理，用户使用系统进行数据信息的查找操作时间上面也不能过长，最好是一秒钟之内，任何系统从开发出来到淘汰系统这段时间我们称为寿命，系统稳定正常使用时间要超出五年时间，还有一点就是系统要能体现出经济实惠的价值出来，使用者进行使用，能产生依赖性就最好了，系统一旦投入运行之后，初次访问者能够在短时间内学会操作，能够快速理解程序内容，我们的程序就算过关了，还有需要注意的就是任何系统在安全性上面不能掉以轻心，系统能保证数据安全才是好的程序。
## 3.3系统运行环境
系统开发选择win7操作系统，开发平台选择eclipse搭配Mysql数据库的形式进行开发，系统选择比C/S模式更加简洁的B/S模式进行编写。编码语言采用Java完成系统功能的编写。系统架构使用的是SSM架构进行系统的开发操作。系统界面设计符合大众需求，稳定性还有数据内容安全性等系统问题，我们在开发期间会有相应的技术手段来保证。
## 3.4 系统流程分析
系统流程分析就是把系统在操作运行过程中的各个环节的业务流程进行分析，下面将从用户登录以及数据查询等功能进行数据流程分析，最后以流程图形式进行展示。
### 3.4.1用户登录流程
系统投入使用，各个功能都有流程操作，比如在登陆时用户名密码填写正确是怎样的反馈，填写错误又是什么样的反馈，后台执行都有对应的操作流程。本次开发的系统的登录流程参照下面的图执行。用户登录流程如下：

![](/md/blog.009.png)

图3-1 用户登录流程图
### 3.4.2信息修改流程
信息修改流程就是用户对数据信息进行简单的修改操作时需要遵循的流程。具体流程图如下：

![](/md/blog.010.png)

图3-2 信息修改流程图
### 3.4.3信息添加流程
信息录入也是有一定的流程，从开始录入到信息成功添加的过程如下：

![](/md/blog.011.png)

图3-3 信息添加流程图
### 3.4.4信息查询流程
信息查询需要关键字的输入，然后回车进行检索找到用户需要的信息展示出来。具体执行过程如下

![](/md/blog.012.png)

图3-4 信息查询流程图

这次打算开发的少儿编程在线培训系统操作流程不是很难，用户稍微指点就可以上手，这个系统可以管理新闻公告信息以及业主和业主房产信息等内容。工作模式计算机信息化。下面简单说说该少儿编程在线培训系统开发需要遵循的开发目标：

（1）首先该系统界面设计要美观，操作要求简单化，设计过程采用控件式布局，操作员在使用系统过程中录入信息简单化。用户每次操作内容时系统就会有相应的提示信息，帮助用户随时清楚自己在干啥。

（2）即时可见：用户在进行修改操作，或者删除操作，拟或是信息简单添加操作等，每次操作完之后在系统对应主页面要显示出来操作后的效果，比如删除某条信息，那么删除后的信息在页面内就不能再次出现了，添加某条信息时，主页面就会同步显示刚添加的内容。

（3）功能完善：系统开发就是为了让用户用得舒适，功能上面要完全符合用户功能需求，操作流程和功能匹配既要完善也要合理。

（4）方便移植：一个系统开发出来并不是一成不变的，后期随着物业规模扩大，相应的改变就是系统内容也会根据物业需求进行完善或者扩充，仅仅需要简单地修改程序内容就能进行具有特色的软件系统的开发，系统更新还有维护简单化。

（5）动态管理：系统数据每天操作都会出现数据信息的动态变化，这些动态变化的信息在系统里面要能够实时更新，比如查询业主和业主房产信息，那么这个业主和业主房产信息要是最新的信息。查询修改删除操作要求的数据内容一直保持最新状态。
## 3.5 功能需求
UML它也被叫做统一建模语言，这种语言功能相当地强大，并且表达出来也不难，使用它进行系统分析不具有局限性，更重要的就是UML把软件领域的许多思想还有技术等内容也包含进去了，通常情况下我们在进行系统开发之前的分析阶段，会用到它来画图，使用它能够更加简单明了的描述我们即将开发的系统所具备的功能。

在本次开发出来的少儿编程在线培训系统中，我们主要分成了信息管理版块，基础信息版块，业主信息管理版块以及登录版块这几个部分的内容，下面将分别进行阐述。

# 4  系统设计
## 4.1系统结构设计
少儿编程在线培训系统使用的是在Web应用程序里面最受欢迎的B/S结构，这种结构唯一要求就是用户不管在任何的场合，选择一天当中的任何时间段进行系统访问，都需要用户电脑可以连上网络，只要有网络，用户就可以很随意地访问程序还有服务器。系统的结构图4-1所示：

![](/md/blog.013.png)

图4.1 系统结构图
## 4.2 系统功能模块设计
在系统设计阶段，我们会进行系统架构的设计，这个部分主要就是把系统功能进行细分，最后把所有小功能组合在一起的过程。系统架构步骤如下：

1、要把需要开发的系统分成很多个小模块

2、对第一步操作分成的小模块进行预先设计

3、设计小模块之间的逻辑关系

4、设计小模块的界面还有存在于模块间的信息传输

在进行设计期间，我们先要知道系统的需求，然后在需求报告的基础上进行初次设计，接着进行后期优化，到最后出具一个可以实现的系统框架图

少儿编程在线培训系统


用户信息管理

公告信息管理

课程信息管理

课程类型管理

商教师信息管理

用用户信息修改

用用户信息新增

商教师信息添加 

商教师信息删除

商教师信息修改

商课程类型添加

商课程类型修改

商课程类型删除

商公告信息添加

商公告信息删改

商公告信息删除

商课程信息添加 

商课程信息修改 

商课程信息删除 

新

公告类型管理

新公告类型修改

新公告类型删除

新公告类型添加

![](/md/blog.014.png)

图4-2 管理员功能结构图
### 4.3  数据库设计

表4.1字典表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.2论坛表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|forum\_name|String|帖子标题|是|
|3|yonghu\_id|Integer|用户|是|
|4|jiaoshi\_id|Integer|教师|是|
|5|users\_id|Integer|管理员|是|
|6|forum\_content|String|发布内容|是|
|7|super\_ids|Integer|父id|是|
|8|forum\_state\_types|Integer|帖子状态|是|
|9|insert\_time|Date|发帖时间|是|
|10|update\_time|Date|修改时间|是|
|11|create\_time|Date|创建时间|是|
表4.3教师表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|账户|是|
|3|password|String|密码|是|
|4|jiaoshi\_name|String|教师姓名|是|
|5|jiaoshi\_photo|String|头像|是|
|6|sex\_types|Integer|性别|是|
|7|jiaoshi\_phone|String|联系方式|是|
|8|jiaoshi\_email|String|邮箱|是|
|9|jiaoshi\_delete|Integer|假删|是|
|10|create\_time|Date|创建时间|是|
表4.4课程信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|kecheng\_uuid\_number|String|课程编号|是|
|3|kecheng\_name|String|课程名称|是|
|4|kecheng\_types|Integer|课程类型|是|
|5|kecheng\_photo|String|课程图片|是|
|6|nianlingduan\_types|Integer|年龄段|是|
|7|jiaoshi\_id|Integer|教师|是|
|8|kecheng\_number|BigDecimal|报名费用|是|
|9|kecheng\_content|String|课程简介|是|
|10|create\_time|Date|创建时间|是|
表4.5报名记录表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|kecheng\_id|Integer|课程|是|
|3|yonghu\_id|Integer|用户|是|
|4|create\_time|Date|创建时间|是|
表4.6公告信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|news\_name|String|公告标题|是|
|3|news\_types|Integer|公告类型|是|
|4|news\_photo|String|公告图片|是|
|5|insert\_time|Date|公告时间|是|
|6|news\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.7用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_photo|String|头像|是|
|4|yonghu\_phone|String|联系方式|是|
|5|yonghu\_email|String|邮箱|是|
|6|new\_money|BigDecimal|余额|是|
|7|yonghu\_delete|Integer|假删|是|
|8|create\_time|Date|创建时间|是|
表4.8用户表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|


# 5 系统实现
如图5.2显示的就是教师信息管理页面，此页面提供给管理员的功能有：查看已发布的教师信息数据，修改教师信息，教师信息作废，即可删除。


![](/md/blog.015.png)


图5.2 教师信息管理页面
### 5.3课程信息管理
如图5.3显示的就是课程信息管理页面，此页面提供给管理员的功能有：根据课程信息进行条件查询，还可以对课程信息进行新增、修改、查询操作等等。

![](/md/blog.016.png)



图5.3 课程信息管理页面
### 5.1公告信息管理
如图5.4显示的就是公告信息管理页面，此页面提供给管理员的功能有：根据公告信息进行新增、修改、查询操作等等。

![](/md/blog.017.png)


图5.4 公告信息管理页面
#
# 结  论
平时自己在学校学习各种各样的知识，按时完成老师布置的作业，虽然从形式上感觉自己的能力增加了不少，自己学会的东西都开始堆积起来了，但是面对毕业设计，想想自己单独完成程序开发，所有的问题就来了，感觉自己一个人完成程序开发肯定相当难。当我在导师帮助下确定了自己的选题之后，我开始跟大家一样进行选题资料收集的工作，我在图书馆看了很多的书籍，有eclipse开发平台的详细操作的书，有Mysql数据库环境搭建以及具体数据库创建和参数设置方面的书籍，还有程序开发具体流程以及功能设置等内容都有相应的书籍给了我答案，于是我开始撰写开题，开始搭建论文大纲的内容结构。慢慢的我开始对毕设没有了顾虑。

最为艰难的时刻就是程序编码那段时间，虽然我根据自己的需求报告撰写系统功能，但是每次编码完一个小功能，在运行的时候都会报错，无数次的尝试和运行，最后还是同学帮我检查出了问题，很多时候也会出现程序代码乱码的问题，不过后来我通过万能的百度解决了。

在独立完成程序开发期间，我发现了很多有关程序开发的论坛，结识了很多资深程序员，我也在网站上面通过别人撰写的博客信息来学习开发相关知识，可以说当我完成程序之后，我相比之前能力有了很大的提高，所以说毕业设计的完成应该是我最为难忘的时候。

19
![](/md/blog.018.png)













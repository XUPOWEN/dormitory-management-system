1系统需求分析
所谓"需求分析"，是指对要解决的问题进行详细的分析，弄清楚问题的要求，包括需要输入什么数
据，要得到什么结果，最后应输出什么。可以说，“需求分析”就是确定要计算机“做什么”。
1.获取需求，识别问题
开发人员从功能、性能、界面和运行环境等多个方面识别目标系统要解决哪些问题，要满足哪些限
制条件，这个过程就是对需求的获取。开发人员通过调查研究，要理解当前系统的工作模型和用户
对新系统的设想与要求。
2.分析需求，建立目标系统的逻辑模型
在获得需求后，开发人员应该对问题进行分析抽象，并在此基础上从高层建立目标系统的逻辑模
型。模型是对事物高层次的抽象，通常由一组符号和组织这些符号的规则组成。常用的模型图有数
据流图、E-R图、用例图和状态转换图等，不同的模型从不同的角度或不同的侧重点描述目标系统。
绘制模型图的过程，既是开发人员进行逻辑思考的过程，也是开发人员更进一步认识目标系统的过
程。
3.将需求文档化
获得需求后要将其描述出来，即将需求文档化。对于大型的软件系统，需求阶段一般会输出三个文
档：
系统定义文档（用户需求报告）；
系统需求文档（系统需求规格说明书）；
软件需求文档（软件需求规格说明书）。
4.需求验证
需求验证是对需求分析的成果进行评估和验证的过程。为了确保需求分析的正确性、一致性、完整
性和有效性，提高软件开发的效率，为后续的软件开发做好准备，需求验证的工作非常必要。
在需求验证的过程中，可以对需求阶段的输出文档进行多种检查，比如，一致性检查、完整性检查
和有效性检查等。同时，需求评审也是在这个阶段进行的。
角色分析
经过实地调查和访谈，我们可以发现宿舍管理信息系统的用户主要包括宿舍管理中心管理员（简称
中心管理员）、宿舍管理员（简称宿管员）、学生和教师四
类，他们在工作和生活中使用系统的情况如下：
1、宿管中心管理员：宿管中心管理员能够使用本系统登记系别、专业、班
级、宿舍等基础数据；能方便地为大一新生分配宿舍、通过多种方式查询学生以
及宿舍住宿信息；中心管理员还管理整个系统所有用户信息以及权限的分配。
2、宿管员：宿管员能够通过本系统登记学生入住、出住宿舍情况，登记来
访者来访，查看学生及宿舍实际住宿安排情况。
3、学生：广大学生能够通过登录本系统查看、修改个人信息，通过多种方
式查询所关注的学生的宿舍号、宿舍电话等信息。
4、教师：教师包括领导、辅导员和任课教师，通过本系统能够多种方式地
查询了解学生及宿舍实际住宿情况，了解学生的个人信息。
1.1问题描述
本小组选题为“学生公寓管理系统”
学生公寓管理系统是院校的学生宿舍进行统一管理。功能需求可大致分为以下模块：
①公寓及财产信息管理
公寓信息管理包含：
出入管理，用户管理，保修管理，用电管理，用水管理，寝室卫生管理订水管理，签到管理。
②公寓管理员信息管理
管理员信息管理包括管理查询，管理员信息修改，管理员信息添加，管理员删除管理，管理员权限
管理，管理员签到管理。
③学生入住公寓管理
学生入住公寓管理，包括登记管理，寝室分配管理，费用管理。
④外来人员及物品出入登记管理
外来人员及物品登记管理包括：外来人员信息录入，外来人员进入登记，外来人员离开登记，外来
人员物品存取管理，外来人员进入时间管理
功能需求
在实施本项目之前，项目组对系统需求做了充分地调查研究与分析。宿舍管理信息系统是一个面向
全院师生使用的系统。在实施本系统后，学校能有效分配
和管理学生宿舍资源，师生能方便查询学生住宿信息，宿管部门能提高对学生住
宿的管理和服务。该系统的用户主要有宿管中心管理员、宿管员、学生和教师。经分析，他们对系
统的功能需求如下：
1、宿舍管理信息系统能够为全校师生服务。系统能够记录学校的每一间学
生宿舍的编号、楼层、可住人数、室内面积、家具配备情况等基本信息，并给其一个惟一标识的编
号。宿管中心负责全院学生宿舍信息维护工作，包括增加、删除和修改。
2、每个学生能够拥有惟一标识其存在的编号（采用其学号）。系统记录下学生个人基本资料，为后
期管理提供信息服务。大一新生入校时，中心管理员根据院系、性别、专业、班级等限制条件从现
有可用宿舍空位中合理分配到具体某一间宿舍的某个床位。学生开始入住和毕业出住宿舍都有详细
的电子手续记录。
3、学生在校期间，宿管员登记其所在宿舍的文明、卫生、纪律情况，为学生管理工作提供数据支
持。
4、基于校园安全管理需要，校外人员、非本栋宿舍住宿者来访本栋住宿的学生时，持身份证件在宿
管员处办理电子登记手续，方可入内探访。
5、可以通过学号、姓名等方式查询某学生所住宿舍及宿舍电话号码，以便学生学习、生活交流，方
便辅导员、教师、管理人员查找、联系学生。
6、学生办理入住手续后，可以凭学号登录系统查看个人学号、姓名、院系、专业、班级等基本资
料，并补充或更改个人民族、籍贯、政治面貌、家庭住址、联系电话、电子邮箱等信息，但学号、
姓名、系别、专业、班级等信息拒绝学生
1.2用况模型分析（使用PowerDesigner进行UML设计）
用例图的主要作用：
1、用来描述待开发系统的功能需求和系统使用场景
2、作为开发过程的基础，驱动各阶段的开发工作
3、用于验证与确认系统需求
1.2.1学生管理
在本系统中，以上用例图的作用是，建立Student角色和系统中各个用例之间的关系，即角色
Student所需要进行的操作。总结如下
1、维护个人信息：学生登录系统后，可以查看个人所有信息，并能对个人的联系电话、电子邮箱、
政治面貌、家庭住址等信息进行更新，但学号、姓名、院系、班级等信息不可更新。
2、查询学生住宿：学生可以通过学号、姓名、班级等字段查询其他学生的住宿信息，获得被查询对
象的所住宿舍、宿舍电话，但被查询对象的其他私人信息不可见。

![image](https://github.com/XUPOWEN/dormitory-management-system/blob/main/1.2.1.drawio.png)
图1.2.1学生用例图
1.2.2宿管员管理
在本系统中，管理员具有多种功能，拥有各种权限，主要包含管理员上班签到，管理员下班签离，
管理员查询学生在寝室的状况，寝室卫生状况的查询，用电管理，用电管理又包含用电查询，电费
充值等用例。
宿管中心是全院学生宿舍管理服务机构，负责全院学生宿舍分配和管理，因此，宿管中心的管理员
主要进行如下活动：
1、安排新生宿舍：宿管中心验证学生缴费凭证后，根据其院系、性别、专
业、班级等约束条件，从现有的宿舍空床位中选择合适的床位给该学生。
2、维护宿舍信息：宿管中心管理员登录系统后，增加、删除、修改学生宿舍信息。
3、维护学生信息：维护院系、专业、班级及学生个人信息，包括增加、删除和修改系别、专业、班
级及学生信息。通过上述活动，获得的中心管理员用例图如图3-2所示
![image]()
图1.2.2宿管员管理用例图
1.3静态模型分析
建立系统静态模型，即建立该系统的对象模型。根据需求分析阶段得到的系统用例图，进一步归纳
汇总从中可以找出系统中存在的类。一边发现系统的类，一边确定这些类的属性和操作，并确定类
与类之间存在的联系，最终给出整个系统的类图。
对象图表示一组对象及它们之间的联系.对象图是系统的详细状态在某一时刻的快照,常用于表示复杂
的类图的一个实例.
对象图中的建模元素有对象和链.对象是类的实例,对象之间的链是类之间的关联的实例,对象图实质
上是类图的实例.
根据上面的用例图的分析得出以下实体类
1、学生类
在学生宿舍管理信息系统中，学生既是系统要管理的数据对象，同时又是系统的一个使用角色，其
相关数据必须存储在数据库中。学生具有学号、姓名、性别、出生日期、系别、专业、班级等属性
特征，以学号作为每一个学生身份标识。在系统中，学生具有增加、删除、修改及查询等行为，所
以在系统中应该有一个学生实体类。
![image]()
1.3.1学生类图
2、宿舍类
宿舍是系统要管理和分配的重要资源，具有宿舍号、楼栋号、床位数等属性特征，同时，宿舍可以
被增加、删除、修改和查询，因此应该在类图中有一个宿舍实体类。
![image]()
1.3.2宿舍类图
3、非学生用户类
系统用户除了学生，还有宿管中心管理员、宿管员、教师，四种使用角色。他们共有的属性特征有
用户名、密码、权限，共有的行为有登录系统、修改密码、查询学生、查询宿舍等行为，因此类图
中要有一个非学生用户类。教师、宿管员和宿管中心管理员是它的子类，除了继承其父类的所有属
性和行为外，继续扩充一些属性和行为，完成自己的职责。
![image]()
1.3.3非学生用户类图
4、来访类
宿舍日常管理中，来访登记是一项常规工作。外人来访活动的属性特点有来访者姓名、单位、证
件、来访时间、来访事由、被访姓名、被访宿舍、双方关系、离访时间。来访者可以多次来访多
人，同一宿舍、同一学生也可以接待多人来访，因此来访记录具有不断增加、查询等行为。
![image]()
1.3.4来访类图
5、系别类、专业类、班级类
大学生在校期间，都在某个系某个专业的某个班级里参加学习和活动。一般地，高等院校有多个
系，每个系有1个到多个专业，每个专业有1个到多个班级。系别有系别代码、系别名称、系主任、
系办公室等属性特征，专业有专业代码、专业名称、所属系别、学制年限等属性特征，班级有班级
代码、所属专业、班主任等属性特征。同时，系别、专业、班级均有可能增减，因此具有添加、删
除、修改以及查询等行为。在类图中，要有这三个类。
![image]()
1.3.4系统总类图
1.4动态模型分析
动态模型主要用来模拟和表达系统的动态行为和特征。动态模型由一组定义了行为的类组成。UML
的动态模型主要包括状态图、顺序图、协作图和活动图。只要能表达出系统的动态行为特点，并不
是必需同时画出。
1.4．1状态图
状态图（Statechart Diagram）主要用于描述一个对象在其生存期间的动态行为，表现为一个对象所
经历的状态序列，引起状态转移的事件（Event），以及因状态转移而伴随的动作（Action）。一般
可以用状态机对一个对象的生命周期建模，状态图用于显示状态机（State Machine Diagram），重
点在与描述状态图的控制流。
如下图例子，状态机描述了门对象的生存期间的状态序列，引起转移的事件，以及因状态转移而伴
随的动作（Action）.
在学生宿舍管理系统中可以不使用状态图和协作图，由于所有的类的状态并不是很复杂，故而大都
以活动图和时序图在动态建模中为主。
活动图是UML用于对系统的动态行为建模的另一种常用工具，它描述活动的顺序，展现从一个活动
到另一个活动的控制流。活动图在本质上是一种流程图。
已缴费学生凭财务收费单到宿管中心，申请安排宿舍。宿管中心管理员查验缴费凭证后，在系统中
录入学生学号、姓名、性别、系别、班级等基本资料后，系统自动查找并显示合适的宿舍床位。宿
管中心管理员打印或填写派房单给学生。学生凭派房单到相应宿舍楼宿管员处，登记入住手续。根
据相关工作流程，画出其活动图如图所示
![image]()
1.4.1学生登记活动图
顺序图也叫时序图，用来描述系统中多个对象之间的动态协作，重点是
显示对象之间发送消息的时间顺序。时序图的一个用途是用来显示用例中的
行为顺序，当执行一个用例行为时，时序图中的每条消息对应了一个类操作
或状态机中引起转换的触发事件。
添加学生宿舍数据的主要参与者是宿管中心管理员，涉及到的类主要有维护宿舍信息界面、宿舍类
和数据库操作类。宿管中心管理员登录系统后，要执行添加新的学生宿舍数据的操作，系统创建并
显示维护宿舍信息界面，宿管中心管理员在界面上编辑完毕后，并且将更新后的数据返到维护宿舍
信息界面供浏览。添加宿舍信息时序图如图所示。
![image]()
1.4.2添加学生宿舍数据顺序图
2系统架构设计
软件架构是指在一定的设计原则基础上，从不同角度对组成系统的各部分进行搭配和安排，形成系
统的多个结构而组成架构，它包括该系统的各个组件，组件的外部可见属性及组件之间的相互关
系。组件的外部可见属性是指其他组件对该组件所做的假设。软件架构设计就是从宏观上说明一套
软件系统的组成与特性。软件架构设计是一系列有层次的决策，比如：功能与展现的决策；技术架
构的决策；自主研发还是合作；商业软件还是开源软件。
步骤:
1)预架构阶段:全面理解需求；需求结构化，摒弃“需求列表”，建立二维需求观（ADMEMS矩阵）。
使用ADMEMS矩阵方法，捋清需求间关系和发现衍生需求
2)概念架构:高层组件及其关系,
1、初步设计，基于关键功能，借助鲁棒图进行以发现职责为目的的初
步设计（不是必须）。
2、高层分割，将复杂系统切分为多个二级系统或多个子系统。
3、考虑非功能需求，采用ADMEMS推荐的目标-场景-决策表。
3)细化架构:5视图法在项目概要设计阶段，进行架构设计，制定规范和约定，为详细设计提供指导.
4)实现：详细设计，编码实现，在项目实现阶段，对开发人员提供规范指引和技术支持。
2.1系统逻辑体系架构设计
逻辑结构设计是将概念结构设计阶段所得到的概念模型转换为具体DBMS所能支持的数据模型（即
逻辑结构），并对其进行优化。
逻辑架构关注的是功能，包含用户直接可见的功能，还有系统中隐含的功能。或者更加通俗来描
述，逻辑架构更偏向我们日常所理解的“分层”，把一个项目分为“表示层、业务逻辑层、数据访问层”
这样经典的“三层架构”。
逻辑结构设计一般分为三步进行：
1.从E-R图向关系模式转化数据库的逻辑设计主要是将概念模型转换成一般的关系模式，也就是将ER图中的实体、实体的属性和实体之间的联系转化为关系模式。在转化过程中会遇到如下问题：
(1)命名问题。命名问题可以采用原名，也可以另行命名，避免重名。
(2)非原子属性问题。非原子属性问题可将其进行纵向和横行展开。
(3)联系转换问题。联系可用关系表示。
2.数据模型的优化数据库逻辑设计的结果不是唯一的。为了进一步提高数据库应用系统的性能，还
应该适当修改数据模型的结构，提高查询的速度。
3.关系视图设计关系视图的设计又称为外模式的设计，也叫用户模式设计，是用户可直接访问的数
据模式。同一系统中，不同用户可有不同的关系视图。关系视图来自逻辑模式，但在结构和形式上
可能不同于逻辑模式，所以它不是逻辑模式的简单子集。
关系视图主要有三个作用：
(1)通过外模式对逻辑模式的屏蔽，为应用程序提供了一定的逻辑独立性。
(2)更好地适应不同用户对数据的不同需求。
(3)为不同用户划定了访问数据的不同范围，有利于数据的保密。
![image]()
2.1.1系统包图
2.2系统物理体系架构设计
物理架构：物理架构，更关注的系统、网络、服务器等基础设施。例如：如何通过服务器部署和配
置网络环境，来实现应用程序的“可伸缩性、高可用性”。或者举一个实际的例子，如何通过设计基础
设施的架构，来保障网站能支持同时10W人在线、7*24小时提供服务，当超过10W人或者低于10W
人在线时，可以很方便的调整部署架构来支撑。
2.2.1构件图设计
构件图用来建模系统的各个构件，包括源代码文件、二进制文件、脚本文件、可执行文件之间的关
系，它们是通过功能或者文件组织在一起的。使用构件图可以帮助读者了解某个功能位于软件包的
哪一位置，以及各个版本的软件各包含哪些功能。
构件是系统的可替代的物理部分,它表示的是实际的事物.构件是定义了良好接口的物理实现单元.它
是系统中可以替代的部分.每个构件体现了系统设计中的特定类的实现.良好定义的构件不直接依赖于
其它构件而依赖于构件所支持的接口.在这种情况下,系统中的一个构件可以被支持正确的接口的其它
构件所替代.接口是被软件或硬件所支持的一个操作集.通过使用命名的接口,可以避免在系统的各个
构件之间直接发生依赖关系.有利于新构件的替换.
2.2.2部署图设计
UML部署图用来描述系统硬件节点构成，以及在这些节点上运行软件构件的分布。
部署图(deployment diagram，配置图)是用来显示系统中软件和硬件的物理架构。从部署图中，您可
以了解到软件和硬件组件之间的物理关系以及处理节点的组件分布情况。使用部署图可以显示运行
时系统的结构，同时还传达构成应用程序的硬件和软件元素的配置和部署方式。
![image]()
图2.2.2宿舍管理系统部署图设计
3系统详细设计
学生宿舍管理信息系统涵盖了学生宿舍管理中的各个功能模块，从学生入校分配房间，到入住宿
舍、日常卫生纪律检查、接待来访到毕业退住等环节形成一体化的管理一条龙，全部实现网络化办
公模式，大大降低管理实践中的手工劳动，提高了管理效率和水平。其总体功能结构设计如图所
示。
3.1功能详细设计
![image]()
3.2类模型详细设计
![image]()
图3.2.1控制类详细设计
![image]()
图3.2.2系统完整类图设计
4数据库分析与设计
数据库设计的目的：数据库设计的目的即设计目标从根本上来说就是要实现数据的共享和安全存
取，从细化及技术上来说，一个优秀的数据库设计必须要最终实现用户对于数据共享的具体要求，
必须要在满足于用户的数据存取要求的基础上实现对于数据的关联性及优化，必须实现数据的安全
性及可移植性，以保证用户数据能够简单的进行移植，必须要实现数据库的可扩容性结构以保证数
据库对于用户未来数据要求的兼容性等等。
数据设计的步骤：
1、需求分析：了解用户的数据需求、处理需求、安全性及完整性要求；需求分析的目标是准确了解
系统的应用环境，了解并分析用户对数据及数据处理的需求，是整个数据库设计过程中最重要步骤
之一，是其余各阶段的基础。在需求分析阶段，要求从各方面对整个组织进行调研，收集和分析各
项应用对信息和处理两方面的需求。
2、概念设计：通过数据抽象，设计系统概念模型，一般为E-R模型；概念设计阶段的目标是把需求
分析阶段得到的用户需求抽象为数据库的概念结构，即概念模式。设计关系型数据库的过程中，描
述概念结构的有力工具是E-R 图，概念结构设计分为局部E-R图和总体E-R图。总体E-R图由局部E
R图组成，设计时，一般先从局部E-R图开始设计，以减小设计的复杂度，最后由局部E-R图综合形
成总体E-R图。E-R图的相关知识参见第一章相关内容。
3、逻辑结构设计：设计系统的模式和外模式，对于关系模型主要是基本表和视图，概念设计的结果
得到的是与计算机软硬件具体性能无关的全局概念模式，概念结构无法在计算机中直接应用，需要
把概念结构转换成特定的DBMS所支持的数据模型，逻辑设计就是把上述概念模型转换成为某个具
体的DBMS所支持的数据模型并进行优化。逻辑结构设计一般分为三部分：概念转换成DBMS所支持
的数据模型、模型优化以及设计用户子模式。
4、物理结构设计：设计数据的存储结构和存取方法，如索引的设计；数据库的物理设计是指对数据
库的逻辑结构在指定的DBMS上建立起适合应用环境的物理结构。物理设计通常分为两步：
1、确定数据库的物理结构
2、对物理结构进行评价
5、系统实施：组织数据入库、编制应用程序、试运行；数据库完成设计之后，需要进行实施，以建
立真实的数据库。实施阶段的工作主要有：建立数据库，结构数据载入，应用程序的开发，数据库
试运行。
6、运行维护：系统投入运行，长期的维护工作。数据库经常性的维护工作
包括：
（1）数据库的转储和恢复。
（2）数据库的安全性、完整性控制。
（3）DBA应根据实际情况对数据库进行调整。
（4）数据库性能的监督、分析和改造。
（5）对监测数据进行分析，不断保证或改进系统的性能。
（6）数据库的重组织与重构造。
4.1数据库概念模型设计（vis io设计）
4.1.1学生实体ER模型
学生是高校教书育人活动中的客体和核心对象，同时也是本系统最主要的管理和服务对象。学生实
体的主要属性有学号、姓名、性别、出生日期、民族、籍贯、政治面貌、身份证号、所在班级、职
本务、、家庭电话、个 页面提供文档纯文本预览，下载后是原格式排版 人电话等。基于E-R模型，画出实体属性图如图所示。
![image]()
图4.1.1学生实体ER模型
4.1.2宿舍实体ER模型
宿舍是高校校园中学生生活、学习的主要场所，在本系统中作为最核心的资源来管理和分配。根据
我院实际情况了解，每间标准宿舍都设置6个床位、6套生活家具，核定住宿为6人。宿舍实体的主要
属性有宿舍号、楼栋号、核住人数、宿舍电话、床位数、家具套数、室内面积等。基于E-R模型，画
出实体属性图如图所示。
![image]()
4.2数据库逻辑模型设计
![image]()
图4.2.1系统总关系模型图4.3数据库的建立
4.3.1学生表（student）
![image]()
Student_roomno寝室编号VARCHAR(20)
建表语句：
Create table students(
Student_id varchar(20)primary key,Student_name varchar(20), Dept_no varchar(20),Student_age
int,Student_sex boolean, Student_classno varchar(20),Student_majorno varchar(20), Student_tel
varchar(20),
foreign key(dept_no)references department(dept_no), Foreign key(Student_classno)references
class(class_no), Foreign key(Student_majorno)references major(major_no) );
创建视图：create view v_student as select*from students;
4.3.2寝室表（dormitory）
![image]()
4.3.3学院表（department）
![image]()
4.3.4专业表（major）
![image]()
4.3.5班级表（class）
![image]()
4.3.6系统用户表（user）
![image]()






















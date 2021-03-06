# 雅虎往事
2011年6月~2014年5月我在雅虎工作了整整3年时间。很多是事情如果不记录下来恐怕以后也不会想起，也会再犯错误，所以在这里写下。所有情况实事求是。

## 开发流程
### Train Mode
当时雅虎流行的开发模式是“Train Mode”。所谓火车模式就是每个月定期交付一部分功能到生产环境上。这种方式乍一看是非常完美的：一，火车模式具备了敏捷开发的定期交付特征；二，如果相关功能没有通过测试那么可以等待下一个提交点的到来。这样整个团队在一个月的时间周期里面所完成的工作量就可以精确的度量。如果没有通过测试也比较坦然，等下一班就好了。那个时候对于开发人员的四个星期是：第一周做计划；二三周写代码；第四周提交给测试并上线。理论上对于测试人员是：一二周做测试计划和设计评审；三周跟进开发进行初步测试；第四周协调上线以及生产环境的验证。

看似轻松的工作隐藏着阴谋。第一，没人告诉你铁轨有好几条。第二，火车虽然不想晚点，但是乘客有可能上不去被卡在门上，于是不能开车。第三，如果单次乘客上的太少老大脸上肯定不好看。第四，每次功能的提出其实是有隐含的时间要求的，所以经常不能等下一班。第五，工程师是月度计划，失去的了执行力的敏捷性。于是Train Mode的结果是各趟火车横七竖八的趴在铁轨上转悠。周围是茫茫碌碌的乘客上蹿下跳。火车走走停停不时倒车。场面甚是欢乐。

大家都那么忙，于是软件质量就没有保障了。工作状态变成了：第一二周给项目擦屁股，也许是几个；第三周做本月的计划听别人发牢骚；第四周是忙碌的冒烟测试。由于大部分项目是从美国那边接手的，稍有闪失就能浪费几天的时间。于是乎一个好主意出现了：Scrum！让MM(Manger & Meeting)张牙舞爪起来！于是测试有可能每天要参加3次Scrum meeting,好像赶集一般。每个Scrum meeting的宗旨是：但凡相关的人都要来。办公室处处洋溢着紧张的气氛，敏捷开发的的最大优势立刻彰显：会议室不够用了。

### Scurm，Kanban
通常CEO的更换会带来相关的一轮技术更替，既然认识到整体公司处于低效的状态，那么引入敏捷开发就是唯一的选择了。刚刚引入的初期，培训和讲座就是铺天盖地的。优秀的理论总是需要正确的理解和执行，恰恰是在执行层面的不得要领造成功亏一篑。

## 测试
查看维基百科的定义，测试就是为了保证软件质量而进行的工作。而质量好与不好是个很难界定的东西。雅虎的测试工作在三年中进行过多次演化。
###蜻蜓点水，走马观花
###多层控制一把抓
###隐退与改进

车东

## 项目
### 历程
雅虎的3年中经历了3个CEO。公司总体的趋势是将组织结构不断扁平化。11年刚到雅虎的时候容力还是个经理，事必躬亲的一线。还记得他会和开发人员开会，一对一的讨论项目上的feature哪些重要，哪些可以忽略。当时Targeting的项目主要靠从美国抢。雅虎是靠广告起家的，初期的时候并不存在一个Targeting的组。后来大家发现把某一类人打包卖给广告主的方式行之有效，于是BT(Behavior Targeting)应运而生。BT的基本思想靠人对网络上的广告进行分类，然后再将能够命中这个分类的人包括进去。分类的广告包括C1(Engagers), C2(Shoppers), 搜索关键词，以及
space id之类。我在雅虎做的第一个项目CatTool就是一个导入广告数据并对其手工分类的一个内部工具。

在雅虎如日中天时的主导技术是yApache, PHP, Maple, Java, C 和YINST。在我进入的时候还能看到一些数据处理流程是C+crontab， Perl+crontab进行的。后来，这些系统越来越多的被Java+Oozie所取代。前端的网站开始变成NodeJS+HTML+WebService。我的第一个项目CatTool就是用通过Perl ETL进行数据的导入，然后各国的分类人员通过一个yApache host的PHP网站进行真正的分类工作。后台的数据库是个Oracle。CatTool是个老而弥坚的项目，说来非常有趣。




## 技术与培训

## 人和事
### 华丽
进雅虎以前我从来没有接触过Linux，人对于自己的无知有两种态度：洋洋自得和过度恐惧。我属于后一种。而华丽就是我的老师。

2011年的雅虎还在清华科技园办公。记忆中清华科技园是个阴冷潮湿的地方。之所以阴冷是因为入职的时候正直春夏，空调大开阴风刺骨。整个楼是灰色的，地毯的灰色的，窗帘紧闭。楼道中是烟民的聚集地。通风扇里面吹来的是湿润的空气。一股男生宿舍的味道。当时的工作环境尴尬而紧凑。

![cube](../images/yahoo-office-20110708.jpg)

> 左边是曹磊，我在中间，右面就是华丽的位置。三个人挤在一起却除了工作上的内容很少说其他的。每天中午12点准时去吃饭，饭后大概有20分钟可以浏览网页和新闻。这大概与A和J同学坐得比较近有关。椅子上搭着的粉红卫衣是华丽的。她通常会用卫衣帽子反向套住头小睡上10分钟。虽然只有10分钟，也是需要勇气和胆量的。如果过了13：10分还没有起来，那就比较危险了。彼时我们都入职没多久，工作中多是含着忐忑。曹磊算是元老了，和他也学了不少。

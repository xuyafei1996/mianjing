# 2020春季实习生招聘面经

面经整理 持续更新中

## fs面经汇总

### 腾讯CDG事业群（二面凉）  

3.9 电话沟通  
3.12 19:00-20:10 一面  
自我介绍？  
jdk了解么？  
hashmap底层？扩容实现？多线程问题？  
concurrentHashMap？读写操作实现？锁机制？实现维持map大小的LRU算法？  

volatile关键字？volatile修饰数组？修饰对象？  

找两条链表公共节点？  
如何判断循环链表？  

mysql索引？B+数搜索复杂度？  
mysql事务？  

进程线程区别？  
进程池？  
进程几种状态？调用sleep方法进程是什么状态？  
单线程，4核cpu，如何让cpu维持50%使用率？  

http了解么？包含什么？  
输入url之后过程？  
tcp如何保证稳定性准确性？  

controller如何知道信息？  
信息如何从网卡到controller？  
一个请求如何被服务器得知？Tomcat如何知道有请求？  
NIO？  
如何实现一个服务器端？  

你有什么问题问我？  



### 3.15 9:00-9:30 腾讯二面  

自我介绍  
详细说说自己的经历  
详细说说做的项目  
你认为后端开发主要做些什么？  
你认为做开发你的优势是什么？  

前后端交互协议？  
http（结构？第一行是什么？）  
http1.0/1.1/2.0区别？  
ref？（查了下是Dubbo里的，之前完全没接触过。。。）  
操作系统原理？应用场景？（听不懂问题。。。）  
缓存作用，应用场景？  
自己实现一个缓存（用什么数据结构？需要快速查询和实现LRU）  
学习能力如何？具体例子？  



### 3.20 阿里巴巴笔试（2道，一道都没做出来QAQ）  

### 3.22 21:30--23:20一面

自我介绍  
个人经历  
为何转行  
项目详情  
mysql索引？  
知道组合索引么？  
知道mysql执行计划么？  
事务隔离级别？  
秒杀场景，库存超卖如何解决？  
乐观锁和悲观锁？sql怎么写？  
mysql优化策略？用户订单表如何分表？  
分布式事务？  
exception，throwable，error？  
runtime能catch么  
throwable能catch么？  
说说快排和堆排序一般的应用场景，时间复杂度  
4个足球队，两两比赛，赢得3分，平手1分，输0分，4个足球队加起来总分有几种情况？取值范围？  
笔试两道题有下去查过么？怎么解决？  
hashmap，hashtable区别  
hashmap底层构造，常用方法实现  
设计模式了解哪些？认为哪个好  
volatile实现  
threadLocal  
redis  
一致性哈希  

### 3.19 美团笔试 （5道做出来1.5道QAQ）

### 3.23 14:30--15:40 美团一面

自我介绍  
StringBuilder，StringBuffer区别  
List，Set区别，使用场景，可以有null值么，有多个可以么  
深拷贝，浅拷贝，如何实现  
hashmap底层，扩容机制，扩容有什么问题？多线程应用有什么问题？  
jvm内存分区s0，s1  
创建对象在jvm内存中的具体流程  
gc算法  
线程池常用参数？CorePoolSize一般设多大？  
提交任务流程，缓存队列设计为无界队列可以么？  
有界队列和无界队列？  
线程状态  
进程间通信机制  
mysql索引  
索引中，用where（给出了各种实例）索引怎么用的  
事务隔离级别  
mvcc  
cas aba问题，如何解决？  
volatile关键字，synchronized关键字  
tcp、udp区别，在4层结构哪一层  
tcp流量控制实现  
tcp三次握手，四次挥手（答到一半被打断了，嫌我说太多。。。）  
linux查找文件中的字段并高亮显示  
手撕代码：快排实现  
平时如何学习？  
你有什么问题问？  

3.24 二面 11:30--12:35  
自我介绍  
项目详细介绍，为什么重构它，有什么问题？  
spring核心原理ioc，aop，SpringBean生命周期过程  
MyBatis映射文件  
手撕算法：  
2N个数，N+1个不同，N个相同，找出相同的那个数  
给他说了暴力1/2算法，排序算法，计数法，滑动窗口，最后写了滑动窗口，最后改良为直接比较  

二叉树前序遍历非递归写法  
你有什么想问？  



### 3.24 腾讯一面 20:20-21:50

手撕算法并改进  
1、两个有序（从小到大）单链表，构造一条新链表，包含出现在两个链表的等值节点  
struct LinkNode {  
  int value;  
  struct LinkNode * next;    
};  
struct LinkNode * intersect( struct LinkNode * firstLink, struct LinkNode * secondLink );   

2、设定如下的对应关系( A=1,B=2,C=3,...,Z=26,AA=27,AB=28,...,AAA=xxx,... )，编写一个转换函数，根据上面的规则把一个字符串转换为数字  
int StrToInt( const char * str );  


3、在二叉排序树上面找出第3大的节点。注意：不能把二叉树全量存储到另外的存储空间，比如存储到数组中，然后取出数组的第三个元素。  
struct TreeNode {  
        int value;  
        struct TreeNode * left, * right;  
};  
struct TreeNode * find( struct TreeNode * root );  

4、给定一个数字串，使用","将数字串拆分为不大于1000的多个的数字，输出所有可能性  
例如数字串 1111 可拆分为：  
1,1,1,1  
1,1,11  
1,11,1  
1,111  
11,1,1  
11,11  
111,1  

做过什么项目？  
平时刷题多么？  
以前是什么专业？多久毕业？  

### 3.25 腾讯二面 18:30--20:20

手撕代码，然后给他讲解过程。
1.对于一棵满二叉排序树深度为K，节点数为 2^K - 1 ；节点值为 1至 (2^K-1)。 
给出K和任意三个节点的值，输出包含该三个节点的最小子树的根节点值
样例输入：k =4 节点：10 15 13
样例输出：12



2.实现一个基于Hash的全内存LRU cache，插入时，发现节点个数超过阈值，则按照全局最近最少使用淘汰节点。
采用链地址法解决Hash冲突：Hash桶个数固定为1千万，最多只能存储1亿个的节点，每个节点的key和value都为uint32_t。
采用malloc 和 free 分配和释放内存，不需要实现内存池。

Struct Node｛    
    uint32_t iKey;   
    uint32_t iElem;  
    其它字段 ...     
};

请分别实现Insert，Get接口。



3.逐行打印n * n回型矩阵（ 不可以在内存填好整个矩阵然后再打印）

n=3     
1 2 3   
8 9 4   
7 6 5

n=4     
1 2 3 4     
12 13 14 5      
11 16 15 6  
10 9 8 7 

讲一下你的项目吧?

实习对地点有要求么？

## 3.31 腾讯HR面 16:30-17:00
自我介绍    
对面试的部门了解么   
还面过哪些公司？面试的部门都选的什么？     
对工作地点有要求么？服从调剂么？    
考研为什么选择南京大学？    
如何协调工作和学习？  
平时怎么学习？     
面试完之后有总结并学习么？
<hr>

## czy面经汇总

### wxg 微信事业群

3.22日  
一面  
自我介绍  
聊项目  
算法  
1、链表的快排  
2、能否成环，以及环的入口  
3、数的开平方  
4、AVL树的旋转  
5、AVL树与堆的区别  

MySQL  
1、查询优化  
2、表是如何设计的  
3、表的连接  

网络  
1、Http的请求函数  
2、三次握手协议  
3、Socket与SocketServer的实现连接与发送请求  

Java  
1、Map底层的源码 ：HashMap  ConcurrentMap  HashTable  

Linux  
1、文件操作的指令  
2、查看网络的指令  

### 微软笔试3.25

1、题目：根据一个数组，分成若干组，每个组k个数（每组的数不重复），每个组算得最大值与最小值的差，将每个组的差求和，求如何分组，使得和最小。  
用例{3，3，4，5，5，6，6，8，8，10，10} k = 4  
输出结果为 15  
2、LeetCode1246（删除回文子数组）

### 美团笔试3.26 （AC 1.5道/ 5道）

1、题目：数字转换，给一个数字k和一个数组ai[]（数组是长度为9的数组ai(1<= i <= 9)，每个位置i对应的值代表 i对应的数字值），将每个位的数字转换为对应数组位置的数字，输出结果。   
用例： k = -12,ai = {2,3,4,5,6,7,8,9,1} 输出结果为 ： -23；  
解释： 1对应ai中位置为1的数2，2对应ai中位置为3的数3，转换后为-23； 
这道题当时不应该将字符串转成数字，因为字符长度太大，数字显然不够用，只通过了50%的用例。 

2、题目：求同心圆的面积，给定一个数组{1,2,3,4,5}代表每个圆的半径，规则：圆是黑白相间的，最里面是个圆，然后是空心环，然后是实心环，然后空心环……
要求是对实心区域求面积，要求精确度为5位小数，并四舍五入。    
很迷的一道题，明明排序，用Math.pi做的，过了50%的用例。    

3、题目：子序列计数问题，对于一个序列arr[],如果对于它的子序列subArr[]中，每个位置都符合——subArr[i] % i == 0，i对应位置（1 <=i <= subArr.length）,那么称这个序列为有趣，求这种有趣序列的个数。  
用例：{1，3，2} 输出为：5  
解释：子序列有{1} ，{3}，{2}，{1，2}，{3，2}满足有趣子序列。  

4、5暂空。  

### 招商银行信用卡中心 3.27 

选择48分（12道），编程52分（两道）  
1、题目：给一个数组a[]，数组的每个位置的值代表同一颜色的袜子的数量，求至少要拿多少只袜子，肯定出现相同颜色的袜子。    
用例：{2,2} 输出：3  
解释：最坏的情况是，不同颜色的必须都拿一只，然后再拿一只就肯定满足题意。  
2、题目：给两个数组，分别代表木棍的长度L[]和花费cost[]，然后每个棍子拿的过程会消耗1，但是如果相邻的棍子的长度和花费都要大于等于之前一个的棍子    
那么该棍子是没有消耗的，所有棍子的排列顺序是可以改变的，问怎么排序，使得消耗最少。    
用例：长度L[] = {4 9 5 2 2} ,花费cost[] = {1 3 5 1 4};输出：2  
解释 ： 2 2 5 4 9  
       1 4 5 1 3  只有棍子 1，4有消耗，所以消耗为2.  
       
### 阿里巴巴笔试汇总  
## 3.23  
1、一共n个人，从中选出任意个人组成一队，我们不妨记为k，再从k个人选出一人做队长。  
2、走迷宫 输入一个n行m列字符串 S为起点E为终点 . 表示可同行#表示不可通过 求最短路径 可上下左右走动 可进行飞行操作 （移动到n+1-x，m+1-y）坐标上去 要求5步以内完成 否则输出-1  
转自链接：https://blog.csdn.net/sdsfdsfdsds/article/details/105056225?depth_1-utm_source=distribute.pc_relevant.none-task&utm_source=distribute.pc_relevant.none-task

## 3.25  
第一题：  
3 * n的数组，每行列选出一个数字，输出他们的差值的绝对值的最小值。  
如：  
5 9 5 4 4  
4 7 4 10 3  
2 10 9 2 3  
最小值为5。 【5，7，5，4，4】 ，差值为2 + 2 + 1 = 5.  
第二题：  
输入n * m的数组，以及q次查询。  
例如 如下数组， 为0代表未知。  
数组的行和列都可以构成等差数列（忘了有没有等比的条件）  
1 0 3  
0 0 0  
q次查询为输入的数组，分别输入x,y，代表x行y列。例如当q = 4时。  
1 1  
1 2
2 1  
2 3  
输出：  
q次查询的结果，有值输出值，值不确定输出Unknow  
转自链接：https://www.nowcoder.com/discuss/391538?type=post&order=time&pos=&page=1  

## 3.27
第一题： 
要求：将字符串s1转换为s2,  
转换规则：每次可以将s1中的任意一个字符移动到s1的末尾  
目的：求最少的改变次数时，s1转换为s2  
输入：  
acdk  
ckad  
输出：2  

第二题：
求n个随机数中最小值的期望值
三行输入，分别为：
n: 随机数的个数
l1, l2, ... ln : li 为第i个随机数的最小值
r1, r2, ... rn ：ri 为第i个随机数的最大值
即第i个随机数的取值区间是 [li, ri]，取到区间里数字的概率相等
输出为随机数最小值的期望
还有一些关于浮点数的要求（记不清楚了）
转自链接：https://www.nowcoder.com/discuss/393479?type=post&order=time&pos=&page=1

## 3.30  
第一题： 
n个鸡场，初始每个有a[i]只鸡，每天增长k只，并且每天最多的那个鸡场，卖一半鸡（向下取整），问m天后共几只鸡； 

第二题:
n个元素的数组，在它的连续子串（连续就是挨着的）中，随机取一个，然后取它的最大值，求这样取出的最大值的期望。（eg，就是【1、2、3】，连续子串有【1】【2】【3】【1、2】【2、3】【1、2、3】，然后比如【1、2、3】的最大值就是3）  
转自链接：https://www.nowcoder.com/discuss/396031?type=post&order=time&pos=&page=1


### 美团面试 3.31

一面  
1、算法：字符串的旋转操作，能否使得两个字符串相等。  
2、介绍一下JVM虚拟机的知识：内存区域划分、垃圾收集机制。  
3、在项目中的SQL优化操作。  
4、Spring的AOP和IOC，以及不使用IOC的不良影响。  
5、聊项目，petri网解析过程的核心算法，然后如何解决的？  
6、你有什么想问的？  
有点抢话，希望下次能在结尾的时候多听听别人说，不急于展示自己。  

二面 4.8
1、自我介绍一下  
2、你这些项目中最具有挑战的是哪一个？主要做了哪些东西？  
3、MySQL是如何优化的？    
4、索引的最左匹配了解吗？如果匹配其他的列可以不可以用到索引，为啥？  
5、垂直分割与水平分割是怎么分割的，垂直分割对应的业务场景？  
6、Spring的AOP熟悉吗？讲讲在开发中用到的场景
7、Spring中 JAVA Bean的生命周期讲讲  
8、ConcurrentHashMap的内部机制  
9、volatile知道吗？
10、虚拟机的G1知道吗？  
11、git用的多吗？讲讲一些指令  
12、你有没有想问的？  
13、实习时间能出来实习多久？  
14、周末干啥？  
<hr>

## cp面经汇总

### 阿里巴巴面经

数据结构:  
排序有哪些，时间复杂度。讲一下归并和快排。  
链表找到其三分之一位置  
图的最短路径算法 讲一讲  
有权图无权图  
有权图的最短路径咋找  
前序遍历，中序遍历，后序遍历。  
平衡二叉树的复杂度，定义。  
平衡二叉树怎么旋转。自己实现过吗？  
队列和栈的区别  
网络：  
TCP 三次握手，四次挥手多了啥  
HTTP 啥层的协议  
七层模型，每层是干啥的  
数据库：  
MySQL 的索引结构  
为啥用B+树  
数据库事务  
隔离级别  
啥级别不会有幻读  
MySQL 的底层加锁是咋加的 （生成一个啥？我没懂我不会）  
JAVA  
HashMap 1.7 1.8 区别  
树化的阈值，初始大小，0.75那个，讲下resize里面怎么调整的  
线程安全用啥能整，ConcurrentHashMap put过程  
JVM  
JVM垃圾清除算法有哪几种  
CMS 咋清除的 SWT几次  
啥样的会被选做 GC ROOT  
双亲委派，啥样的破坏双亲委派，TOMCAT 为啥要破坏双亲委派  
sychronized 锁升级  
问我 OAuth2 授权码模式咋整的  

## cvte面经

OAuth2 有啥作用  
Redis 咋用的呀   
MD5 为啥有缺陷   
BCrypt   
咋解决 MD5 缺陷  
innodb 讲一讲  
innodb 怎么容灾的   
写 SQL   
innodb 自己有啥缓存方法   
Redis 的持久化   
Time-Wait 为啥要整两个   
很多 Time-Wait 如何排查   
TOMCAT 怎么处理一个请求   
如果 Time-Wait 很多你怎么排查   
负载因子 变换会有啥问题   
AOP Cglib 为啥比 Proxy 快   

## 腾讯面经

硬拷贝和软拷贝 为啥需要硬拷贝 为啥需要软拷贝  
硬拷贝软拷贝存在哪  
多线程 多进程 优缺点  
socket 编程  
进程之间通信  
TCP UDP 之间的区别  
聊聊 GC  
设计模式有什么  
单例模式怎么实现  
HTTP 长连接和短链接，什么情况下用短链接不叫好，什么情况下用长链接比较合适    

<hr>

## djq面经汇总  

### 蚂蚁金服一面  
（笔试很简单，多线程循环打印1—100奇偶数）
1. 你觉得项目中用了MQ给你带了什么好处，设计初衷是什么？会带来什么缺点嘛？（项目针对性比较强，不细说）
2. 在网页键入taobao.com，到返回一个页面，这期间都发生了什么？
3. 你说到了session和cookie，这两者有什么区别，应用场景是啥？
4. 返回界面的文字，图片，链接，你觉得是从哪里来的，或者说储存在哪里?
5. 描述一下TCP三次握手，这期间可以携带数据吗？携带了数据会造成什么后果？
6. 描述一下四次分手，第二次和第三次中间处于何种状态？
7. 说一下object类的所有方法以及他们的功能（真的是所有：clone，notify/all，finalize，wait，hashcode，equals，tostring，getclass）
8. 抽象类和接口有什么区别？说一下你的个人理解。
9. 详细说一下final关键字，修饰变量，方法，类都有什么不同？能想到什么具体应用场景吗？
10. 说一下equals方法，hashmap的底层，跟hashtable，concurrentHashMap都什么区别
11. 静态分派和动态分派的区别？具体应用场景？
12. 1.8concurrentHashMap有什么变化，优化的意义在哪？
13. hashmap除了结点数大于8，还有什么情况会树化（这个我没想出来，也可能是我没听清楚）
14. hashcode方法有什么特点？hashset的底层是如何实现的？为什么用hashmap？
15. 说说JVM内存结构（这里要问清楚是JMM还是运行时常量池）
16. 你刚说1.8后方法区移动到内存中变成元空间，为什么要移过去呢？
17. 那为什么常量池没有移动到内存，而是转移到堆了呢？
18. 最后一个问题，说一下线程池的饱和策略

### 蚂蚁金服二面
1. 从项目启动到现在，介绍一下你的工作以及遇到的难点，怎么解决的？
2. 讲一下微服务架构都有哪些模块？他们是怎么一起工作的？
3. 让你实现一个eureka，你会怎么实现？
4. 用户认证，为什么要用JWT，而没用session-cookie，应用场景？优劣？加密用的是什么算法？
5. 为什么使用rabbitMQ，没用别的mq？
6. 说一说你项目应用了什么设计模式？适配器模式什么应用场景？
7. 让你实现AOP，你怎么实现？
8. spring事务有了解吗？是如何传播的？在你项目里的实际业务中是如何传播的？
9. 例如有ABC三个事务，分别原子性，整体也原子性，A事务出错回滚，整体事务也会回滚，你会怎么设计呢？
10. ZooKeeper有了解吗？redis和Mencache的选型问题?
11. 你之前的webServer项目介绍一下整个流程?你是如何做的多线程？socket相关?
12. 你怎么使用线程池？参数怎么选择？
13. 你写线程的时候会给他们起个可爱的名字吗？为什么要起？线程错误排查工具用过哪些？
14. spring framework都有哪些模块？你使用到了哪些模块？怎么使用的？
15. 使用的时候有没有对某模块功能进行扩展？
16. 说一下集合类（线程安全角度）

### 蚂蚁金服三面
1. 详细介绍一下点云扩增工具项目
2. 你对分布式架构有什么理解？
3. 总结一下你的本科与研究生阶段有过的成就？可以拿来说的那种？
4. 参加过竞赛吗？
5. 你的项目中或在学习过程中有没有遇到过很难的点？然后专心研究去解决掉他的？
6. 周围有没有优秀的人？有没有值得你学习的点，并且你现在在跟着做的？
7. 平时看什么书？
8. 有没有根据兴趣学习过一些额外的计算机知识，AI领域?
9. 在github研究过哪些开源项目？
10. 你的职业规划是什么样的？

### 蚂蚁金服四面hr
1.做个自我介绍
2.说一下你本科到研究生阶段你觉得出彩的事情，学习方面或业余活动都可以。
3.这些活动你最大的收获是什么？
4.你在学习中遇到过最大的困难是什么？然后详细说一说解决困难的过程。
5.你们团队的结构？如何分工？你觉得你的角色发挥了什么作用呢？
6.你到现在做过最刺激的事情是什么？除了这种旅游的刺激项目还有其他方面的吗？
7.给你出个场景题吧：如果你是南京一个铅笔厂的市场经理，你的老板想要你打入杭州的铅笔市场，你该做一些什么调研呢？或者说怎么说服让老板给你启动资金。具体一点比如说要考虑哪些因素？
8.你平时会和同学们聊哪方面的技术话题，关注什么前沿领域？
9.你有什么特别想做的
10.你的同学和老师怎么评价你？
11.你来阿里最想提升自己哪方面？
12.你的职业规划？
13.询问具体实习时间以及是否愿意来杭州
<hr>

## shanhe面经

### 阿里CCO一面 3.31 后端

- 自我介绍
- 聊了些经历,因为我本科毕业后中间有三年左右的gap,问了我是否从事互联网行业工作
- 项目中有什么亮点(其他的一些项目细节,比如项目是否已经运行?是否有人使用?抛开中间件,你怎么设计一个用户权限或者搜索?)
- 你在项目管理中是怎么做的?
- 用户登陆是怎么做的?
- cookie和session的区别
- java有几个基本数据类型,分别是多少字节?
- java中的访问权限有哪些,分别是什么意思?
- 为什么hashCode()方法和equals()方法要一起重写?
- 两个不同的对象可以有相同的hash值吗?
- HashMap底层结构是什么
- 线程池知道吗?
- 有哪些核心属性?
- 如何建立一个线程池
- 请描述一下线程池中的线程增加并达到最大的过程
- 线程池达到最大并且等待队列也满了以后,还有线程申请调用线程池内的线程进行任务,会发生什么?
- Threadlocal了解吗?
- 有没有遇到过栈溢出或者内存溢出?怎么解决的?
- heap堆里面的溢出是怎么解决的?
- 描述一下jvm内存模型
- heap堆里面更细分的有哪些区域?
- 平时使用什么数据库?
- 数据库事务有哪些属性?
- 一致性是什么意思?
- 数据库并发会带来哪些问题?
- 详细描述一下数据丢失的场景
- MySQL是怎么解决数据丢失的?
- 索引有了解吗?为什么使用索引更快?
- 你刚才提到了回表,为什么回表次数更少?
- 索引的数据结构是什么样的?
- SQL优化有了解吗?是否在实际中使用过?
- 如果让你进行优化,你会从哪方面进行考虑?
- 你刚才提到了分表,具体如何操作?
- 分库如何保证key值唯一?
- 你刚才提到了使用不同的步长保证key值唯一,那么具体操作该怎么做呢?
- 并发情况下如何保证数据的一致性?
- 你刚才提到使用sycronized,这个是jvm提供的锁机制,在分布式系统下是不生效的,那么我们如何在分布式下保证数据的一致性?
- Linux了解吗?知道哪些命令?
- 如何在一个文件中查找某个字符串出现的次数
- 你使用过哪些设计模式
- 工厂模式有很多,抽象工厂、变量工厂等,请你详细说明一下他们的应用场景
- 单例模式分几种分别是什么?
- Spring的特性是什么?
- AOP是如何实现的?
- 描述一下MVC模式
- 最后问一下TCP协议中的三次握手是什么?为什么非要三次?
- 平时喜欢看什么书?
- 从什么时候开始接触的互联网这行?
- 你还有什么问题吗?

### 阿里飞猪一面 测试(第二次打电话凉)

- static了解吗?有哪些特性?
- 为什么static修饰的方法无法被非static修饰的方法使用?
- ArrayList和LinkedList的区别
- TreeMap和HashMap有什么区别?
- HashMap底层实现?
- 多态了解吗?
- 下面程序输出的是什么?

```java
class A{
    public String show(D obj){
        return ("A D");
    }

    public String show(A obj){
        return ("A A");
    }
}

class B extends A {
    public String show(B obj){//
        return ("B B");
    }

    public String show(A obj){
        return ("B A");
    }

}

class C extends B{}

class D extends B{}

class Test {

    public static void main(String [] args) {
        A a1 = new A();
        A a2 = new B();
        B b = new B();
        C c = new C();
        D d = new D();

        System.out.println(a1.show(b));   //① A A

        System.out.println(a1.show(c));   //② A A

        System.out.println(a1.show(d));   //③ A D

        System.out.println(a2.show(b));   //④ B A

        System.out.println(a2.show(c));   //⑤ B A

        System.out.println(a2.show(d));  // ⑥ A D

        System.out.println(b.show(b));    //⑦ B B

        System.out.println(b.show(c));    //⑧ B B

        System.out.println(b.show(d));    //⑨ A D
    }
}

```

- 在一段程序中,有可能抛异常,但是我们某段代码一定要在最后执行,如何实现?
- 哪些排序的时间复杂度是O(nlogn)?
- 然后是一个算法题,检验括号有效性,输入只有括号,有效输出true否则false,要求时间复杂度O(n),空间复杂度O(1)
- 如下表格如何找出数学成绩大于80的同学的学生信息

```
   tbl_student
Name     age     Height
Lily   18  50
Jim    19   60
Ann    18  48
  
   tbl_score
Id  Name Math English
1 Jim  90 90
2 Mei 80 80
3 Lily 70 90
```

二面没问啥东西,挂得莫名其妙

### 腾讯wxg一面(直接凉,自此就是腾讯黑)

- 自我介绍

- 平时使用什么开发?

- 会不会用C++(我说我不会,然后面试官:我们都是用C++的啊?然后开始走流程)

- 接下来牛客两道题,简单得一批,但Java环境不能提交,一道是两个已排序链表合并到一个,一道是链表排序

- 然后开始找我茬,看我第二题用的双链表问我为什么要增加时间复杂度?

  我???要不是你不是在那儿不耐烦的催我写我能为了求尽快写完用双链表?

- 然后问写些Linux命令

- 如何查找进程,要求显示各个进程的负载率

- 如何查找端口

- 数据库的事务是什么?

### 4.8 15:00-15:30 美团一面

- 自我介绍
- java的基本类型有哪些?
- 对象和基本类型的区别?
- final修饰词怎么用?
- 所有类的父类是什么?有哪些常用方法?
- HashMap底层原理(实现和扩容机制),线程安全嘛?线程不安全会带来哪些问题?
- 如何实现线程同步?
- Synchronized怎么实现线程同步的?(底层原理)
- 二叉树的深度遍历和广度遍历如何实现?
- 排序算法有几种是件复杂度?每一个时间复杂度都有哪些排序算法?
- MySQL有哪些索引(从数据结构角度来说)?
- b+树索引的数据结构是什么样的?这种索引的好处在哪?
- 查询多列值时想要使用索引,需要注意什么?
- explain有了解吗?里面需要注意哪些列?
- 计算机网络模型是什么样的?
- Nginx负载均衡是哪一层的协议?
- Spring框架有哪些特点?
- filter和intercepor可以交给Spring容器创建吗?
- 在你自己做的项目中,印象最深的功能是哪一个?

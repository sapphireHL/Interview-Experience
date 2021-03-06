# 春招实习面经

## 网易游戏
### 视频一面
- 1、自我介绍
- 2、看你研究的是三维测量，能介绍一下吗
- 3、进程调度方式（先来先服务，最短工作优先，最优响应比优先，时间片轮转）
- 4、线程同步方法（互斥锁，信号量，条件变量）
- 5、死锁是怎样的
- 6、TCP、UDP区别
- 7、为什么要字节对齐
- 8、虚函数会增加类的大小吗
- 9、图形学了解吗
- 10、stable_sort和sort区别
- 11、异常安全讲一下（查一下）
- 12、手写strncpy
- 13、两个矩形怎么判断重叠

## 360
### 视频一面
- 1、自我介绍
- 2、Linux系统了解深吗，命令，用了什么网络编程接口
- 3、epoll和select区别
- 4、epoll两种触发模式
- 5、Linux多线程并发机制
- 6、Linux有哪些锁
- 7、shell脚本懂吗，awk，cd
- 8、纯虚函数概念
- 9、内存泄漏从编程上怎么避免（智能指针）
- 10、编程，找到第一个只出现一次的字符
- 11、编程，树的层序遍历
- 12、二叉树最远两个节点的距离（说思路）
- 13、动态地求中位数（说思路）
- 14、分布式系统，zookeeper，大数据接触过吗
- 15、其他技术有了解吗，libevent
- 16、服务器挂掉了重启发现端口被占用了，可以在编程避免吗（setsockopt，reuseaddr）
- 17、项目有用到动态库静态库吗

### 视频二面
- 1、在浏览器输入url到页面显示的过程
- 2、TCP建立连接的过程
- 3、讲解一下线程池模型
- 4、工作队列用的什么数据结构，多线程同步怎么处理
- 5、高并发频繁加锁对性能有影响吗，怎么优化（减小锁的粒度，无锁队列）
- 6、主线程往工作队列加任务，如果请求量大，主线程可能工作不过来吗
- 7、worker线程处理ok，主线程出现瓶颈怎么做
- 8、编程，多个有序的vector，提取出所有vector的公共元素，排好序输出（复杂度）
- 9、设计一个图片服务器，从哪些角度思考，哪些功能（上传图片，看别人图片，搜索特定用户，图片标签，搜索图片，查看热门图片），考虑用户量很庞大，数据量也很庞大，服务器会出现什么问题（处理不过来），为什么会处理不过来，从哪些角度解决（多机，负载均衡），多机处理面临什么问题（切分流量，水平扩展），怎么解决。几个概念你有听说过吗，loadbalance（负载均衡），

## 百度
### 视频一面
- 1、自我介绍
- 2、手写二分查找
- 3、有个大文件，有很多行，每行一个key value，key有序，给个key，把key对应的那一行输出（对key二分查找，文件头尾指针，fseek）
- 4、讲一下reactor模式
- 5、epoll和select区别，epoll底层原理，线程池实现思路，如果所有线程都在工作，又来了一些任务，这时候会发生什么，工作队列同步
- 6、http协议的关键点
- 7、服务器性能测试过吗，和主流的服务器比较过吗，并发量，吞吐量
- 8、设计模式了解吗，单例模式的场景，实现原理
- 9、http报文特别大，每次读多少字节，一个报文分几次发送，怎么完整接受，有没有试过发送特别大的报文，这是TCP里面的什么问题（粘包）
- 10、机器学习了解吗
- 11、给个哈希表，每个doc包含一些terms，现在要找出一个terms出现在哪些doc里
- 12、平时用linux吗，简单命令了解哪些，管道熟悉吗，有一个文件输出第100行到200行，用head和tail实现
- 13、大数据，hadoop，mapreduce了解吗

### 视频二面
- 1、自我介绍
- 2、服务器怎么实现的
- 3、子线程如果卡住了，会一直等待吗
- 4、nginx，apache的处理模型是什么样，nginx的工作进程接受请求的方法和你的有什么区别（nginx工作进程不会卡住，全异步）
- 5、怎么判断哪个线程空闲，怎么让程序充分利用多核，线程实际上是在多核上跑吗
- 6、实现了http哪个版本的协议，http1.0，1.1，2.0的区别
- 7、怎么区分header和body的内容
- 8、如果别人想用你的服务器写业务逻辑，怎么写
- 9、有哪些配置，配置文件（端口）
- 10、对于post请求加一些限制，在你这里具体怎么实现
- 11、两个请求同时来，会同时接受还是阻塞一个，http2.0了解吗
- 12、keep-alive，长连接有什么好处
- 13、一个客户端多个请求会复用这个连接吗
- 14、编程，最大子序列
- 15、你想从事哪个方向工作
（建议：和开源的server比较一下，看怎么优化，对linux熟悉，awk，lua）

### 视频三面
- 1、自我介绍
- 2、你做的难度最高的项目，遇到什么困难，怎么解决的
- 3、服务器架构
- 4、做项目收获了什么
- 5、编程，有序数组，从中间取一个点前后颠倒，给一个值，返回其下标
- 6、非计算机怎么想到编程
- 7、职业规划，5年内
- 8、技术管理是什么样的
- 9、100个人100盏灯，每个人会把自身倍数的灯置反，开始都是灭的，最后哪些灯是亮的
- 10、有个项目你负责，你带两个实习的同学，到了规定的时间有个同学没做完，你应该怎么做，下次遇到同样的问题会怎么做


## 头条
### 视频一面
- 1、编程，求二叉树中序遍历的下一个节点
- 2、http服务器讲一下
- 3、reactor模式是什么
- 4、做过压力测试吗，支持多少并发，瓶颈在哪里，服务器什么配置，几核，内存
- 5、如果要支持很大并发量，需要什么资源（单机50w连接没问题）
- 6、为什么要做服务器
- 7、epoll和select的区别
- 8、什么时候用水平触发什么时候用边缘触发
- 9、同步异步，阻塞io非阻塞io讲一下
- 10、进程有几种状态（创建，就绪，运行，阻塞，结束）
- 11、进程线程区别，多线程会共享哪些（全局变量，堆，静态变量，文件），一个线程的栈有多大（2m？）
- 12、static哪些作用（4个）
- 13、程序入口main可以改变吗（可以）
- 14、虚函数讲一下
- 15、编程说思路：股票买卖最大利润（leetcode）

### 视频二面
- 1、编程，链表，奇数位升序偶数位降序，对链表排序
- 2、LRU怎么实现（哈希+双向链表，O（1））
- 3、有一个数据结构，存用户和得分，想快速得到300到500分的所有用户（区间查找），用什么数据结构实现（b+树）
- 4、https了解吗，安全是怎么做的（认证，加密）
- 5、介绍下tcp三次握手和四次挥手
- 6、客户端发syn后处于什么状态（syn-sent），服务器返回syn之后（syn-receive），服务器接收到fin之后（close-wait）

### 视频三面
- 1、自我介绍
- 2、介绍下http服务器，做过压力测试吗
- 3、编程，求二叉树的最长路径长度
- 4、编程，长宽为n和m的咖啡店，店里有顾客和障碍，寻找一个出发点，使得到所有顾客的距离之和最短，不能跨障碍，上下左右行走


## 腾讯
### 现场一面
- 1、自我介绍
- 2、tcp三次握手，断开为什么需要四次
- 3、reactor和线程池介绍一下
- 4、可以建立非阻塞socket吗（fcntl），connect可以是非阻塞吗
- 5、虚函数实现方式
- 6、手写，一个数二进制里面出现1的次数
- 7、LRU怎么实现
- 8、有100w个单词，找到出现频率最高的10个单词（最小堆）
- 9、lua了解吗
- 10、linux，查找一个单词出现的行数，用什么命令
- 11、tcp和udp区别
- 12、有些项目会用udp做传输，但是又有可靠性，这是什么原因（udp比tcp快，tcp的策略太多，不会完全用到）

### 现场二面
- 1、闲聊
- 2、flappybird写了多长时间，手感如何，balabala
- 3、怎么想做http服务器，做了多长时间，代码量多少
- 4、如果是长连接，会不会出现两个线程同时处理同一个连接上来的两个请求，假设处理速度差不多，同时向客户发响应，会有问题吗，怎么解决（）
- 5、什么情况下用多线程（某些请求非常耗费cpu，）
- 6、recv会不会发送数据拷贝
- 7、团队项目多少人，你做的什么工作，做了多长时间
- 8、网易投了吗
- 9、什么游戏玩的多
- 10、为什么想做游戏开发


### 现场三面
- 1、自我介绍，问户口家庭情况
- 2、从你角度看东大和南大学生能力哪个好
- 3、哪些数据结构常用，数据结构对于软件开发有什么意义，能用画画做个比喻吗，数据结构相当于什么，算法相当于什么（算法是画画步骤，数据结构是布局，这里画什么那里画什么？）
- 4、举个例子，怎样找到最快到达的加油站（bfs）
- 5、某公司有数千员工，要坐电梯到各自楼层，两个电梯，怎么设置让员工最快到达（单双层）
- 6、你个人有什么梦想，什么时候想做游戏开发
- 7、服务器用的什么数据库
- 8、毕业之后职业发展目标规划
- 9、实习的目的
- 10、有没有考虑读博
- 11、你对自己时间管理怎么做的
- 12、业余时间爱好特长
- 13、你性格内向吗
- 14、你有没有毕生要追求的目标
- 15、市面上什么游戏你觉得是好游戏


## 阿里
### 电话一面
- 1、自我介绍
- 2、介绍实验室项目，目标什么，做了什么工作，有没有问题是你思考很长时间都没解决，突然有一天豁然开朗，继续做的话你觉得在哪个方面可以做得更好，怎么评价这套系统，核心指标是什么
- 3、介绍下reactor加线程池模型
- 4、有没有调研过现在工业上主要的http服务器有哪些
- 5、为什么不精读一个而是要自己写一个，和其他开源相比有没有发现你写的代码有什么不足的地方
- 6、高性能http服务器上最核心的部分是什么（？？？）
- 7、异步的思想怎么实现
- 8、一个变量在子线程修改会影响主线程的值吗，在父进程修改一个全局变量会影响子进程的值吗，子线程创建会马上创建变量吗（写时复制？）

### 视频二面
- 1、问了些简历上的内容，游戏项目，算法竞赛
- 2、reactor模型是什么意思，和传统的有什么区别（？？？）
- 3、多线程同时从队列里取任务怎么同步，用锁之后对性能有损害吗，用哪些方法减少加锁的代价（无锁队列，减小加锁粒度），原子性操作怎么做到的，Linux下有哪些原子操作（CAS，atomic_int），
- 4、编程，给个自然数n，打印出1到n的全排列，next_permutation怎么实现的，递归版本写一下，你实现的算法复杂度是多少（n^n），有办法降低吗（每次交换两个数位置），swap的代价大吗（inline就没有开销），swap怎么实现的，函数调用的代价大不大，把哪些内容压入栈（下一语句的地址，上下文保存在寄存器，），cpu怎样执行一条指令（对寄存器上的数进行计算），递归栈会溢出吗，多少次会溢出（），一个程序里面有几个栈（线程决定）


### 视频三面
- 1、你在面试过程有什么想法，学到什么
- 2、项目的分工和你扮演的角色，项目目标，过程，还有哪些改进的方式
- 3、你最近用的比较多的3个app，有什么其他的兴趣爱好，有看什么书吗
- 4、有没有经常和同学参加集体活动
- 5、和朋友出去聚会，你觉得你是什么角色
- 6、用三个词形容你自己
- 7、实习的时间地点
- 8、你面过哪些公司，哪家公司比较满意，感兴趣，怎么评价这些公司给你的感受
- 9、毕业后的规划，有什么长期的目标
- 10、你拿到offer排名前三的公司，如果有阿里你会重新排名吗
- 11、有什么想了解的



## 搜狗
### 电话面
- 1、自我介绍
- 2、sizeof class，对齐问题，加个虚函数size会变化吗
- 3、tcp和udp区别，数据完整是什么概念（完整，顺序），为什么数据会丢失，为什么会出现先发后到
- 4、http协议格式
- 5、线程池模型
- 6、epoll和select区别，epoll比select多的事件有哪些
- 7、stl哪些比较熟悉，map数据结构，map有序吗，vector是什么数据结构，根据什么情况确定用vector还是map
- 8、一个class需要实现什么才能满足map的需求
- 9、有一堆url地址，去重（直接比较url很费时，压缩md5）
- 10、Linux用得最多的命令，gdb查看所有线程的堆栈（bt？），怎么调试带参数的程序
- 11、netstat用来看什么信息，recvq，sendq什么意思，在网络过程中是属于什么阶段的数据（内核里？）

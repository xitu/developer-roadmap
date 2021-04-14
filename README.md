
# 一、Go语言的起源、发展以及普及

## 1.  学习Go语言

###  Go语言起源

### Go语言的主要特征与发展的环境

### Go语言常犯错误汇总

###  Golang书籍推荐

  - Go入门指南        比较适合新手，内容相对基础一些
  - Go语言圣经        书如其名
  - Go语言中文网        找对圈子，学的更快
  - 菜鸟教程        这个网站非常适合快速上手某门语言
  - Go语言高级编程        内容适合进阶
  - go语言原本        欧神出品，虽然号称进度只有9.9%/100%，但不妨碍它的优秀，值得一看
  - golang设计模式        设计模式 Golang实现，《研磨设计模式》的golang实现
  -  Go实战开发        作者是著名的 Go 开源项目 beego 的作者，他的最佳实践非常值得阅读
  -  Go palyground        不用搭建本地 Go 环境，在线就编写 Go 的代码

### Go语言开源项目

1. xgen-编写XSD工具基础库，可将XML模式定义为多语言类型或声明的代码
2.  GQLEngine-高性能Go语言的GraphQL服务端落地框架
3. Orange  一款基于Golang语言的Web开发框架
4. Go-admin -基于Golang快速搭建可视化数据管理后台的框架
5. Go-snowflake   Go语言实现的snowflake算法，为分布式系统实现唯一ID，单机测试1s可生成20id
6. KubeVela  一个简单易用且高度可扩展的应用管理平台与核心引擎
7. TiDB   见识过mysql性能瓶颈之后你会想要选择的一款数据库
8. EasyMIDI   EasyMidi是一个简单可靠的库，用于处理标准Midi文件（SMF）。


### Go语言环境安装

下载地址：	<https://www.golangtc.com/download>

GOPATH

-----


# 二、Go工作环境设置

## 编辑器

- Jetbrains GoLand  强烈推荐
- Jetbrains IDEA + go插件
- VS Code
- Atom
- liteide
- Sublime Text

## 依赖管理

- glide
	- 安装：<https://glide.sh/>
	- 初始化
	- 依赖下载
- mod

## Go源码发布

## Go部署

### shell脚本

[如何优雅的通过Shell脚本一键部署GO项目到服务器 ｜Go主题月](https://juejin.cn/post/6943843305750970399)


# 三、包、变量、函数

### 包

[拜拜了，GOPATH君！新版本Golang的包管理入门教程](https://juejin.cn/post/6844903808942735368)

[Go的包管理工具（一）](https://juejin.cn/post/6844903778945237006)

[Go 语言标准库 text/template 包深入浅出](https://juejin.cn/post/6844903762901860360)

[Go 语言闭包详解](https://juejin.cn/post/6844903793771937805)

[Go 包管理工具 govendor 使用指南](https://juejin.cn/post/6844903759886155790)

[Go语言json包的使用技巧 ｜Go主题月](https://juejin.cn/post/6945023713930641445/)


### 第三方包

### 导入语句

#### 分组导入语句

#### 多个导入语句

### 导出名

[Go语法之包、导入包、导出名](https://juejin.cn/post/6844903695893676045)



### 函数

 [[译] 解析 Go 中的函数调用](https://juejin.cn/post/6844903474568642567)

[[译] Go 函数调用 Redux](https://juejin.cn/post/6844903474572820487)

[Go中的init函数](https://juejin.cn/post/6844903864555012104)

[Golang中函数传参存在引用传递吗？](https://juejin.cn/post/6844903618890432520)

[Golang 函数式编程简述](https://juejin.cn/post/6877505132620333064)

[从内存分配策略(堆、栈)的角度分析,函数传递指针真的比传值效率高吗？](https://juejin.cn/post/6844903800042422280)

[一篇文章 说清楚 Go语言里的函数](https://juejin.cn/post/6844904175478767624)

  

### 多返回值

[通过汇编看golang函数的多返回值 | 🏆 技术专题第二期征文](https://juejin.cn/post/6863781364333248525)



### 变量

[Golang环境变量设置详解](https://juejin.cn/post/6844903817071296525)

[Go初始化变量的招式](https://juejin.cn/post/6844903613005824008)

[Golang并发之共享内存变量](https://juejin.cn/post/6844903809139900423)

[Golang从零开始：命名规范、变量和常量](https://juejin.cn/post/6844903789988675597)

[【Go学习之路】Go变量](https://juejin.cn/post/6856783152921346061)

[CGO_ENABLED环境变量对Go静态编译机制的影响](https://juejin.cn/post/6844903619527983111)

[golang面试题：reflect（反射包）如何获取字段tag？为什么json包不能导出私有变量的tag？](https://juejin.cn/post/6844904191358402574)



#### 变量的初始化

#### 短变量声明

[GO的短变量声明](https://juejin.cn/post/6878161651724943368)



### 基本类型

#### bool

#### string

[Go之如何截取string字符串？截取英文与中文字符串](https://juejin.cn/post/6844903796930265096)

[Go系列 string、bytes、rune的区别](https://juejin.cn/post/6844903743524175879)

[详解Go regexp包中 ReplaceAllString 的用法](https://juejin.cn/post/6844903773551230990)

[Go之int整数与string字符串相互转换](https://juejin.cn/post/6844903796913471495)

[golang中你不知道的 string](https://juejin.cn/post/6844904016720199693)

[Go 标准库介绍一: strings](https://juejin.cn/post/6844903465928359944)

[golang的fmt包String(),Error(),Format(),GoString()的接口实现](https://juejin.cn/post/6844903760041345032)



#### int  int8  int16  int32  int64uint uint8 uint16 uint32 uint64 uintptr

[Golang 中 int，int64 和字符串互转（译文）](https://juejin.cn/post/6844904120998952967)

[原来这才是 Go Interface](https://juejin.cn/post/6844903950911553550)

[Golang interface接口深入理解](https://juejin.cn/post/6844903555141222407)

[从goim定制, 浅谈 go interface 解耦合与gRPC](https://juejin.cn/post/6844903828177829896)

[golang面试题：能说说uintptr和unsafe.Pointer的区别吗？](https://juejin.cn/post/6844904178280562701)

[Golang中MulUintptr实现原理](https://juejin.cn/post/6886045069149732877)


#### byte // uint8 的别名

[Go系列 string、bytes、rune的区别](https://juejin.cn/post/6844903743524175879)

[Go之[]byte字节数组与string字符串相互转换](https://juejin.cn/post/6844903796917682189)

[Strings、bytes and runes -- 就要学习 Go 语言](https://juejin.cn/post/6844903745747156999)

[go中的strings, bytes, runes 和 characters](https://juejin.cn/post/6844904114745245709)



####  rune unicode码点 

[Go系列 string、bytes、rune的区别](https://juejin.cn/post/6844903743524175879)

[Golang 中 runes 和 字符串互转（译文）](https://juejin.cn/post/6844904121003147272)

[Strings、bytes and runes -- 就要学习 Go 语言](https://juejin.cn/post/6844903745747156999)

[Golang 中[]byte, string和[]rune的相互转化的底层原理和剖析](https://juejin.cn/post/6931523990280208392)



#### float32 float64

#### complex64 complex128



### 零值
没有明确初始值的变量声明会被赋予他们的零值

[编程书说的“Go程序员应该让聚合类型的零值也具有意义”是在讲什么](https://juejin.cn/post/6844904003482943501)

[Golang 零值、空值与空结构](https://juejin.cn/post/6895231755091968013)


* 零值是
	* 数值类型为0
	* 布尔类型为false
	* 字符串为""（空字符串）
- 零值和空值的关系
- 零值的空值的区别



### 类型转换

[Go基础类型转换](https://juejin.cn/post/6844903973208457224)

[golang中的四种类型转换总结](https://juejin.cn/post/6844904113914789902)

[Golang 中一个 time.Duration 相关类型转换问题](https://juejin.cn/post/6862976040042987527)



### 类型推倒



### 常量

[Golang从零开始（二）：命名规范、变量和常量](https://juejin.cn/post/6844903789988675597)

[Golang学习——常量const和iota](https://juejin.cn/post/6844904145162338317)

[golang进阶一：类型比较，常量，nil](https://juejin.cn/post/6844904167299874830)

### 数值常量

## 流程控制语句：for、if、else、switch、defer

### for

#### for循环

[昨天那个在for循环里append元素的同事，今天还在么？](https://juejin.cn/post/6875102599595425800)

[Golang 高并发编程For循环中使用Goroutine最容易犯的错误](https://juejin.cn/post/6844904133208604679)

[Go语言性能优化- For Range 性能研究](https://juejin.cn/post/6844903696430546952)

[[Golang]这几个for-range的坑，你必须要会呀，铁汁](https://juejin.cn/post/6868963573482127374)


##### 初始化语句

##### 条件表达式

[关于变量在 if-else 条件表达式里的作用域范围](https://juejin.cn/post/6844903605367996424)

##### 后置语句

#### 循环条件


### IF

##### if 的简短语句

##### if 和 else


### switch

[Go 语言流程控制：switch-case](https://juejin.cn/post/6844904145913118728)

[[译] part 10: golang switch 语句](https://juejin.cn/post/6844903827359924237)


switch 的求值顺序



### defer

包含该defer语句的函数执行完毕时，defer后的函数才会被执行 -----------推迟调用<br>
 在一个函数中执行多条defer语句，它们的执行顺序与声明顺序相反

[Go 延迟函数 defer 详解](https://juejin.cn/post/6844903507011567623)

[go 学习笔记之咬文嚼字带你弄清楚 defer 延迟函数](https://juejin.cn/post/6844904000567902216)



- defer 栈
  - 推迟的函数调用会被压入一个栈中。当外层函数返回时，被推迟的函数会按照后进先出的顺序调用。



### 更多类型：struct、slice和映射

#### 指针

* Go 拥有指针。指针保存了值的内存地址。

[Golang研学：在用好Golang指针类型](https://juejin.cn/post/6844903831365648391)

[彻底学会 Go 指针 -- 就要学习 Go 语言](https://juejin.cn/post/6844903734745513991)

[Golang中range指针数据的坑](https://juejin.cn/post/6844903773559619591)

[Golang 指针：使用方法、特点 和 运算](https://juejin.cn/post/6844903725773897742)

[Go之反射实现类型与指针拷贝](https://juejin.cn/post/6844903922205720590)



### 结构体

* 一个结构体（struct）就是一组字段（field）。

[golang | Go语言入门教程——结构体初始化与继承](https://juejin.cn/post/6850418111531712520)

[15. 理解 Go 语言面向对象编程：结构体与继承](https://juejin.cn/post/6844904161616592903)

[包罗万象的结构体 -- 就要学习 Go 语言](https://juejin.cn/post/6844903765103886343)

[Golang自定义结构体转map](https://juejin.cn/post/6855129007193915400)



##### 结构体字段

结构体字段使用点号来引用

[Golang自定义结构体转map](https://juejin.cn/post/6855129007193915400)

##### 结构体指针

结构体字段可以通过结构体指针来访问

##### 结构体声明

结构体声明可以通过直接列出字段的值来新分配一个结构体。

### 数组

* 类型[n]T表示拥有n个T类型的值的数组。

[Go如何对数组切片进行去重](https://juejin.cn/post/6844903967114297352)

[《快学 Go 语言》第 4 课 —— 低调的数组](https://juejin.cn/post/6844903710791843854)

[Go切片与C数组转换](https://juejin.cn/post/6844903921274585095)

Go之[]byte字节数组与string字符串相互转换<https://juejin.cn/post/6844903796917682189>

### 切片

* 每个数组的大小都是固定的。而切片则为数组元素提供动态大小的、灵活的视角。在实践中，切片比数组更常用。

[深度解析 Go 语言中「切片」的三种特殊状态](https://juejin.cn/post/6844903712654098446)

[（正经版）面试官：切片作为函数参数是传值还是传引用？](https://juejin.cn/post/6888117219213967368)

[Go 切片使用注意事项](https://juejin.cn/post/6844903556290445325)

[如何在Go中使用切片容量和长度](https://juejin.cn/post/6844903998734991368)


#### 切片就像引用的数组

* 切片并不直接存储数据，它只是描述了底层数组中的一段。

#### 切片文法

* 切片文法类似于没有长度的数组文法。

#### 切片的默认行为

#### 切片的长度与容量

#### nil切片

[连nil切片和空切片一不一样都不清楚？那BAT面试官只好让你回去等通知了。](https://juejin.cn/post/6882534005410005005)

#### 用make创建切片

#### 切片的切片

切片可包含任何类型，甚至包括其它的切片。

#### 向切片追加元素

#### range

for循环的range形式可遍历切片或映射。



### 映射

[gin 自动映射参数及自动校验](https://juejin.cn/post/6925701771511726093)

[PHP转Go系列：map映射](https://juejin.cn/post/6844903865431638023)

#### 映射的文法

#### 修改映射 



### 函数值

##### 函数的闭包
[Go 语言闭包详解](https://juejin.cn/post/6844903793771937805)

[go 学习笔记之仅仅需要一个示例就能讲清楚什么闭包](https://juejin.cn/post/6844903950504689677)

[GO-三个方面理解闭包](https://juejin.cn/post/6844904047175008263)

[Go 语言中的闭包实现](https://juejin.cn/post/6844903465274048519)





# 四、方法和接口

### 1. 方法

- 指针接收者
- 方法与指针重定向
- 选择值或指针作为接收者



### 接口

[Golang interface接口深入理解](https://juejin.cn/post/6844903555141222407)

[Go 语言接口详解（一）](https://juejin.cn/post/6844903809211170824)

[Go 语言接口详解（二）](https://juejin.cn/post/6844903821416595464)



#### 接口与隐式形式

#### 接口值

#### 底层值为 nil 的接口值

[Go “一个包含nil指针的接口不是nil接口”踩坑](https://juejin.cn/post/6844903905797603335)

#### nil接口值

#### 空接口

[31. 说说 Go 语言中的空接口](https://juejin.cn/post/6844904183770906638)

#### 类型断言

[14. Go 语言中的类型断言是什么？](https://juejin.cn/post/6844904153056034823)

[聊聊golang的类型断言](https://juejin.cn/post/6900192355324952589)

#### 类型选择

#### Stringer



### 错误

[Go语言(golang)的错误(error)处理的推荐方案](https://juejin.cn/post/6844903757101137934)

[Golang error 的突围](https://juejin.cn/post/6844903944490057736)

[[译] Part 31: golang 中的自定义 error](https://juejin.cn/post/6844903810943418375)

[[译] Go 1.13 errors 包错误处理](https://juejin.cn/post/6844903944741896206)



### Reader

[Golang 最细节篇 —— Reader，ReaderAt 的区别，你如果是做存储的，可千万别搞错了；](https://juejin.cn/post/6900534635181113352)

### 图像

[golang 图像验证码](https://juejin.cn/post/6844903541568454670)    转载



# 五、并发

#### 

[Golang 的 协程调度机制 与 GOMAXPROCS 性能调优](https://juejin.cn/post/6844903662553137165)

[Go并发调度器解析之实现一个协程池](https://juejin.cn/post/6844903619163062280)     转载

#### Goroutine

#### Channel

[go语言之行--golang核武器goroutine调度原理、channel详解](https://juejin.cn/post/6844903634497437709)

[Golang —— goroutine（协程）和channel（管道）](https://juejin.cn/post/6844903778617917453)

[深入理解Golang之channel](https://juejin.cn/post/6844904016254599176)

[什么时候用goroutine？什么时候用channel？ ｜Go主题月](https://juejin.cn/post/6943952470993272845)

#### GMP模型

[深入理解Golang之channel](https://juejin.cn/post/6844904016254599176）

[ Golang调度器的GMP模型](https://juejin.cn/post/6879589946982662158)

#### 原子性、可见性、有序性

[Golang 并发编程核心—内存可见性](https://juejin.cn/post/6911126210340716558)

#### Mulex

#### 并发控制

[深入golang之---goroutine并发控制与通信](https://juejin.cn/post/6844903625773285384)

[Go 译文之通过 context 实现并发控制](https://juejin.cn/post/6844903886243758093)

[go并发之goroutine和channel，并发控制入门篇](https://juejin.cn/post/6906408822701719560)



#### 阻塞&非阻塞

[在Golang中各种永远阻塞的姿势](https://juejin.cn/post/6844903598216871943)

[Golang 实现轻量、快速的基于 Reactor 模式的非阻塞 TCP 网络库](https://juejin.cn/post/6844903945907748872)

#### 同步vs异步

[面试官让我用channel实现sync包里的同步锁，是不是故意为难我？](https://juejin.cn/post/6844904164749918216)

[Visual Studio Live Share - 和你的队友同步共享代码，即时编辑](https://juejin.cn/post/6844903511629496328)

[kingtask：一个由 Go 开发的轻量级的异步定时任务系统](https://juejin.cn/post/6844903423624609800)

[用一个简易的 web chat 说说 Python、Golang、Nodejs 的异步](https://juejin.cn/post/6844903485494788103)

#### Select

[深入理解go-channel和select的原理](https://juejin.cn/post/6844903940190912519)

# 六、框架

##  Web框架        

### Revel

### Beego

### Martini

### Gin Gonic
[Go gin框架封装中间件之1：用户角色权限管理中间件 ｜Go主题月](https://juejin.cn/post/6943147832937447431)

[Go gin框架封装中间件之2：操作日志中间件 ｜Go主题月](https://juejin.cn/post/6943503384729583652)

[Go GORM是时候升级新版本了 2.0新特性介绍（1） ｜Go主题月](https://juejin.cn/post/6945404499850854408)

[Go GORM是时候升级新版本了 2.0新特性介绍（2）| Go主题月](https://juejin.cn/post/6946012224573931528)

### Buffalo

### Goji

### Tiger Tonic

### Gocraft

### Mango

## 微服务框架        

###  go-kit 

### Micro

### go-zero

### gRPC
[Go RPC入门指南1：RPC的使用边界在哪里？如何实现跨语言调用？| Go 主题月](https://juejin.cn/post/6946452659159171102)



# 七、优化

#### Go语言测试

#### Go语言性能分析

[go pprof 性能分析](https://juejin.cn/post/6844903588565630983)

[Go 程序性能分析 101](https://juejin.cn/post/6844903495703740424)

[golang 使用pprof和go-torch做性能分析](https://juejin.cn/post/6844903798373089287)

[Go开发web必懂的概念和底层原理，通过对比的方式让大家更好的理解 | Go主题月](https://juejin.cn/post/6950954283068031012)

[多维度思考：如何提高项目的开发时间、提高安全性、提高运行速度，从多个维度带来的一些思考。 | Go主题月](https://juejin.cn/post/6950959850994008094)


# 八、问题排查



# 九、Golang面试

[进程 线程 协程 各自的概念以及三者的对比分析 | Go主题月](https://juejin.cn/post/6950952506176471071)




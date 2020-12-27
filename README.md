# Golang开发手记


用Go语言做开发，在这个Repository里整理一些常用的案例，计划慢慢积累作为以后开发的CookBook。

更多原创技术文章，关注公众号「网管叨bi叨」

## 目录
- 初始化
  - [Go应用初始化工作的执行顺序](https://github.com/kevinyan815/gocookbook/issues/24)
- 字符串
  - [操作中文字符串](https://github.com/kevinyan815/gocookbook/issues/11)
- 数组
  - [数组的上限推导和越界检查](https://github.com/kevinyan815/gocookbook/issues/37)
- Slice切片
  - [声明和初始化](https://github.com/kevinyan815/gocookbook/issues/3)
  - [追加和删除元素](https://github.com/kevinyan815/gocookbook/issues/4)
  - [过滤重复元素](https://github.com/kevinyan815/gocookbook/issues/5)
  - [排序结构体切片](https://github.com/kevinyan815/gocookbook/issues/12)
  - [切片并非引用类型](https://github.com/kevinyan815/gocookbook/issues/38)
- Map
  - [声明和初始化](https://github.com/kevinyan815/gocookbook/issues/6)
  - [不要向nil map写入键值](https://github.com/kevinyan815/gocookbook/issues/7)
  - [修改map](https://github.com/kevinyan815/gocookbook/issues/8)
  - [遍历map](https://github.com/kevinyan815/gocookbook/issues/15)
- 读写数据
  - [编码JSON](https://github.com/kevinyan815/gocookbook/issues/2)
  - [解码JSON](https://github.com/kevinyan815/gocookbook/issues/1)
  - [逐行读取文件](https://github.com/kevinyan815/gocookbook/issues/13)
  - [Go语言文件操作大全](https://mp.weixin.qq.com/s/dQUEq0lJekEUH4CHEMwANw)
- [Range 迭代](https://github.com/kevinyan815/gocookbook/issues/15)
- 标准库
  - [正则表达式](https://github.com/kevinyan815/gocookbook/issues/9)
  - [time](https://github.com/kevinyan815/gocookbook/issues/14)
- 命令行
  - [命令行flag](https://github.com/kevinyan815/gocookbook/issues/36)
- 并发编程
  - [用WaitGroup进行协同等待](https://github.com/kevinyan815/gocookbook/issues/34)
  - [Reset计时器的正确姿势](https://github.com/kevinyan815/gocookbook/issues/17)
  - [结合cancelCtx, Timer, Goroutine, Channel的一个例子](https://github.com/kevinyan815/gocookbook/issues/18)
  - [使用WaitGroup, Channel和Context打造一个并发用户标签查询器](https://github.com/kevinyan815/gocookbook/issues/21)
  - [使用sync.Cond实现一个有限容量的队列](https://github.com/kevinyan815/gocookbook/issues/22)
  - [使用信号量控制有限资源的并发访问](https://github.com/kevinyan815/gocookbook/issues/30)
  - [使用Chan扩展互斥锁的功能](https://github.com/kevinyan815/gocookbook/issues/25)
  - [用SingleFlight合并重复请求](https://github.com/kevinyan815/gocookbook/issues/31)
  - [CyclicBarrier 循环栅栏](https://github.com/kevinyan815/gocookbook/issues/32)
  - [Go并发编程同步原语之ErrorGroup](https://github.com/kevinyan815/gocookbook/issues/35)
- 线上问题解决实录
  - [重定向运行时panic到日志文件](https://github.com/kevinyan815/gocookbook/issues/19)
  - [用Go的交叉编译和条件编译让自己的软件包运行在多平台上](https://github.com/kevinyan815/gocookbook/issues/20)
- 一些有意思的小程序
  - [一个简单的概率抽奖工具](https://github.com/kevinyan815/gocookbook/issues/23)
  - [限流算法之计数器](https://github.com/kevinyan815/gocookbook/issues/29)
  - [限流算法之滑动窗口](https://github.com/kevinyan815/gocookbook/issues/26)
  - [限流算法之漏桶](https://github.com/kevinyan815/gocookbook/issues/28)
  - [限流算法之令牌桶](https://github.com/kevinyan815/gocookbook/issues/27)
  - [并发趣题--H2O制造工厂](https://github.com/kevinyan815/gocookbook/issues/33)

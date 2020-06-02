# <center>MyBatis 源码解析 </center>

在阅读MyBatis 源码之前，不妨先问自己两个问题：
1. 为什么要阅读优秀开源软件的源码？
2. 为什么要阅读 MyBatis 的源码？

如果上面的两个问题，你心中还没有一个明朗的答案，不妨先听听笔者自己的想法。
事有先后，笔者先自问自答第一个问题：为什么要阅读源码？
+ 不妨回想一下初学写作的时候，我们是如何学会写作的：学会基本的拼音 -> 大量的背诵、听写、默写 —> 大量的仿写 -> 大量的名著阅读 —> 自由写作
+ 不妨再回想一下初学编程的时候，我们是如何学会编程的：学会基本的语法 -> 大量的 “hello world” -> 参与小的工程项目 -> 阅读优秀的代码实例 -> 拆轮子与造轮子 -> 参与复杂项目 -> 学会架构设计

有没有一种似曾相识的感觉！原来写作与编程的学习过程，有诸多相似之处。所以回过头来，我们可以试着回答一下第一个问题：为什么要阅读优秀开源软件的源码？
> 阅读优秀的开源软件源码能培养阅读者的“代码审美”，并且可以积累原始的“代码模板（类比写作好词好句）”，日积月累，会提高阅读者的编程能力；

> 阅读优秀的开源软件也可以打破隔膜，让阅读者知其然并知其所以然，拒绝“黑盒”。

再尝试回答第二个问题：为什么要阅读 MyBastis 的源码？
> 首先这个问题应该只针对以 Java 为主语言的后端开发者，不可否认的是，国内的 Java 开发者对持久层框架的技术选型基本倾向于 MyBatis，所以 MyBatis 在受众与使用比例上，都是很流行的，所以深入了解 MyBatis 的源码是有现实基础的；

> 此外，MyBatis 本身作为一个轻量级的框架，本身并不复杂，对初学者的门槛也不算高，适合第一次接触开源框架的源码阅读爱好者。


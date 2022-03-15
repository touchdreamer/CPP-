# C/C++后台开发工程师学习路线图

## C/C++语言基础知识整理

### 常见问题整理
- 指针与引用的区别，C 与 C++ 的区别，struct 与 class 的区别
- struct 内存对齐问题，sizeof 与 strlen 区别
- 面向对象的三大特性：封装、继承、多态
- 类的访问权限：private、protected、public
- 类的构造函数、析构函数、赋值函数、拷贝函数
- 移动构造函数与拷贝构造函数对比
- 内存分区：全局区、堆区、栈区、常量区、代码区
- 虚函数实现动态多态的原理、虚函数与纯虚函数的区别
- 深拷贝与浅拷贝的区别
- 一些关键字：static, const, extern, volatile 等
- 四种类型转换：static_cast、dynamic_cast、const_cast、reinterpret_cast
- 静态与多态：重写、重载、模板
- 静态多态和动态多态
- 四种智能指针及底层实现：auto_ptr、unique_ptr、shared_ptr、weak_ptr
- 右值引用、完美转发（c++11）
- std::move函数
- 一些重要的 STL：vector, list, map, set 等。
- 容器对比，如 map 与 unordered_map 对比，set 与 unordered_set 对比，vector 与 list 比较等。
- 智能指针
- C 语言的内存机制
- malloc free new delete 区别
- 

### C++相关书籍整理
#### 基础学习
- <C++ Primer>
- 
#### 进阶学习
- <深度探索C++对象模型>
- Effective C++
- Effective STL
- <STL 源码剖析>
- B 站侯杰老师的视频

## 操作系统

### 操作系统常见问题整理
- 系统调用过程
- 进程线程区别
- 进程通信方式
- 线程通信方式
- 进程上下文切换方式
- 线程上下文切换方式
- 同步、异步、阻塞、非阻塞
- 静态链接和动态链接
- 虚拟内存
- 用户态和内核态的区别以及切换代价
- 互斥锁和自旋锁底层区别
- 孤儿进程和僵尸进程
- 虚拟内存
- 异常处理（中断、陷阱、故障、终止）
- 操作系统内存管理
- 虚拟文件系统（VFS）
- 银行家算法
- 实现一个 LRU cache
- 内存泄露的场景、处理方法

### 书籍推荐
- 鸟哥 linux 私房菜
- 深入理解计算机操作系统(CSAPP)
- 现代操作系统
- Linux系统编程接口
- Linux内核设计与实现

## 网络编程（涉及计算机网络）
### 计算机网络常见问题整理
- TCP基础知识
  -  TCP 如何实现可靠通信
  -  TCP 三次握手，四次挥手
  -  TCP 流量控制，拥塞避免
  -  SYN 泛洪
  -  粘包和分包
  -  timewait 等待2MSL原因
- 为什么要有 mac 地址，mac 地址从何而来
- IO 多路复用（select,poll,epoll）
- 在浏览器数据一个网址所经历的过程
- 边缘触发和水平触发
- 基于事件驱动的reactor模式
- 反向代理、负载均衡

### 书籍推荐
- UNP（UNIX网络编程）
- APUE（UNIX 高级环境编程）
- 《TCP/IP详解卷1：协议》
- 《图解HTTP》
- 《Linux高性能服务器编程》
- Linux多线程服务器端编程
- 深入理解 nginx

## 数据结构与算法
- 堆排序
- 单调栈、单调队列（接雨水、最大矩阵面积）
- 

## 数据库
### Mysql
- 一个 sql 语句，数据库中做了什么？
- 

### Redis
- 五种数据结构
- 持久化（AOF、RDB）
- 数据分片
- 主从复制
- redis 集群


# 小项目
- 写一个文件事件处理器
- 写一个网络库（参考 muoduo）



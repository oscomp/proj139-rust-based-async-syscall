# proj139-rust-based-async-syscall
基于Rust的异步系统调用设计和实现


### 项目描述

基于硬件或模拟器提供的用户态中断机制，对传统操作系统中同步系统系统调用进行改造成异步方式，从而提高并发执行性能；基于Rust语言的异步机制封装出方便易用的Rust语言异步系统调用库，方便应用程序的开发。

### 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

向勇

* github [https://github.com/xyongcn](https://github.com/xyongcn)
* email [xyong@tsinghua.edu.cn](mailto:xyong@tsinghua.edu.cn)

### 难度

高

### 特征

* 用户态中断
* Rust

### License

* GPL3

### 预期目标

* 把kprobe和eBPF写成独立的库，以支持对基于Rust语言的OS使用
* 

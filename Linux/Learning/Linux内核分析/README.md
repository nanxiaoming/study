关于《Linux内核分析》MOOC课程：http://mooc.study.163.com/course/USTC-1000029000

github: https://github.com/linmufeng/LinuxKernel

该课基于X86 & Linux

第一周：计算机是如何工作的？

- 存储程序计算机工作模型
- 32位X86汇编基础
- 反汇编一个简单的C程序

第二周：操作系统是如何工作的？

- 函数调用堆栈
- 借助Linux内核部分源代码模拟存储程序计算机工作模型及时钟中断
- 构造一个简单的操作系统内核

第三周：构造一个简单的Linux系统MenuOS

- Linux内核源代码导读
- 构造一个简单的Linux系统
- 跟踪调试Linux内核的启动过程

第四周：扒开系统调用的三层皮

- 使用库函数触发一个系统调用
- C代码中嵌入汇编代码的写法
- 使用嵌入式汇编代码触发同一个系统调用
- 系统调用在内核代码中的处理过程

第五周：程序和进程

- 程序的编译、链接和可执行文件格式
- 进程的描述和程序的装载

第六周：进程的执行和进程的切换

- 用户态堆栈和内核态堆栈
- 进程上下文的保存和恢复
- 进程切换的关键代码switch_to分析

第七周：Linux内核的实质和Linux系统的一般执行过程

- 内核执行路径的集合——中断（异常）处理过程的集合
- Linux系统的一般执行过程

第八周：Linux系统架构和执行过程概览

- Linux系统架构
- Linux执行过程概览

# docker-DIY

## Linux Namespace介绍
`Linux Namespace`是`Kernel`的一个功能
* `UTS Namespace`: 主要用来隔离`nodename`和`domainname`两个系统标识
* `IPC Namespace`: 用来隔离`System V IPC`和`POSIX message queues`
* `PID Namespace`: 是用来隔离进程`ID`的
* `Mount Namespace`: 用来隔离各个进程看到的挂载点视图
* `User Namespace`: 主要是隔离用户的用户组`ID`
* `Network Namespace`: 是用来隔离网络设备、`IP`地址端口等网络栈的`Namespace`
## Linux Cgroups介绍
`Linux Cgroups（Control Groups）`提供了对一组进程及将来子进程的资源限制、控制和统计的能力，这些资源包括CPU、内存、存储、网络等

# C++静态服务器
# 使用方法
## 开发环境
*ubuntu18.04+codeblocks16.01+g++7*
## 命令
cd 到根目录
make
./a.out
# 主要技术
__1 实现了线程池__
__2 用双向链表了实现了定时器，用于处理超时的长连接__
__3 使用了智能锁等RAII技术__
__4 使用了epoll技术__
__5 采用reactor模型__
# 项目目的
主要目的是在学习之后想写写代码试试

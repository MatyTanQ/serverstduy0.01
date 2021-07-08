# v1 实现一个简单小型http服务器 
# server_study c++
- 记录自己学习一个项目
- 主要是根据GitHub上面的项目学习的@qinguoyi以及陈硕muduo的思想学习,以及游双的高性能服务器编程
希望自己能够坚持学习下去，
## 准备和目标
- 
- 利用已经看的《高性能服务器编程》方法，相当于整理和复习
- 为muduo框架学习打下基础，在边学习的过程中利用学习的知识慢慢理清项目的开发，学习多线程网络编程的思想
- MattWeb小型网络库
- 实际用了15天，同时还不是很透彻~很多问题还没想明白


## day1 util相关内容实现
- 封装mutex，condition等.利用RAII思想封装锁 完成
- 创建socket工作，连接以及监听的fd函数。（不写成类） 完成
- 安装boost 完成
- 编写测试类

## day2 线程池实现

- 编写健壮性工具
- 测试连接工具
- 线程池实现

## day3 epoll io复用类实现
- 还没想好怎么放
## day4 http解析，数据库连接


## day5 定时器
- 定时器，利用升序链表实现
## day6 异步日志
- 实现了Blockqueue（生产者消费者模型）
- 同步没有用信号量，用了封装的条件变量和互斥锁
- 
## day7 sqlpool server类

- sqlpool类使用单例模式
- 利用模板，将http_conn作为模板，传递给线程池，让线程池中的work进行任务




根据陈硕书籍来修改

v2

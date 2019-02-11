# WEB_PICTURE
使用epoll 和线程池实现简单的图片浏览服务器

运行服务器:

```
changke@King:~/网络编程/WEB_PICTURE/webserver$ make
g++ -c func.cpp -lpthread -g
g++ -c ThreadPool.cpp -lpthread -g
g++ main.cpp func.o ThreadPool.o -o main -lpthread -g
changke@King:~/网络编程/WEB_PICTURE/webserver$ ./main 127.0.0.1 2345

```


实现效果:
<a href="https://blog.csdn.net/qq_41681241/article/details/86907477">喳喳班的csdn</a>

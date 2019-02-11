# WEB_PICTURE
使用epoll 和线程池实现简单的图片浏览服务器
对于html文件,mp3文件,视频文件等都可作处理,初级性能不是很稳定,尝试显示图片还行吧,其他还没试!

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
